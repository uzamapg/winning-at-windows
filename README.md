<h1 align="center">
  <img src="./images/trophy-small.png" width="40" alt="trophy" />
  <br />
  winning-at-windows
</h1>

<p align="center">
  <b>Curated Windows 11 software, tweaks, and quality-of-life hacks.</b><br />
  <sub>Personal picks — not a comprehensive database. Your mileage may vary.</sub>
</p>

<p align="center">
  <a href="deprecated.md">Deprecated picks (previous rotation)</a>
</p>

---

## Table of Contents

| # | Section | Focus |
|---|---------|-------|
| 1 | [Ricing](#-ricing-appearance-customization) | Visual customization & theming |
| 2 | [System Maintenance](#-system-maintenance-and-optimization) | Cleanup, optimization & backups |
| 3 | [Usability / QoL](#-usability--quality-of-life) | Productivity & workflow |
| 4 | [Minimalist Apps](#-apps-for-minimalists) | Lightweight alternatives |
| 5 | [Icons & Art](#-icons-and-other-art) | Icons, wallpapers, cursors |
| 6 | [Windows Hacks](#-windows-settings-and-hacks) | Registry tricks & settings |
| 7 | [Other Resources](#-other-resources) | Community lists & forums |

---

## Ricing (appearance customization)

> Visual mods, themes, docks, blur effects, and everything that makes Windows feel *yours*.

### General Customization

| Tool | What it does |
|------|-------------|
| [**Windhawk**](https://windhawk.net/) | Ever-expanding marketplace of free Windows mods. Stable, light on resources. The [Resource Redirect mod](https://windhawk.net/mods/icon-resource-redirect) is the easiest way to replace system icons. |
| [**Stardock**](https://www.stardock.com/) | Suite of tools: [IconPackager](https://www.stardock.com/products/iconpackager/), [WindowFX](https://www.stardock.com/products/windowfx/) (window effects), [TouchTasks](https://www.stardock.com/products/touchtasks/) (corner gestures), [Start11](https://www.stardock.com/products/start11/) (start menu layouts). |
| [**StartAllBack**](https://www.startallback.com/) | Alternative start menu for Win11. |
| [**Open-Shell**](https://github.com/Open-Shell/Open-Shell-Menu) | Classic start menu, open source. |
| [**WinPaletter**](https://github.com/Abdelrhman-AK/WinPaletter) | Accent colors, sounds, icons, fonts — all in one. |
| [**No!! Meiryo UI**](https://github.com/Tatsu-syo/noMeiryoUI) | Change Windows system fonts with fine-grained control. |
| [**SecureUxTheme**](https://github.com/namazso/SecureUxTheme) | Apply custom themes without modifying system files. No reboot needed. |

### Docks & Desktop

| Tool | What it does |
|------|-------------|
| [**MyDockFinder**](https://store.steampowered.com/app/1787090/MyDockFinder/) | Mac-like dock and Finder bar. Pair with [Tray Weather](https://github.com/FelixdelasPozas/TrayWeather) for a weather icon. |
| [**WinDynamicDesktop**](https://github.com/t1m0thyj/WinDynamicDesktop) | Wallpaper that changes with time of day. |
| [**Wallpaper Engine**](https://www.wallpaperengine.io/en) | Animated wallpapers. |
| [**Lively Wallpaper**](https://www.rocksdanister.com/lively/) | Animated wallpapers (open source). |
| [**Rainmeter**](https://www.rainmeter.net/) | Desktop widgets. Browse skins on [deviantArt](https://www.deviantart.com/). Grab [RainRez](https://forum.rainmeter.net/viewtopic.php?f=18&t=10471&hilit=rainrez) if you switch resolutions often. |

<details>
<summary><b>Rainmeter skins worth checking</b></summary>

- [**Droptop**](https://github.com/Droptop-Four) — macOS-style menu bar. Even better with [Yaron's System Monitor](https://github.com/Yaron2334/SystemMonitor/) (+ [HWiNFO](https://www.hwinfo.com/)).
- [**Omnimo**](https://omnimo.info/), [**Big Sur**](https://www.deviantart.com/fediafedia/art/Big-Sur-1-0-BETA-for-Rainmeter-846882462?comment=1%3A846882462%3A4964685064), [**Longhorn Sidebar**](https://www.deviantart.com/fediafedia/art/Longhorn-Sidebar-for-Rainmeter-947066452) — popular suites by [fediafedia](https://fediafedia.com/).
- [**MontereyRainmeter**](https://github.com/creewick/MontereyRainmeter) — Mac-style widgets.
- [**Jax / Jaxcore**](https://jaxcore.app/) — pushing Rainmeter to its limits. [YourFlyouts](https://www.deviantart.com/jaxoriginals/art/919259685) is a great ModernFlyouts alternative.

</details>

### Blur & Transparency

| Tool | What it does |
|------|-------------|
| [**ExplorerBlurMica**](https://github.com/Maplespe/ExplorerBlurMica) | Background blur for Explorer windows. |
| [**TranslucentFlyouts**](https://github.com/ALTaleX531/TranslucentFlyouts) | Background blur for context menus. |
| [**RoundedTB**](https://github.com/RoundedTB/RoundedTB) | Margins and/or rounded corners on the taskbar. |
| [**ModernFlyouts**](https://modernflyouts-community.github.io/) | Modern pop-up indicators for volume, brightness, caps-lock. |

### Icon & File Management

| Tool | What it does |
|------|-------------|
| [**filetypesman**](https://www.nirsoft.net/utils/file_types_manager.html) | Manage filetype icons & associations. Alternative: [Types](https://ystr.github.io/types/). |
| [**Resource Hacker**](https://angusj.com/resourcehacker/) | Edit resources in EXE/DLL. Essential for stubborn icons. Run with [NSudo](https://github.com/M2Team/NSudo) to get permissions. Icons live in `\Windows\SystemResources\shell32.dll.mun` and `\imageres.dll.mun`. |

<details>
<summary><b>Resource Hacker tips</b></summary>

- **Nonempty folder icon (Win11):** Replace Icon Group 162 in `imageres.dll.mun`.
- **Disable folder thumbnails (22H2+):** Overwrite Icon Group 6 in `imageres.dll.mun`.
- **Change Home icon in Explorer sidebar:** Overwrite Icon Group 51380 in `shell32.dll.mun`. Or [remove it entirely](https://www.elevenforum.com/t/add-or-remove-home-in-navigation-pane-of-file-explorer-in-windows-11.2449/).

</details>

### Extras

- **Prettify Explorer thumbnails:** Add previews for more filetypes via [x2plugins](https://www.zabkat.com/x2plugins.htm), [DJVU](https://www.cuminas.jp/en/downloads), [SVG](https://github.com/EtheaDev/SVGShellExtensions), or [Sumatra](https://www.sumatrapdfreader.org/free-pdf-reader) (for PDF).
- **Sound Manager** ([GitHub](https://github.com/ORelio/Sound-Manager)) — custom sound schemes, including startup chimes on Win11.
- **Screensavers:** [Screensavers Planet](https://www.screensaversplanet.com/) has retro classics like [Flying Toasters](https://www.screensaversplanet.com/screensavers/after-dark-flying-toasters-1153/) and [Johnny Castaway](https://www.screensaversplanet.com/screensavers/johnny-castaway-237/).

### Firefox Extensions

| Extension | What it does |
|-----------|-------------|
| [Vertical Tabs](https://github.com/ranmaru22/firefox-vertical-tabs) | Edge-style vertical tabs. |
| [Stylus](https://github.com/openstyles/stylus) | Inject CSS to restyle websites. Huge [script database](https://userstyles.world/). |
| [Wikiwand](https://www.wikiwand.com/) | Modernizes the Wikipedia UI. |
| [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) | Userscripts. |
| [Bonjourr](https://addons.mozilla.org/en-US/firefox/addon/bonjourr-startpage/) | Minimalist startpage. |

---

## System Maintenance and Optimization

> Keep your system clean, fast, and backed up.

| Tool | What it does |
|------|-------------|
| [**Process Explorer**](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) | Task Manager on steroids. Search handles and DLL processes. |
| [**Autoruns**](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns) | Comprehensive startup process manager. |
| [**WizTree**](https://diskanalyzer.com/) | Visual disk space analyzer. Blazing fast on NTFS. Alternative (paid): [FolderSizes](https://www.foldersizes.com/). |
| [**Bulk Crap Uninstaller**](https://www.bcuninstaller.com/) | Thorough uninstaller with leftover detection. Faster alternative: [Geek Uninstaller](https://geekuninstaller.com/). |
| [**O&O RegEditor**](https://www.oo-software.com/en/ooregeditor) | Registry editor with far superior search vs. built-in RegEdit. |
| [**Compactor**](https://github.com/Freaky/Compactor) | GUI for Windows built-in file compression. Great for games. |
| [**FileOptimizer**](https://nikkhokkho.sourceforge.io/static.php?page=FileOptimizer) | Lossless file size reduction. Saved ~0.87 GB on 10 GB of PDFs. |
| [**czkawka**](https://github.com/qarmin/czkawka) | Find empty files, duplicates, unnecessary junk. Use after [BleachBit](https://www.bleachbit.org/) for deep cleanup. |
| [**Mp3tag**](https://www.mp3tag.de/en/) | Edit audio metadata. Fixes half-broken album art. |
| [**Veeam Agent**](https://www.veeam.com/agent-for-windows-community-edition.html) | Painless incremental backups of your entire system. Free! |
| [**Chocolatey**](https://chocolatey.org/) | Package manager via PowerShell. Being superseded by [winget](https://winget.run/). |

---

## Usability / Quality of Life

> Productivity tools, search, window management, and small conveniences.

### Power Tools

| Tool | What it does |
|------|-------------|
| [**Microsoft PowerToys**](https://github.com/microsoft/PowerToys) | Always on Top, Awake, Color Picker, FancyZones, File Locksmith, Text Extractor, and more. Use [XnShell](https://www.xnview.com/en/xnshell/) instead of Image Resizer. |
| [**ExplorerPatcher**](https://github.com/valinet/ExplorerPatcher) | Restores Win10 functionality in Win11. Clean Alt-Tab, taskbar weather, and more. |
| [**Winaero Tweaker**](https://winaero.com/winaero-tweaker/) | Hundreds of "secret" Windows settings in one GUI. |
| [**EarTrumpet**](https://github.com/File-New-Project/EarTrumpet) | Per-app volume control from the system tray. |

### Search & Navigation

| Tool | What it does |
|------|-------------|
| [**Everything**](https://www.voidtools.com/) + [**EverythingToolbar**](https://github.com/srwi/EverythingToolbar) | Instant filename search, integrated into the taskbar. |
| [**Listary**](https://www.listary.com/pro) | Search bar for any "Open File" dialog. Killer feature: quick find from anywhere. |
| [**WinSetView**](https://github.com/LesFerch/WinSetView) | Set default Explorer views (e.g., always show details). |

### Window Management

| Tool | What it does |
|------|-------------|
| [**AltSnap**](https://github.com/RamonUnch/AltSnap) | Move/resize windows with Alt+click. Always-on-top, roll-up, close with middle-click. |
| [**OnTopReplica**](https://github.com/LorenzCK/OnTopReplica) | Always-on-top PIP for any window. Roll your own PIP for [Stremio](https://www.stremio.com/) etc. |
| [**windows-terminal-quake**](https://github.com/flyingpie/windows-terminal-quake) | Quake mode for Windows Terminal (more stable than built-in). |

### Clipboard & Screenshots

| Tool | What it does |
|------|-------------|
| [**Ditto**](https://ditto-cp.sourceforge.io/) | Clipboard manager. |
| [**Snipaste**](https://www.snipaste.com/) | Screen snipping with auto-detection of UI regions. |
| [**SnipDo**](https://snipdo-app.com/) | Text selection popup with quick actions (search, translate, copy). |

### File Utilities

| Tool | What it does |
|------|-------------|
| [**QuickLook**](https://github.com/QL-Win/QuickLook) / [**Seer**](http://1218.io) | Spacebar file preview in Explorer (macOS-style). |
| [**DragDropConfirm**](https://github.com/broken-e/DragDropConfirm) | Confirmation dialog for drag-and-drop file moves. |
| [**ExtractNow**](https://extractnow.com/) | Double-click to unzip/unrar/etc. |
| [**notepad-replacer**](https://github.com/olohmann/notepad-replacer) | Redirect `notepad.exe` to [Notepad++](https://notepad-plus-plus.org/) or your editor of choice. |

### Battery & Power

| Tool | What it does |
|------|-------------|
| [**BatteryInfoView**](https://www.nirsoft.net/utils/battery_information_view.html) | Battery status, charge rate, wear level. |
| [**BatteryBar**](https://batterybarpro.com/) | Calibrated runtime estimates. Floats or pins as a toolbar. |
| [**BatteryMode**](https://github.com/tarcode-apps/BatteryMode) | Power plan switching with customization (Win7 tray icon option). |
| [**CircleBattery**](http://rebelvalkyrie.com/?page=circle-battery) | Glowing circular arc in the tray. Click to prevent sleep. |

### Other

| Tool | What it does |
|------|-------------|
| [**ShareDrop**](https://www.sharedrop.io/) | Between-device file sharing, even across networks. |
| [**JDownloader**](https://jdownloader.org/) | Bulk download manager. Feature-rich. [Disable ads](https://superuser.com/questions/1297098/how-to-disable-ads-in-jdownloader). |
| [**SuperF4**](https://stefansundin.github.io/superf4/) | Ctrl+Alt+F4 to forcefully kill the foreground app. |
| [**MiniBin**](https://download.cnet.com/minibin/3000-2094_4-75451640.html) | Recycle bin from the system tray. Themeable. |
| [**Desktop Media**](https://www.softpedia.com/get/Desktop-Enhancements/Other-Desktop-Enhancements/Desktop-Media.shtml) | Drive icons on the desktop. |
| [**Incipitor**](https://www.dcmembers.com/bgmcoder/download/incipitor/) | Automate adding Start Menu shortcuts. |
| [**ShellExView**](https://www.nirsoft.net/utils/shexview.html) / [**ShellMenuView**](https://www.nirsoft.net/utils/shell_menu_view.html) / [**ShellMenuNew**](https://www.nirsoft.net/utils/shell_menu_new.html) / [**OpenWithView**](https://www.nirsoft.net/utils/open_with_view.html) | Remove unwanted right-click menu entries. |

---

## Apps for Minimalists

> Lightweight alternatives that do one thing well.

| App | What it is |
|-----|-----------|
| [**nomacs**](https://github.com/nomacs) | Image viewer — minimal UI, surprisingly feature-rich. |
| [**mupdf**](https://mupdf.com/) | Hyperminimal PDF viewer. Even leaner than [Sumatra](https://www.sumatrapdfreader.org/free-pdf-reader). |
| [**Sioyek**](http://sioyek.info/) | PDF viewer (if you don't need touchscreen scrolling/zooming). |

---

## Icons and Other Art

> Where to find icons, wallpapers, cursors, and visual inspiration.

### Icon Sources

| Source | Notes |
|--------|-------|
| [**DeviantArt**](https://www.deviantart.com/) | Endless inspiration. Key artists: [Niivu](https://www.deviantart.com/niivu) (Win themes, now [on GitHub](https://github.com/niivu/Windows-11-themes)), [Octaviotti](https://www.deviantart.com/octaviotti), [hechiceroo](https://www.deviantart.com/hechiceroo/art/Mnemo-n-icons-413224458) (Mnemo icons), [vladsukhetskyi](https://www.deviantart.com/vladsukhetskyi/art/VS-Cursor-11-0-Premium-900146070) (cursors). |
| [**IconArchive**](https://iconarchive.com/) | Massive collection, searchable by keyword and style. |
| [**macOSicons**](https://macosicons.com) | macOS-style icons for almost everything. |
| [**icons8 Fluency**](https://icons8.com/icons/fluency) | Win10/11 design language. Also: [Folder11](https://github.com/icon11-community/Folder11), [folder-icons](https://github.com/sameerasw/folder-icons). |
| [**elementosh-icons**](https://github.com/Macintosh98/elementosh-icons) | elementaryOS-style Linux icons. |
| [**Dribbble**](https://dribbble.com/search/icon-replacement) | Gorgeous designs (not ready-to-use — screenshot + [remove.bg](https://www.remove.bg/) workaround). Artist pick: [Sandor](https://dribbble.com/sandor). |

### Wallpaper Sources

| Source | Notes |
|--------|-------|
| [**500px**](https://500px.com) | Discover photos, many make excellent wallpapers. |
| [**wallhaven**](https://wallhaven.cc) | Large wallpaper database. |
| Google Photos albums | [Windows wallpapers](https://photos.app.goo.gl/7xH7UuhLAjLZdtrs5), [Windows beta wallpapers](https://photos.app.goo.gl/r8BMfQhc3vDW8Ehq5), [macOS wallpapers](https://goo.gl/photos/HjY1hmo6p3jfFz8a7), [iOS wallpapers](https://goo.gl/photos/ZVpabTtcezd35XBa9). |

### Windows Terminal Themes

- [**atomcorp's collection**](https://windowsterminalthemes.dev/) — easy-to-navigate website.

### Retro Gaming Icons

For emulators, retro-styled icons complete the look:

- [Antiseptic icons](https://www.deviantart.com/starvingartist/art/Antiseptic-Videogame-Systems-23217105) by starvingartist
- [Snes Mini theme](https://github.com/ruckage/es-theme-snes-mini) by Ruckage
- [hakchi2](https://github.com/ClusterM/hakchi2) by ClusterM
- [Additional Icon Pack 2.1](https://imgur.com/gallery/09qQibS) by Faustbear
- [Pixel Gaming Machine Icons](https://www.deviantart.com/jaffacakelover/art/Pixel-Gaming-Machine-Icons-413704203) by JaffaCakeLover
- WiiU: [Basic](https://www.deviantart.com/eriaciaite/art/Basic-WiiU-Icon-326889848) and [Deluxe](https://www.deviantart.com/taurosa/art/Deluxe-WiiU-Icon-326889969) by Taurosa

### Paid Themes & Sets

- [**dpcdpc11 on Gumroad**](https://dpcdpc11.gumroad.com/) — themes, wallpapers, cursor sets.

---

## Windows Settings and Hacks

> Registry tricks, context menu edits, and power-user settings.

<details>
<summary><b>Add items to the classic right-click context menu</b></summary>

Example: Add a "Trim margins" command for PDFs using [pdfCropMargins](https://github.com/abarker/pdfCropMargins). Save as a `.reg` file and import via regedit:

```reg
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\MuPDF\shell]

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\MuPDF\shell\Trim margins]
"Icon"="\"C:\\Users\\anon\\Insync\\OneDrive\\Pictures\\Custom taskbar icons\\crop.ico\""

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\MuPDF\shell\Trim margins\command]
@="C:\\Python310\\Scripts\\pdf-crop-margins.exe \"%1\""
```

For other file types: open the extension in [Types](https://ystr.github.io/types/) and check the "Class" field. Replace `"MuPDF"` accordingly, and adjust the icon path and command.

</details>

<details>
<summary><b>Disable UAC (run all apps as admin)</b></summary>

```cmd
REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /f /v EnableLUA /t REG_DWORD /d 0
```

> **Warning:** This breaks installation of [WSA from Google Play](https://github.com/MustardChef/WSABuilds). Temporarily re-enable (change `0` to `1`) before installing.

</details>

<details>
<summary><b>Change taskbar icons for pinned UWP apps</b></summary>

1. Get the AppID: `get-StartApps | Format-Table | Out-String -width 9999` (PowerShell)
2. Create a shortcut to `explorer.exe shell:appsFolder\YOURAPPID`
3. Run: `Win7AppId1.1 "YourAppShortcut.lnk" "YOURAPPID"` ([download](https://code.google.com/archive/p/win7appid/downloads))
4. Change the shortcut icon, pin to taskbar.

Method from [dpcdpc11](https://dpcdpc11.com/custom-taskbar-icons-guide/).

</details>

### Quick Hacks

| Hack | How |
|------|-----|
| **Change Win11 Settings app icon** | Replace PNGs in `C:\Windows\ImmersiveControlPanel\images` (match `logo.targetsize*` sizes). |
| **Remove clock/date from taskbar** | [Guide](https://www.thewindowsclub.com/hide-clock-and-date-from-taskbar-windows-10) |
| **Refresh icon cache (no restart)** | `cmd /c taskkill /f /im explorer.exe & del /a %userprofile%\AppData\Local\IconCache.db & start explorer` |
| **Rebind built-in hotkeys** | Example: Win-S to open Everything. Set Everything to Ctrl+Alt+U, then AHK script: `#S::SendInput ^!u` |
| **Disable Widgets feed entirely** | [Remove or disable Widgets](https://winaero.com/remove-and-uninstall-widgets-from-windows-11/#:~:text=In%20the%20Local%20Group%20Policy,Click%20Apply%20and%20OK.) via Group Policy. |

---

## Other Resources

> Community lists, forums, and power-user collections.

| Resource | Notes |
|----------|-------|
| [**Scott Hanselman's power user tools**](http://hanselman.com/tools) | Curated list by a Microsoft veteran. |
| [**retrial's Windows Ultimate Collection**](https://xdaforums.com/t/windows-ultimate-collection-guidives.4507867/) | XDA forums curated lists. |
| [**mydigitallife forums**](https://forums.mydigitallife.net/) | Deep Windows expertise. [Win11 tweaks overview](https://forums.mydigitallife.net/threads/windows-11-tweaks-fixes-and-modifications-overview.83744/). Registration required. |
| [**elevenforum**](https://www.elevenforum.com/) / [**tenforums**](https://www.tenforums.com/) | Community discussions + excellent [Win10 tutorials](https://www.tenforums.com/tutorials/1977-windows-10-tutorial-index.html) and [Win11 tutorials](https://www.elevenforum.com/tutorials/). |
| [**Courage-1984**](https://github.com/Courage-1984/Windows-Ricing-Privacy-Customization-Optimization) | Similar list with a focus on security & privacy. |

---

<p align="center">
  <sub>Trophy icon by <a href="https://www.flaticon.com/free-icons/trophy">Freepik</a></sub>
</p>
