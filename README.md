# Introduction

List of games working on the Raspberry PI 5 (Steam, GOG, Wine etc.)

## Tools

Ubuntu x64 + Pi-Apps + Box86 + Box64 + Steam
GoG games standalone .exe installers downloaded via GoG website
Flatpak for OpenMW (sudo apt install openmw version always crashes)

## Steam


| RPI model | Game | OS | Configuration | Remarks | 
|-----------|------|----|---------------|---------|
| RPI 5 16GB | Half-Life | Ubuntu 24.04.3 LTS aarch64 | ??? | Runs well, but some graphics effects slow the game down to 1-2 fps 
| RPI 5 16GB | Half-Life 2 | Ubuntu 24.04.3 LTS aarch64 | ??? | Runs at 0-1 fps
| RPI 5 16GB | Call of Duty 2 | Ubuntu 24.04.3 LTS aarch64 | Proton Hotfix + PROTON_USE_WINED3D=1 %command% | Runs very poorly 
| RPI 5 16GB | The Secret of Monkey Island Special Edition | Ubuntu 24.04.3 LTS aarch64 | Proton 9.0-4 + PROTON_USE_WINED3D=1 %command% | Runs very well

## GoG

| RPI model | Game | OS | Configuration | Remarks | 
|-----------|------|----|---------------|---------|
| RPI 5 16GB | Broken Sword 5 | Ubuntu 24.04.3 LTS aarch64 | Lutris + GoG exe installation + wine-ge-8-26-x86_64 | Runs okay
| RPI 5 16GB | Fallout 2 Classic | Ubuntu 24.04.3 LTS aarch64 | Lutris + GoG exe installation + wine-ge-8-26-x86_64 | Runs okay
| RPI 5 16GB | Full Throttle Remastered | Ubuntu 24.04.3 LTS aarch64 | Lutris + GoG exe installation + wine-ge-8-26-x86_64 | Runs very well
| RPI 5 16GB | Shadowgate | Ubuntu 24.04.3 LTS aarch64 | Lutris + GoG exe installation + wine-ge-8-26-x86_64 | Runs very well

## Other

| RPI model | Game | OS | Configuration | Remarks | 
|-----------|------|----|---------------|---------|
| RPI 5 16GB | OpenMW (Morrowind) | Ubuntu 24.04.3 LTS aarch64 | OpenMW installed via Flatpak | Runs okay, but performance tanks outside

