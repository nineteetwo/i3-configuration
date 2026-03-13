## i3 WM Yapılandırması

Basit ve minimal bir i3 pencere yöneticisi yapılandırması. <br>
<a href="https://github.com/nineteetwo/MagiOS-concepts-i3">Önceki özelleştirme (ricing) çalışmamı</a> temel almaktadır. <br>
<div align="center">
  <img src="Screenshot from 2026-01-19 02-14-07.png" width="45%">
  <img src="Screenshot from 2026-01-19 10-35-21.png" width="45%">
</div>

### Gereksinimler

- i3
- picom
- polybar
- alacritty
- neofetch
- rofi
- feh
- autotiling

### Kurulum

#### Ubuntu / Debian Tabanlı Dağıtımlar

```bash
sudo apt-get update
sudo apt-get install autotiling i3 feh polybar rofi alacritty picom neofetch
```
#### Arch Tabanlı Dağıtımlar
```bash
sudo pacman -S i3 polybar feh rofi alacritty picom neofetch
```
Tüm yapılandırma dosyalarını (screenshots dizini hariç) ~/.config dizininize kopyalayın.

```bash
cp -r * ~/.config
```
<b>Kopyalama işleminden önce mevcut yapılandırma dosyalarınızı yedeklediğinizden emin olun.

i3 yapılandırma dosyasındaki ekran ayarlarını xrandr kullanarak kendi sisteminize göre düzenlemeyi unutmayın.


Bu yapılandırma varsayılan olarak PulseAudio kullanır. Eğer PipeWire kullanıyorsanız ilgili kısımları değiştirin.</b>


### Kullanım
```bash
Mod tuşu: Super (Windows tuşu)

Super + X: Rofi'yi açar

Super + Enter: Alacritty'yi açar

Super + Shift + Q: Odaklanılan (aktif) uygulamayı kapatır

Super + Shift + Sayı: Odaklanılan uygulamayı belirtilen çalışma alanına (workspace) taşır

Super + Shift + E: Oturumu kapatır (Çıkış yap)

Super + Shift + R: i3'ü yeniden başlatır

Super + Shift + Yön Tuşları: Odaklanılan pencereyi taşır
```


❤️ Umarım bu yapılandırmayı keyifle kullanırsınız. ❤️
