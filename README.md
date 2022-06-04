<h1 align="center">ꪶ𝗖𝗵𝗲𝗲𝗺𝘀 𝗕𝗼𝘁-𝗠𝗗 𝗩𝟮ꫂ<br></h1>
<p align="center">
  <img src="https://telegra.ph/file/8adfac9d34c43ce444fbf.jpg" width="540" height="300" />
</p>

<p align="center">
Daemon whatsapp is a automated whatsapp bot formked from <a href="https://github.com/DGXeon" target="_blank">Xeon</a>and modified by <a href="https://github.com/gwydion67" target="blank">Gwydion67<a> using <a href="https://github.com/adiwajshing/Baileys" target="_blank">Baileys</a> and <a href="https://github.com/nodejs" target="_blank">Nodejs</a>. 
  <b> use it well 😄
</p>

<p align="center">
<a href="https://youtu.be/imFIX-Wrt3s"><img title="Size" src="https://img.shields.io/badge/Tutorial-Video-green"></a>
</p>

------

## ```Bot Support Groups```

- [`1st GC`](https://chat.whatsapp.com/HYj9wu5Jrv6CROxyeQbHoS)
- [`2nd GC`](https://chat.whatsapp.com/LS1Xx3fSqg7FpSYSjKWhL5)

# Setup For Deployment 👇

## `SETTINGS`

- CHANGE OWNER NUMBER 
- CHANGE OWNER NAME
- CHANGE BOT NAME 
  ==> at config.js

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/gwydion67/CheemsBot-MD2/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/DGXeon/CheemsBot-MD2.git
cd CheemsBot-MD2
npm start
```
## `For Termux/Ssh/Ubuntu`
```bash
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
git clone https://github.com/DGXeon/CheemsBot-MD2
cd CheemsBot-MD2
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagemagick
apt install bash
git clone https://github.com/DGXeon/CheemsBot-MD2
cd CheemsBot-MD2
npm start
```
## `For 24/7 Activation`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
