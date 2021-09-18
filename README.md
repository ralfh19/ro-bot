<p align="center">
<img src="https://i.postimg.cc/FR0j97j5/image.jpg" alt="RO-BOT" width="500"/>


</p>
<p align="center">
<a href="#"><img title="RO-BOT" src="https://img.shields.io/badge/RO-BOT -blue?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">

---

# RO-BOT
## Informasi
> RO-BOT adalah recode an dari muzza-bot)
>
>

## Bugs and Tester
* Jika kamu menemukan bug jangan lupa buka Issues
* Info Lebih Lanjut, Chat [owner-ronove](https://wa.me/6282182623238)
* Kamu bisa testing fitur RO-BOT [disini](https://wa.me/62821826232389?text=.menu)

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)
* Lolhuman Api, Regist on [this](https://api.lolhuman.xyz/register) and get a free APIKEY
* xteam api, Regist on [this](https://justaqul.xyz/auth/registration) and get a free APIKEY
* [Image Magick](https://imagemagick.org/script/download.php) ( for nulis command, Centang Kolom 1,2,3,5,6)

# Instalasi
## For Windows
```bash
git clone https://github.com/ralfh19/ro-bot.git
cd ro-bot
npm start
```
## For Termux
```pkg install nodejs -y
pkg install ffmpeg
pkg install imagemagick
cd ro-bot
npm start
```
>

## For VPS
```bash
apt install nodejs git ffmpeg imagemagick
git clone git clone https://github.com/ralfh19/ro-bot.git
cd ro-bot
npm start
```

## Edit file
- edit owner dll disini [this section](https://github.com/ralfh19/ro-bot/blob/main/Farid.js/#L52)


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
