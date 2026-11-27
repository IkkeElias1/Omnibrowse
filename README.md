# OmniBrowse

A fast, minimal web browser for Windows that packs in as many useful features as possible without giving up performance. It runs on Microsoft Edge WebView2, so pages render exactly as they do in Edge and Chrome.

## Download

Get the latest version from **[Releases](https://github.com/IkkeElias1/Omnibrowse/releases)**:

- **`OmniBrowse_x.y.z_x64-setup.exe`**: installer (recommended). Keeps itself up to date and installs WebView2 if it is missing.
- **`OmniBrowse-x.y.z-portable.exe`**: a single file you can run from anywhere. Needs the WebView2 runtime, which Windows 10 and 11 already include.

Requires Windows 10 or 11 (64-bit).

## Features

- **Tabs your way**: smooth drag and drop, tab groups with names and colours, pinned tabs, and a speaker on tabs playing sound (click to mute).
- **Windows, split view and sessions**: drag a tab out into its own window or onto another window, show two to four tabs side by side (2 columns, 2 rows, 3 columns, one large + two, 2 × 2), and pick up where you left off: windows, tabs, groups and pinned tabs come back on the next start.
- **Hot tabs and limits**: see what every tab uses (memory, CPU), unload or close the busy ones, and cap memory, CPU and download speed.
- **Screenshots, reader view and pop-out video**: capture an area, the visible part or the whole page; read articles without clutter; float any video in a small window that stays on top.
- **Bookmarks bar and folders**: a bookmarks bar under the address bar with folders, drag to reorder, and a bookmark manager. Import bookmarks (with their folders) and history from Chrome, Edge, Opera, Opera GX, Brave, Vivaldi and Firefox.
- **Password manager**: saves and fills sign-ins, encrypted with your Windows account. Sites only get a password when you pick it. Import and export CSV.
- **Command palette** (`Ctrl+K`): jump to any tab, bookmark, history entry, app or command.
- **Ad and tracker blocking** built in (EasyList, EasyPrivacy, EasyList Cookie List, Fanboy's Annoyance and Social lists), with a per-page list of what was blocked.
- **Site information panel**: certificate details, cookies, ad blocking and permissions per site.
- **Home page**: shortcuts to your favourite sites, editable Quick Access folders, a file explorer, and apps: Windows programs and web apps running on your PC (`http://localhost:…`), which OmniBrowse can start for you. Pick a wallpaper and an accent colour to make it yours.
- **Search settings**: choose the search engine, hide AI answers (Google, DuckDuckGo, Brave) and set SafeSearch, right from the home page.
- **Fast by design**: links start loading when you hover them; tabs you are not using are paused and unloaded to save memory.
- Private tabs, history, a download manager, extensions from the Chrome Web Store / Edge Add-ons, and it can be your default browser.

## Shortcuts

| Action | Keys |
| --- | --- |
| New tab / window / private tab | `Ctrl+T` / `Ctrl+N` / `Ctrl+Shift+N` |
| Command palette | `Ctrl+K` |
| Screenshot | `Ctrl+Shift+S` |
| Reader view | `F9` |
| Reopen closed tab | `Ctrl+Shift+T` |
| History / downloads / bookmarks | `Ctrl+H` / `Ctrl+J` / `Ctrl+Shift+O` |
| Bookmark this page / bookmarks bar | `Ctrl+D` / `Ctrl+Shift+B` |
| Delete browsing data | `Ctrl+Shift+Del` |
| Address bar | `Ctrl+L` |
| Full screen | `F11` |

Type `about:` in the address bar to see every built-in page.

## Your data

Everything stays on your PC, in `%LocalAppData%\OmniBrowse` (screenshots you save go to Pictures › OmniBrowse). OmniBrowse has no account and sends no telemetry. Apart from the pages you open (and links it preloads while you hover them, which you can turn off in Settings → Performance), it only downloads the ad-blocking filter lists and checks GitHub for updates.
