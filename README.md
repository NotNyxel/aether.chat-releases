<p align="center"><img src="icon.svg" width="88" alt="aether.chat" /></p>

<h1 align="center">aether.chat · Releases</h1>

<p align="center">
  Signed Windows installers and the auto-update feed for <b>aether.chat</b>, a lightweight Discord-style chat app with
  peer-to-peer voice and video.
</p>

## Download

Get the latest **`aether.chat_<version>_x64-setup.exe`** from the
**[Releases page](https://github.com/NotNyxel/aether.chat-releases/releases/latest)** and run it. It installs for your
Windows user only (no admin needed). Then create an account and you're in.

From version 0.3.0 onward the app **updates itself**: when a new release appears here you'll get an
"Update available" card inside the app.

## What's in this repo
| File (per release) | Purpose |
|---|---|
| `aether.chat_<version>_x64-setup.exe` | The installer |
| `aether.chat_<version>_x64-setup.exe.sig` | Ed25519 signature checked by the in-app updater |
| `latest.json` | The update feed the app polls |

Releases tagged **(legacy)**, v0.1.0 and v0.2.0, predate the updater and were called "AetherChat". Installing any
newer version replaces them automatically.

Requires Windows 10/11 with Microsoft Edge WebView2, which is preinstalled on Windows 11.
