<p align="center">
<img src="https://user-images.githubusercontent.com/121724837/210158495-b77869b9-484f-4e6b-b8c1-c7e05cb0f22b.jpg" alt="LYNXZZ BOT" width="128" height="128"/>
</p>
<p align="center">
<a href="#"><img title="LYNXZZ BOT" src="https://img.shields.io/badge/-LYNXZZBOT-orange"></a>
</p>
<p align="center">
<a href="https://github.com/LynxzzBot"><img title="Author" src="https://img.shields.io/badge/Author-Lynxzz-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/LynxzzBot/followers"><img title="Followers" src=".. image:: https://img.shields.io/github/followers/82?style=plastic
   :alt: GitHub followers"></a>
<a href="https://github.com/LynxzzBot/Lynxzz"><img title="Stars" src=".. image:: https://img.shields.io/github/stars/66?logo=LynxzzBot
   :alt: GitHub User's stars"></a>
</p>

<p align="center">
  <a href="https://github.com/LynxzzBot/file#requirements">Requirements</a> •
  <a href="https://github.com/LynxzzBot/file#instalasi">Installation</a> •
  <a href="https://github.com/LynxzzBot/file#features">Features</a> •
  <a href="https://github.com/LynxzzBot/file#thanks-to">Thanks to</a>
</p>
</div>


---



# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)
* [Libwebp](https://developers.google.com/speed/webp/download) (for sticker wm)
* [Image Magic](https://imagemagick.org/script/download.php) ( for nulis command, Centang Kolom 1,2,3,5,6)
* Any text editor

# Instalasi
## For Windows
```bash
git clone https://github.com/LynxzzBot/file.git
cd babybot
npm install
npm start
```
## For Termux
```bash
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/LynxzzBot/file.git
cd babybot
npm install
npm start
```

## Installing the FFmpeg for Windows
* Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://www.gyan.dev/ffmpeg/builds/).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `ffmpeg`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
> ffmpeg -version
```


## Installing the libwebp for Windows
* Unduh salah satu versi libwebp yang tersedia dengan mengklik [di sini](https://developers.google.com/speed/webp/download).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `libwebp`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
setx /m PATH "C:\libwebp\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal libwebp, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
webpmux -version
```

## Donate
- [Saweria](https://sociabuzz.com/cybervin/donate)

# Features
- Cek [disini](https://github.com/LynxzzBot/file/blob/main/help.js)

# Thanks to
* [`Baileys`](https://github.com/adiwajshing/Baileys)
* [`Xinz-Team`](https://github.com/Xinz-Team)