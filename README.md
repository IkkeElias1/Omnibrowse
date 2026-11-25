# OmniBrowse

A fast, minimal web browser for Windows that packs in as many useful features as possible without giving up performance. It runs on Microsoft Edge WebView2, so pages render exactly as they do in Edge and Chrome.
<img width="1919" height="1005" alt="image" src="https://github.com/user-attachments/assets/7641fe0d-e3be-4460-9a20-14dfe7771c39" />

## Download

Get the latest version from **[Releases](https://github.com/IkkeElias1/Omnibrowse/releases)**:

- **`OmniBrowse_x.y.z_x64-setup.exe`**: installer (recommended). Adds a Start menu entry and installs WebView2 if it is missing.
- **`OmniBrowse-x.y.z-portable.exe`**: a single file you can run from anywhere. Needs the WebView2 runtime, which Windows 10 and 11 already include.

Requires Windows 10 or 11 (64-bit).

## Features

- **Ad and tracker blocking** built in, using EasyList, EasyPrivacy, EasyList Cookie List, Fanboy's Annoyance List and Fanboy's Social Blocking List. Lists update automatically, and you can see exactly what was blocked on each page.
- **Site information panel**: connection and certificate details, cookies (with one-click delete), ad blocking and permissions (camera, microphone, location, notifications…) per site.
- **Local apps on the home page**: launch Windows programs, or open web apps that run on your PC (`http://localhost:…`). OmniBrowse can start a web app's server for you when it is not running and stops it when you close the browser.
- **Import** bookmarks and history from Chrome, Edge, Opera, Opera GX, Brave, Vivaldi and Firefox.
- **File explorer** on the home page, with drives, previews and search.
- **Fast by design**: links start loading when you hover them, and tabs you are not using are paused and unloaded to save memory.
- **Private tabs**, history, bookmarks, a full download manager and Chrome Web Store / Edge Add-ons extensions.
- Settings, history, downloads, bookmarks and extensions in one place, with a shared sidebar.

## Shortcuts

| Action | Keys |
| --- | --- |
| New tab / private tab | `Ctrl+T` / `Ctrl+Shift+N` |
| Reopen closed tab | `Ctrl+Shift+T` |
| History / downloads / bookmarks | `Ctrl+H` / `Ctrl+J` / `Ctrl+Shift+O` |
| Bookmark this page | `Ctrl+D` |
| Delete browsing data | `Ctrl+Shift+Del` |
| Address bar | `Ctrl+L` |
| Full screen | `F11` |

## Your data

Everything stays on your PC, in `%LocalAppData%\OmniBrowse`. OmniBrowse has no account and sends no telemetry. Apart from the pages you open (and links it preloads while you hover them, which you can turn off in Settings → Performance), the only thing it downloads on its own is the ad-blocking filter lists.
