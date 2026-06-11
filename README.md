# Scripts Builder 🏗️

This repository is a dedicated **Builder** for the **Scripts** component of the Kodi ecosystem. 

## Role in Ecosystem
This repository is part of the [Kodi Build Hub](https://github.com/IamRPDev/kodi-build). Its primary responsibilities are:
1.  **Orchestration**: Triggered by the central hub to start builds.
2.  **Compilation**: Maintains the `./source` and `./compiled` directory structure to build the component from upstream source.
3.  **Distribution**: Upon successful build, it dispatches the final installers to OS-specific release repositories.

## Supported Branches
- **Piers**: The latest development/master branch.
- **Omega**: The stable release branch.

## Build Matrix
| Platform | Status | Release Target |
|:---|:---:|:---|
| Linux 64 | [![Build Status](https://github.com/IamRPDev/repo-scripts-build/actions/workflows/build.yml/badge.svg)](https://github.com/IamRPDev/repo-scripts-build/actions) | [repo-scripts-build-linux64](https://github.com/IamRPDev/repo-scripts-build-linux64) |
| Windows 64 | | [repo-scripts-build-win64](https://github.com/IamRPDev/repo-scripts-build-win64) |
| Android ARM64 | | [repo-scripts-build-android-arm64](https://github.com/IamRPDev/repo-scripts-build-android-arm64) |
| OSX 64 | | [repo-scripts-build-osx64](https://github.com/IamRPDev/repo-scripts-build-osx64) |

---
*Back to [Kodi Build Hub Index](https://github.com/IamRPDev/kodi-build)*
