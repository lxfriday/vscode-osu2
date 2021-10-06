# VSCODE OSU Mode!!!

OSU Mode is a fork of Power Mode, they said it shouldn't be done...

However, after being bored and realizing that VSCode was not the only modern editor without it, I knew I didn't have to try, but I couldn't let VSCode live in the shadow of its big brother or Atom.

I present you, **VSCODE OSU MODE**!!! (now with Genshin Impact Characters!)

![DEMO](https://raw.githubusercontent.com/ao-shen/vscode-power-mode/master/images/demo-osu.gif)

- To enable OSU mode, add `"osumode.enabled": true` to your settings.
- To disable combo counter, add `"osumode.enableComboCounter": false,` to your settings.
- To enable letter explosions at the cursor when you type, add `"osumode.enableCursorExplosions": true,` to your settings.
- Set your own imgs, add `"osumode.preferImgList": ['https://img.png', ...]` array
  - note: imgs can not be local imgs, `C:\\folder\\xzxzx.png`... will be useless, imgs must be `http://fdsfsdf.png`
  - you can upload imgs to [https://imgurl.org/](https://imgurl.org/), then copy the address to `osumode.preferImgList`
- Set back img frequency, add `"osumode.imgInterval" : number`, `number` can be any number,better not too small or too big
- To disable default imgs(by the extension), add `"osumode.enableDefaultImgs": false` to your settings.
- To disable randomly imgs, add `"osumode.enableRandomPlayImgs": false` to your settings, default `true` and imgs will be played in order.

## Features:

- NEW: COMBO COUNTER
- Everything Power Mode has

## Acknowledgements:

- Thanks to [@hoovercj](https://github.com/hoovercj) for [Powermode](https://github.com/hoovercj/vscode-power-mode)

## Changelog:

- v3.1.0
  - Updated Settings to be "osumode" instead of "powermode"!
  - Removed existing powermode presets, now you can install Osumode and Powermode separately!
  - Removed extra settings that only pertained to Powermode features!
  - Removed status bar combo counter!
- v3.0.1
  - Updated Readme!
- v3.0.0
  - Forked from Power Mode!
  - Added per character cursor explosions!
  - Added combo counter animations!
  - Added combo images!
