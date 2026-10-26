# BEAMwire

AV wiring diagrams (line drawings) for live events. Place equipment from a library with real connectors, connect ports with right-angle cables that hop over each other, get warned (or stopped) when connectors don't mate, and export a PDF with border, title block, legend and your logo, plus patch sheets for routers and switchers. Claude can draw for you from a description. By [BEAM Events](https://beamevents.com).

This repository only holds the **installers and updates**.

## Download
Get the latest version from **[Releases](https://github.com/BEAMevents/BEAMwire/releases/latest)**:

- **BEAMwire-Setup-x.y.z.exe** (Windows) installs BEAMwire and **updates itself automatically**.
- **BEAMwire-x.y.z-mac-arm64.dmg** (Mac, Apple Silicon). It tells you when a newer version is out; download the new .dmg to update.

The Windows installer isn't code-signed yet, so SmartScreen may warn on first launch: click **More info → Run anyway**. The Mac app isn't notarized: the first time, right-click BEAMwire → **Open** → **Open**.

## Updates
The installed Windows version checks for updates in the background and shows **Update x.y.z ready** in its header. Click it, then **Install & restart**.

## Claude
To have Claude draw, open the **✦ Claude** panel and sign in with an Anthropic API key (console.anthropic.com → API keys). Usage is billed to that Anthropic account. The key is stored encrypted on the computer.
