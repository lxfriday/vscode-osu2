# VSCODE OSU Mode

![DEMO](https://raw.githubusercontent.com/lxfriday/vscode-osu2/master/images/demo-osu.gif)

- `osumode.enabled`: To disable OSU mode, add `"osumode.enabled": false` to your settings, default `true`.
- `osumode.enableComboCounter`: To disable combo counter, add `"osumode.enableComboCounter": false` to your settings, default `true`.
- `osumode.enableCursorExplosions`: To disable letter explosions at the cursor when you type, add `"osumode.enableCursorExplosions": false,` to your settings, default `true`.
- `osumode.enableBackImg`: To disable back imgs when you type, add `"osumode.enableBackImg": false` to your settings, default `true`.

The four settings above are enabled by default.`osumode.enabled` controlls the whole extension, if it is set `false`, the extension will not work.

- Set your own imgs, add `"osumode.preferImgList": ['https://img.png', ...]` array
  - note: imgs can not be local imgs, `C:\\folder\\xzxzx.png`... will be useless, imgs must be `http://fdsfsdf.png`
  - you can upload imgs to [https://imgurl.org/](https://imgurl.org/), then copy the address to `osumode.preferImgList`
- Set back img frequency, add `"osumode.imgInterval" : number`, `number` can be any number,better not too small or too big, default `50`.
- To disable default imgs(by the extension), add `"osumode.enableDefaultImgs": false` to your settings, default `true`.
- To disable random imgs, add `"osumode.enableRandomPlayImgs": false` to your settings, default `true` and imgs will be played in order, default `true`.

Default settings.

![default settings](https://raw.githubusercontent.com/lxfriday/vscode-osu2/master/images/default-settings.jpg)

在 [`imgList.json`](https://github.com/lxfriday/vscode-osu2/blob/master/imgList.json) 文件中有一个图片列表，存储了一些王者荣耀英雄皮肤图片。如果你也喜欢，可以尝试替换使用。

<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/1631544621627716b636092860_%E5%89%AF%E6%9C%AC2.png"  width="300"/></div>

<details>
<summary>展开查看 （点我 点我）</summary>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/1631544621627716b636092860_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(33)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(35)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(11)_%E5%89%AF%E6%9C%AC.png" width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(15)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(16)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(17)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(18)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(20)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(21)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(24)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(25)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(27)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(28)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(29)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(32)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(34)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(36)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(37)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(37)_%E5%89%AF%E6%9C%AC2.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(38)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(40)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(6)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(9)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/1631544621627716b636092860_%E5%89%AF%E6%9C%AC2.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(7)_%E5%89%AF%E6%9C%AC.png"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(33).jpg"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(37).jpg"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(38).jpg"  width="300"/></div>
<div><img src="https://qiniu1.lxfriday.xyz/osu-imgs/0%20(35).jpg"  width="300"/></div>
</details>

## Notice

内置图片存放于 GitHub 图床，在国内可能由于某些原因加载速度会很慢，需要耐心等待。你可以试着打开下面的图片测试你的电脑能否正常显示背景图片。

[点我测试](https://raw.githubusercontent.com/lxfriday/vscode-osu2/master/images/Character_Keqing_Portrait.png)

## Acknowledgements:

- Thanks to [@hoovercj](https://github.com/hoovercj) for [Powermode](https://github.com/hoovercj/vscode-power-mode)
- Thanks to [@ao-shen](https://github.com/ao-shen) for [OSU Mode](https://github.com/ao-shen/vscode-power-mode)

## Changelog:

- v3.3.2
  - Updated readme and icon!
- v3.3.1
  - Updated readme and compress package size!
- v3.3.0
  - Added `enableBackImg`!
- v3.2.2
  - Updated readme gif!
- v3.2.1
  - Fixed background image `z-index`
- v3.2.0
  - Added `preferImgList`!
  - Added `imgInterval`!
  - Added `enableDefaultImgs`!
  - Added `enableRandomPlayImgs`!
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
