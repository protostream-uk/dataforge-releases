# DataForge

A fast, focused desktop database client for **MySQL / MariaDB** and **Redis**, for Windows and macOS.

This repo only holds the installers. Download the latest from **[Releases](https://github.com/protostream-uk/dataforge-releases/releases/latest)**; once installed, DataForge keeps itself up to date from here.

**Windows:** run `DataForge-Setup-x.y.z.exe`. It installs per-user (no admin). The build isn't code-signed yet, so SmartScreen may warn: *More info → Run anyway*.

**macOS:** download the `.dmg` for your Mac (`arm64` = Apple Silicon, `x64` = Intel) and drag DataForge to **Applications**. The build isn't notarised yet, so the first time, run:

```bash
xattr -cr /Applications/DataForge.app
```

(or open it once and allow it under *System Settings → Privacy & Security → Open Anyway*). Updates installed by the app don't need this again.
