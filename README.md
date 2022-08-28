# obs-ndi

## YOU HAVE STUMBLED UPON THE DEV BRANCH FOR V5.0.0

Network A/V in OBS Studio with NewTek's NDI (5.0) technology.

[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40LePalakis)](https://twitter.com/LePalakis)
[![Financial Contributors on Open Collective](https://opencollective.com/obs-websocket/all/badge.svg?label=financial+contributors)](https://opencollective.com/obs-websocket)

## Features
- **NDI Input (Source)**: Receive NDI video and audio in OBS
- **NDI Output**: Transmit video and audio from OBS via NDI
- **NDI Filter** (a.k.a NDI Dedicated Output): Transmit a single input (source) or scene via NDI

## Downloads
Binaries for Windows, macOS and Linux are available in the [Releases](https://github.com/Palakis/obs-ndi/releases) section.

## Local build

Windows:
In a **PowerShell 7** terminal, `cd` to the folder you want the code in:
```
PS …> git clone --recursive https://github.com/obsproject/obs-studio.git
PS …> pushd obs-studio
PS …\obs-studio> Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
PS …\obs-studio> git config --global --add safe.directory absolute/path/to/your/repo/obs-studio
PS …\obs-studio> .\CI\build-windows.ps1
PS …\obs-studio> popd
PS …> git clone https://github.com/Palakis/obs-ndi.git
PS …> pushd obs-ndi
PS …\obs-ndi> .\.github\scripts\Build-Windows.ps1
```
