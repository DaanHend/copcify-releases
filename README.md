# Copcify — downloads

Copcify is a Windows desktop app that converts point clouds (`.las`, `.laz`, `.pts`, `.xyz`)
to [COPC](https://copc.io) (`.copc.laz`).

This repository holds the installers only; the source code is not public.

## Install

1. Open [the latest release](https://github.com/DaanHend/copcify-releases/releases/latest) and
   download `Copcify_<version>_x64-setup.exe`.
2. Run it. No administrator rights and no internet connection are needed.
3. Windows may show "Windows protected your PC", because the installer is not code-signed:
   choose *More info* → *Run anyway*.

Once installed, Copcify offers new versions by itself when it starts.

## Check the download

Each release has a `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\Copcify_<version>_x64-setup.exe -Algorithm SHA256
```

The hash must equal the one in `SHA256SUMS.txt`.

## Problems

Mail d.hendriks@periplus.nl and attach the log file (*About* → *Open log folder* in the app).

Copyright © 2026 Daan Hendriks. All rights reserved.
