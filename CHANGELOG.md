# Changelog

All notable changes to this project will be documented in this file.

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
