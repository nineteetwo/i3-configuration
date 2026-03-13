## i3 WM 設定

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
<br>

シンプルでミニマルな i3 ウィンドウマネージャーの設定です。<br>
<a href="https://github.com/nineteetwo/MagiOS-concepts-i3">以前のライシング（ricing）</a>をベースにしています。<br>

### 要件

- i3
- picom
- polybar
- alacritty
- neofetch
- rofi
- feh
- autotiling

### インストール

#### Ubuntu / Debian 系ディストリビューション

```bash
sudo apt-get update
sudo apt-get install autotiling i3 feh polybar rofi alacritty picom neofetch
```
#### Arch 系ディストリビューション
```bash
sudo pacman -S i3 polybar feh rofi alacritty picom neofetch
```
###セットアップ
すべての設定ファイル（screenshots ディレクトリを除く）を ~/.config ディレクトリにコピーします。

```bash
cp -r * ~/.config
```
<b>コピーする前に、既存の設定ファイルを必ずバックアップしてください。


xrandr を使用して、i3 設定ファイルのディスプレイ設定を環境に合わせて調整してください。


この設定はデフォルトで PulseAudio を使用します。PipeWire を使用している場合は変更してください。</b><br/>


###使用方法
**Mod キー**: Super (Windows キー)

**Super + X**: rofi を開く

**Super + Enter**: alacritty を開く

**Super + Shift + Q**: 現在フォーカスされているアプリケーションを閉じる

**Super + Shift + 数字**: フォーカスされているアプリケーションを指定したワークスペースに移動する

**Super + Shift + E**: ログアウト

**Super + Shift + R**: i3 を再起動する

**Super + Shift + 矢印キー**: フォーカスされているウィンドウを移動する

❤️ この設定を楽しんで使っていただければ幸いです。 ❤️
