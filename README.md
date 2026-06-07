# Kickoff - No Search (NS)

A fork of KDE Plasma's Application Launcher (Kickoff) with a **"Hide Search Bar"** toggle added to the settings.


## What's different

- **Hide Search Bar** option in the General settings tab
- Everything else is identical to the original

<img width="830" height="684" alt="Screenshot_20260607_163607" src="https://github.com/user-attachments/assets/fcd361a3-b98b-426b-9a38-db334fcd74b7" />


## Installation

## Download or clone the repository

```bash
kpackagetool6 --type=KPackage/PlasmaApplet --install /path/to/kickoff-nosearch-6.6(folder or zip file)
```

## Uninstall

```bash
kpackagetool6 --type=KPackage/PlasmaApplet --remove org.kde.plasma.kickoff
```

Or delete the installed files manually:

```bash
rm -rf ~/.local/share/plasma/plasmoids/org.kde.plasma.kickoff-nosearch/
```


## Original source

https://github.com/KDE/plasma-desktop/tree/master/applets/kickoff

https://invent.kde.org/plasma/plasma-desktop/-/tree/master/applets/kickoff
