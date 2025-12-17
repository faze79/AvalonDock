| Downloads                                                                                                                                               | NuGet Packages
| :------------------------------------------------------------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.svg)](http://nuget.org/packages/Dirkster.AvalonDock)                                      | [Dirkster.AvalonDock](http://nuget.org/packages/Dirkster.AvalonDock)
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.Aero.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Aero)              | [Dirkster.AvalonDock.Themes.Aero](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Aero)
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.Expression.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Expression)  | [Dirkster.AvalonDock.Themes.Expression](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Expression)
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.Metro.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Metro)            | [Dirkster.AvalonDock.Themes.Metro](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Metro)
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.VS2010.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.VS2010)          | [Dirkster.AvalonDock.Themes.VS2010](http://nuget.org/packages/Dirkster.AvalonDock.Themes.VS2010)
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.VS2013.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.VS2013)          | [Dirkster.AvalonDock.Themes.VS2013](http://nuget.org/packages/Dirkster.AvalonDock.Themes.VS2013) (see [Wiki](https://github.com/Dirkster99/AvalonDock/wiki/WPF-VS-2013-Dark-Light-Demo-Client) )

![Net48](https://badgen.net/badge/Framework/.Net&nbsp;4.8/blue) ![Net8](https://badgen.net/badge/Framework/.NET&nbsp;8/blue) ![Net10](https://badgen.net/badge/Framework/.NET&nbsp;10/blue)

## Master Branch
[![Build status](https://ci.appveyor.com/api/projects/status/kq2wyupx5hm7fok2/branch/master?svg=true)](https://ci.appveyor.com/project/Dirkster99/avalondock/branch/master)[![Release](https://img.shields.io/github/release/Dirkster99/avalondock.svg)](https://github.com/Dirkster99/avalondock/releases/latest)&nbsp;[Continuous Integration](https://ci.appveyor.com/project/Dirkster99/AvalonDock/build/artifacts)

<a href="https://github.com/Dirkster99/AvalonDock/issues">
    <img src="https://img.shields.io/github/issues-raw/Dirkster99/AvalonDock.svg?style=flat-square">
  </a>
  <a href="https://github.com/Dirkster99/AvalonDock/issues">
    <img src="https://img.shields.io/github/issues-closed-raw/Dirkster99/AvalonDock.svg?style=flat-square">
  </a><br/>

<a href="https://github.com/Dirkster99/AvalonDock/issues">
    <img src="https://img.shields.io/github/issues-pr-raw/Dirkster99/AvalonDock.svg?style=flat-square">
  </a>
  <a href="https://github.com/Dirkster99/AvalonDock/issues">
    <img src="https://img.shields.io/github/issues-pr-closed-raw/Dirkster99/AvalonDock.svg?style=flat-square">
  </a>
  
# AvalonDock
Support this project with a :star: -report an issue, or even better, place a pull request :mailbox: :blush:

My projects <a href="https://dirkster99.github.io/Edi/">Edi</a>, <a href="https://github.com/Dirkster99/Aehnlich">Aehnlich</a>, and [many others](https://github.com/search?p=4&q=%22dirkster.avalondock%22&type=Code) (open source or commercial) are powered by this project.

AvalonDock is a WPF Document and Tool Window layout container that is used to arrange documents
and tool windows in similar ways than many well known IDEs, such as, Eclipse, Visual Studio,
PhotoShop and so forth. Here are some CodeProject articles:

* [AvalonDock [2.0] Tutorial Part 1 - Adding a Tool Window](https://www.codeproject.com/Articles/483507/AvalonDock-Tutorial-Part-Adding-a-Tool-Windo)
* [AvalonDock [2.0] Tutorial Part 2 - Adding a Start Page](https://www.codeproject.com/Articles/483533/AvalonDock-Tutorial-Part-Adding-a-Start-Page)
* [AvalonDock [2.0] Tutorial Part 3 - AvalonEdit in AvalonDock](https://www.codeproject.com/Articles/570313/AvalonDock-Tutorial-Part-AvalonEdit-in-Avalo)
* [AvalonDock [2.0] Tutorial Part 4 - Integrating AvalonEdit Options](https://www.codeproject.com/Articles/570324/AvalonDock-Tutorial-Part-Integrating-AvalonE)
* [AvalonDock [2.0] Tutorial Part 5 - Load/Save Layout with De-Referenced DockingManager](https://www.codeproject.com/Articles/719143/AvalonDock-Tutorial-Part-Load-Save-Layout)

This repository contains **additional bug fixes and a feature added** fork for:
xceedsoftware/wpftoolkit version **3.2-3.6**. Version 4.0 and later are developed indepentently, which is why this library (version 4.0 and later) uses the namespaces and library names that were used in AvalonDock 2.0 and earlier versions. But most importantly, the usage of this AvalonDock project remains free for both, commercial and open source users.

There is also an open source repository https://github.com/dotnetprojects/WpfExtendedToolkit with a fixed and stable version of all other (other than AvalonDock) components from the WPFToolKit.

Be sure to checkout the <a href="https://github.com/Dirkster99/AvalonDock/wiki">Wiki for more details</a>.

## Building AvalonDock from Source

This project supports multitargeting frameworks (.NET 4.8, .NET 8, .NET 10). This means that it requires
Visual Studio 2022 or better to build.

# Feature Added - Dark and Light VS 2013 Theme

Please review the <a href="https://github.com/Dirkster99/AvalonDock/wiki">Project Wiki</a> to see more demo screenshots.
All screenshots below are from the <a href="https://github.com/Dirkster99/MLib">MLib</a> based VS 2013 Dark (Accent Color Gold)/Light (Accent Color Blue) theme on Windows 10. Similar theming results should be possible with other theming libraries since the implementation follow these <a href="https://www.codeproject.com/Articles/1236588/File-System-Controls-in-WPF-Version-III">guidelines</a>.

The Docking Buttons are [defined in XAML](https://github.com/Dirkster99/AvalonDock/wiki/OverlayWindow), which ensures a good looking image on all resolutions, even 4K or 8K, and enables us to color theme consistently with the Window 10 <b>Accent Color</b>.

<table width="100%">
   <tr>
      <td>Description</td>
      <td>Dark</td>
      <td>Light</td>
   </tr>
   <tr>
      <td>Dock Document</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/DockDocument.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/DockDocument.png" width="400"></td>
   </tr>
   <tr>
      <td>Dock Document</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/DockDocument_1.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/DockDocument_1.png" width="400"></td>

   </tr>
   <tr>
      <td>Dock Tool Window</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/DockToolWindow.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/DockToolWindow.png" width="400"></td>
   </tr>
   <tr>
      <td>Document</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/Document.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/Document.png" width="400"></td>
   </tr>
   <tr>
      <td>Tool Window</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/ToolWindow.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/ToolWindow.png" width="400"></td>
   </tr>
</table>

## Theming

Using the *AvalonDock.Themes.VS2013* theme is very easy with *Dark* and *Light* themes.
Just load *Light* or *Dark* brush resources in you resource dictionary to take advantage of existing definitions.

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/AvalonDock.Themes.VS2013;component/DarkBrushs.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/AvalonDock.Themes.VS2013;component/LightBrushs.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

These definitions do not theme all controls used within this library. You should use a standard theming library, such as:
- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro),
- [MLib](https://github.com/Dirkster99/MLib), or
- [MUI](https://github.com/firstfloorsoftware/mui)

to also theme standard elements, such as, button and textblock etc.

# Mile Stone History

## Version 4.72.7

### Changed
- Updated all packages to version 4.72.7 for consistency across the entire library

## Version 4.72.6

### Fixed
- **VS2013 Theme**: Fixed Document TabItem style (ItemContainerStyle) to use correct border resource keys
  - Line 325: Changed BorderBrush from self-binding to `DocumentWellTabUnselectedBorder`
  - Line 343: Added BorderBrush setter for active state using `DocumentWellTabSelectedActiveBorder`
  - Line 355: Added BorderBrush setter for inactive state using `DocumentWellTabSelectedInactiveBorder`
  - Line 375: Added BorderBrush setter for hovered state using `DocumentWellTabUnselectedHoveredBorder`
  - This ensures document tab borders use the customizable border resource keys instead of binding to background

## Version 4.72.5

### Added
- **VS2013 Theme**: Added unique AutomationProperties.Name to all TabItem styles for improved accessibility
  - Document TabItem: "Document Tab - {Title}"
  - Tool Window TabItem: "Tool Window Tab - {Title}"
  - LayoutDocumentTabItem: "Layout Document Tab - {Title}"
  - LayoutAnchorableTabItem: "Layout Anchorable Tab - {Title}"

## Version 4.72.4

### Fixed
- **VS2013 Theme**: Fixed DocumentPaneControl template to use correct border resource keys
  - Line 220: Changed BorderBrush from `DocumentWellTabSelectedActiveBackground` to `DocumentWellTabSelectedActiveBorder`
  - Line 287: Changed BorderBrush from `DocumentWellTabSelectedInactiveBackground` to `DocumentWellTabSelectedInactiveBorder`
  - This ensures the tab container border (the underline under all tabs) uses the correct customizable border keys

## Version 4.72.3

### Added
- **VS2013 Theme**: Added dedicated border resource keys for document tabs, enabling full customization of tab borders
  - `DocumentWellTabSelectedActiveBorder` - Border color for active selected tab
  - `DocumentWellTabSelectedInactiveBorder` - Border color for inactive selected tab
  - `DocumentWellTabUnselectedBorder` - Border color for unselected tab
  - `DocumentWellTabUnselectedHoveredBorder` - Border color for hovered unselected tab
- Border resource keys implemented in all three VS2013 color schemes (Dark, Light, Blue)

### Changed
- Updated target frameworks from `net40`, `netcoreapp3.0`, `net5.0-windows` to `net48`, `net8.0-windows`, `net10.0-windows`
- All packages now support modern .NET frameworks

### Usage Example
```xaml
<ResourceDictionary xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
                    xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
                    xmlns:reskeys="clr-namespace:AvalonDock.Themes;assembly=AvalonDock.Themes.VS2013">

    <!-- Customize active tab border -->
    <SolidColorBrush x:Key="{x:Static reskeys:ResourceKeys.DocumentWellTabSelectedActiveBorder}"
                     Color="Red" />
</ResourceDictionary>
```

## Version 4.72.2

### Changed
- Updated target frameworks to net48, net8.0-windows, net10.0-windows
- Removed deprecated framework targets (net40, netcoreapp3.0, net5.0-windows)
- All packages now support modern .NET frameworks

## Version 4.72.1

See git history for earlier changes.

## Version 4.72.0

- [#436 Changed how the next active document is picked on document close.](https://github.com/Dirkster99/AvalonDock/pull/436) (thanx to [FredrikS fredriks123](https://github.com/fredriks123))
- [#438 NullCheck for DragPoint](https://github.com/Dirkster99/AvalonDock/pull/438) (thanx to [Ben bbuerger](https://github.com/bbuerger))
- [#423 issue #422 DockingManager.LayoutItemTemplateSelector is applied twice because...](https://github.com/Dirkster99/AvalonDock/pull/423) (thanx to [Mona04](https://github.com/Mona04))
- [#425 Fix: Potential NRE on app close](https://github.com/Dirkster99/AvalonDock/pull/425) (thanx to [Khaos66](https://github.com/Khaos66))
- [#427 Fix floating windows still created twice](https://github.com/Dirkster99/AvalonDock/pull/427) (thanx to [Khaos66](https://github.com/Khaos66))
- [Add DockingManager.ShowNavigator](https://github.com/Dirkster99/AvalonDock/pull/428) (thanx to [Calum Robinson](https://github.com/calumr))
- [#431 Fix unwanted group orientation change when using mixed orientation](https://github.com/Dirkster99/AvalonDock/pull/431) (thanx to [KuroiRoy](https://github.com/KuroiRoy))

## More Patch History
Please review the **Path History** for more more information on patches and feaures in <a href="https://github.com/Dirkster99/AvalonDock/wiki/Patch-History">previously released versions of AvalonDock</a>.
