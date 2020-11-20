# No Big Sur Icon

**Any Pull Request is welcomed !!!!**


## Introduction

After macOS Bug Sir update, many applications like Chrome start to change their icons with new design styles. But some users like me don't like them, so this repo is aimed at providing users with their former icons.


## List

| Name          | Link                                |
| ------------- | ----------------------------------- |
| Google Chrome | [Link](Google%20Chrome/README.md)   |
| Telegram     | [Link](Telegram/README.md)          |
| QuickTime Player | [Link](QuickTime%20Player/README.md) |
| Safari | [Link](Safari/README.md) |
| Siri | [Link](Siri/Siri.icns) |

## How to change the app icon?

- Download the icon.
- In Finder, open the `Applications` folder and select the app you want to change icon
-  `File -> Get Info` or shortcut `Cmd + i`, then just drag the icns file to the window.

- Use command `killall Dock; killall Finder` to refresh cache. 

## Directory Format

Take `Google Chrome` as example:

- ./Google Chrome/ :
  - app.icns
    - The name of icns file should be equal to the one in `Google Chrome.app`
  - README.md
    - Tutorial to replace, including file path and points for attention
