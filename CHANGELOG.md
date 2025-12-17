# Changelog

All notable changes to this project will be documented in this file.

## [4.72.7] - 2025-12-17

### Changed
- Updated all packages to version 4.72.7 for consistency across the entire library

## [4.72.6] - 2025-12-17

### Fixed
- **VS2013 Theme**: Fixed Document TabItem style (ItemContainerStyle) to use correct border resource keys
  - Line 325: Changed BorderBrush from self-binding to `DocumentWellTabUnselectedBorder`
  - Line 343: Added BorderBrush setter for active state using `DocumentWellTabSelectedActiveBorder`
  - Line 355: Added BorderBrush setter for inactive state using `DocumentWellTabSelectedInactiveBorder`
  - Line 375: Added BorderBrush setter for hovered state using `DocumentWellTabUnselectedHoveredBorder`
  - This ensures document tab borders use the customizable border resource keys instead of binding to background

## [4.72.5] - 2025-12-17

### Added
- **VS2013 Theme**: Added unique AutomationProperties.Name to all TabItem styles for improved accessibility
  - Document TabItem: "Document Tab - {Title}"
  - Tool Window TabItem: "Tool Window Tab - {Title}"
  - LayoutDocumentTabItem: "Layout Document Tab - {Title}"
  - LayoutAnchorableTabItem: "Layout Anchorable Tab - {Title}"

## [4.72.4] - 2025-12-17

### Fixed
- **VS2013 Theme**: Fixed DocumentPaneControl template to use correct border resource keys
  - Line 220: Changed BorderBrush from `DocumentWellTabSelectedActiveBackground` to `DocumentWellTabSelectedActiveBorder`
  - Line 287: Changed BorderBrush from `DocumentWellTabSelectedInactiveBackground` to `DocumentWellTabSelectedInactiveBorder`
  - This fixes the issue where the tab container border was using Background keys instead of the newly created Border keys

## [4.72.3] - 2025-12-17

### Added
- **VS2013 Theme**: Added dedicated border resource keys for document tabs
  - `DocumentWellTabSelectedActiveBorder` - Border color for active selected tab
  - `DocumentWellTabSelectedInactiveBorder` - Border color for inactive selected tab
  - `DocumentWellTabUnselectedBorder` - Border color for unselected tab
  - `DocumentWellTabUnselectedHoveredBorder` - Border color for hovered unselected tab
- Tab borders can now be fully customized through resource dictionaries
- Border resource keys implemented in all three VS2013 color schemes (Dark, Light, Blue)

### Changed
- Updated `Generic.xaml` control template to use new border resource keys
- Updated `ResourceKeys.cs` with new ComponentResourceKey definitions
- Updated all VS2013 theme brush files (DarkBrushs.xaml, LightBrushs.xaml, BlueBrushs.xaml)

## [4.72.2] - 2025-12-17

### Changed
- Updated target frameworks to net48, net8.0-windows, net10.0-windows
- Removed deprecated framework targets (net40, netcoreapp3.0, net5.0-windows)
- All packages now support modern .NET frameworks

## [4.72.1] - Previous Release

See git history for earlier changes.
