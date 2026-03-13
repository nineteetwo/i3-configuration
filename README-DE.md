## i3 WM Konfiguration

<div align="center">
  <b>
    <a href="README.md">English</a> |
    <a href="README-TR.md">Türkçe</a> |
    <a href="README-JP.md">日本語</a> |
    <a href="README-DE.md">Deutsch</a>
  </b> 
</div><br>

<div align="center">
  <img src="Screenshot from 2026-01-19 02-14-07.png" width="45%">
  <img src="Screenshot from 2026-01-19 10-35-21.png" width="45%">
</div>
Eine einfache und minimalistische i3 Window-Manager-Konfiguration.<br>
<a href="https://github.com/nineteetwo/MagiOS-concepts-i3">Basierend auf meinem vorherigen Ricing.</a><br>

### Voraussetzungen

- i3
- picom
- polybar
- alacritty
- neofetch
- rofi
- feh
- autotiling

### Installation

#### Ubuntu / Debian-basierte Distributionen

```bash
sudo apt-get update
sudo apt-get install autotiling i3 feh polybar rofi alacritty picom neofetch
```
#### Arch-basierte Distributionen
```bash
sudo pacman -S i3 polybar feh rofi alacritty picom neofetch
```

### Einrichtung

Kopiere alle Konfigurationsdateien (außer das screenshots-Verzeichnis) in dein `~/.config`-Verzeichnis.
```bash
cp -r * ~/.config
```
**Stelle sicher, dass du deine vorhandenen Konfigurationsdateien sicherst, bevor du sie kopierst.<br>
Passe unbedingt deine Anzeigeeinstellungen in der i3-Konfiguration mit xrandr an.<br>
Diese Konfiguration verwendet standardmäßig PulseAudio. Ändere dies, falls du PipeWire verwendest.**<br>

### Verwendung

- **Mod-Taste:** Super (Windows-Taste)
- **Super + X:** Rofi öffnen
- **Super + Enter:** Alacritty öffnen
- **Super + Shift + Q:** Die aktuell fokussierte Anwendung schließen
- **Super + Shift + Zahl:** Die fokussierte Anwendung in den angegebenen Arbeitsbereich (Workspace) verschieben
- **Super + Shift + E:** Abmelden
- **Super + Shift + R:** i3 neu starten
- **Super + Shift + Pfeiltasten:** Das fokussierte Fenster verschieben

❤️ Ich hoffe, dir gefällt diese Konfiguration. ❤️
