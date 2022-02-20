

# BOTV13
## Heroku Buildpack

Click the deploy icon below !

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kadennotermux/v13)

```bash
 > heroku/nodejs
 > https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
 > https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

## Termux
```bash
> pkg install bash
> pkg install nodejs
> pkg install libwebp
> pkg install git
> pkg install imagemagick
> pkg install ffmpeg
> termux-setup-storage
> cd /sdcard/v13
> git clone https://github.com/Lexxy24/v13.git
> cd v13
> git clone https://github.com/Lexxy24/node_modules
> npm start
```

## settings
Edit Nomor Owner DLL `'./settings/setting.json'`

```ts
{
"BotName":"NanaBotz",
"OwnerNumber":"62857890047322",
"OwnerName":"LexxyOFC",

"GithubOwner":"https://github.com/Lexxy24",
"YoutubeOwner":"https://youtube.com/c/LEX4YOUU",
"GroupOwner":"https://chat.whatsapp.com/DiexeOhNqQv5Qsm6Y2vD4d"
}
