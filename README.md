<h1 align="center">ꪶ𝗖𝗵𝗲𝗲𝗺𝘀 𝗕𝗼𝘁-𝗠𝗗ꫂ<br></h1>
<p align="center">
  <img src="https://telegra.ph/file/8adfac9d34c43ce444fbf.jpg" width="540" height="300" />
  Credits to <a href="https://github.com/DGXeon" target="_blank">Xeon</a> and <a href="https://github.com/youssefbotrouss2" target="_blank">Youssef</a>
</p>

<p align="center">
Cheems Bot Multi Device is a automated whatsapp bot forked by <a href="https://github.com/Thriam" target="_blank">Thriam</a> from <a href="https://github.com/DGXeon" target="_blank">Xeon</a> using <a href="https://github.com/adiwajshing/Baileys" target="_blank">Baileys</a> and <a href="https://github.com/nodejs" target="_blank">Nodejs</a>. Dont forget to give a star bro.
</p>

<p align="center">
<a href="https://youtu.be/imFIX-Wrt3s"><img title="Size" src="https://img.shields.io/badge/Tutorial-Video-green"></a>
</p>

------

# ```Bot Info```
<p align="center">
<a href="https://github.com/DGXeon/followers"><img title="Followers" src="https://img.shields.io/github/followers/DGXeon?color=red&style=flat-square"></a>
<a href="https://github.com/DGXeon/CheemsBot-MD/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/DGXeon/CheemsBot-MD?color=blue&style=flat-square"></a>
<a href="https://github.com/DGXeon/CheemsBot-MD/network/members"><img title="Forks" src="https://img.shields.io/github/forks/DGXeon/CheemsBot-MD?color=red&style=flat-square"></a>
<a href="https://github.com/DGXeon/CheemsBot-MD/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/DGXeon/CheemsBot-MD?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/DGXeon/CheemsBot-MD"><img title="Open Source" src="https://img.shields.io/badge/Author-Xeon%20Bot%20Inc.-red?v=103"></a>
<a href="https://github.com/DGXeon/CheemsBot-MD/"><img title="Size" src="https://img.shields.io/github/repo-size/DGXeon/CheemsBot-MD?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FDGXeon%2FCheemsBot-MD&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/DGXeon/CheemsBot-MD/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>
<p align='center'>
    </p>

-------

# Setup For Deployment 👇

## `SETTINGS`

- CHANGE OWNER NUMBER [Here](https://github.com/Thriam/CheemsBot-MD/config.js#L25)
- CHANGE OWNER NAME [Here](https://github.com/Thriam/CheemsBot-MD/config.js#L30)
- CHANGE BOT NAME [Here](https://github.com/Thriam/CheemsBot-MD/config.js#L29)

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Thriam/CheemsBot-MD/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/DGXeon/CheemsBot-MD.git
cd CheemsBot-MD
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
git clone https://github.com/DGXeon/CheemsBot-MD
cd CheemsBot-MD
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
git clone https://github.com/DGXeon/CheemsBot-MD
cd CheemsBot-MD
npm start
```
## `For 24/7 Activation`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
