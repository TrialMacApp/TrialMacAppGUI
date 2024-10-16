## 项目简介

使用 [Dobby](https://github.com/jmpews/Dobby) 制作的 macOS 环境动态注入库，用来更改部分软件的试用逻辑。

## 为什么要建这个项目

为了让更多消费者能更加了解某个 APP，我创建了此脚本用来支持诸多 APP 的较长时间试用，因为很多软件只有 7 天、15 天的试用期，不太够充分了解其所有能力。

使用此脚本的所有人，应该在完全了解或充分使用一个 APP 后购买正版使用。

另外多说一句，有些网站，挂着盗版的资源还要卖钱，并且还真的有xx花钱用盗版软件。要不找开源或免费替代软件，要不花钱买正版，或者拼车买正版。

## 注意

```diff
+ 已支持x86和arm双端，x86测试不完全

+ 这是完全免费的 不用花一毛钱

+ app有helper的先装helper，我还没有对helper做同一处理，例如stash、Macs Fan Control 等软件

+ 我的试用也不一定很全面，有问题有bug就提issue
```

## 如何使用

1.  [点我下载](https://github.com/TrialMacApp/TrialMacApp/archive/refs/heads/master.zip) 然后解压
2.  打开电脑自带的 `终端`
3.  在窗口中输入 `cd ` 注意 cd 两个字母后有一个空格
4.  打开 `Finder` 把上面解压出来的 **文件夹** ，拖动到 `终端` 里，然后按下回车键
5.  输入 `./TrialMacApp` 回车，开始使用

## Releases下载GUI程序，命令行支持所有APP试用

> 命令行保持最新，GUI程序不定时更新

![](/img/1.png "")

## 感谢以下项目

- jmpews - [Dobby](https://github.com/jmpews/Dobby)
- QiuChenlyOpenSource - [SearchHexCodeInFile](https://github.com/QiuChenlyOpenSource/SearchHexCodeInFile)
- alexzielenski - [optool](https://github.com/alexzielenski/optool)
- tyilo - [insert_dylib](https://github.com/tyilo/insert_dylib)
- QiuChenly - [InjectLib](https://github.com/QiuChenly/InjectLib) 

## 常见问题

1.  

## APP支持申请

 - 可以直接在issue里提，遵循模板规则

## 支持的 app 如下

> ARM 一定支持的，因为我本身就是ARM机器

> 版本是 ✅ 则支持所有版本，支持所有版本的则支持X86

> MAS = Mac App Store （代表是否从MAS下载的）

| 序号 | 名称                 | 版本     | MAS |  ARM | X86 |备注             |
| -- | -------------------- | -------- | --- | --- | --- | ---------------- |
| 1 | Macs Fan Control | 1.5.16 |  | ✅ |  |  |
| 2 | Things3 | ✅ |  | ✅ | ✅ |  |
| 3 | Xnip | ✅ | ✅ | ✅ | ✅ |  |
| 4 | Transmit | ✅ | ✅ | ✅ | ✅ |  |
| 5 | BuhoCleaner | ✅ |  | ✅ | ✅ |  |
| 6 | Image2Icon | 2.18 | ✅ | ✅ |  |  |
| 7 | FileZilla Pro | 3.66.5 | ✅ | ✅ |  |  |
| 8 | menubarx | ✅ | ✅ | ✅ | ✅ |  |
| 9 | SQLPro Studio | ✅ | ✅ | ✅ | ✅ |  |
| 10 | Texifier | 1.9.27 |  | ✅ |  |  |
| 11 | Sketch | ✅ | ✅ | ✅ | ✅ |  |
| 12 | Omi录屏专家 | ✅ | ✅ | ✅ | ✅ |  |
| 13 | CleanShot X | 4.7 |  | ✅ |  |  |
| 14 | Aldente Pro | 1.28.4 |  | ✅ |  |  |
| 15 | Table Plus | 6.0.4 |  | ✅ |  | 暂停支持 |
| 16 | Doppler | ✅ |  | ✅ | ✅ |  |
| 17 | Text Scanner | 1.7.5 | ✅ | ✅ |  | 终端执行其二进制文件 |
| 18 | 欧陆词典 | ✅ |  | ✅ | ✅ |  |
| 19 | Blocs | ✅ |  | ✅ | ✅ |  |
| 20 | PlistEdit Pro | ✅ |  | ✅ | ✅ |  |
| 21 | Downie 4 | ✅ |  | ✅ | ✅ |  |
| 22 | Typora | ✅ |  | ✅ | ✅ |  |
| 23 | Stash | 2.6.4 |  | ✅ |  |  |
| 24 | App Cleaner | 8.4.1 |  | ✅ |  |  |
| 25 | Hype4 | ✅ | ✅ | ✅ | ✅ |  |
| 26 | Infuse | ✅ | ✅ | ✅ | ✅ |  |
| 27 | Kaleidoscope | ✅ |  | ✅ | ✅ |  |
| 28 | Pixelmator Pro Trial | ✅ |  | ✅ | ✅ |  |
| 29 | Proxyman | 5.2.0 |  | ✅ |  |  |
| 30 | ServerCat | 1.12 | ✅ | ✅ |  |  |
| 31 | Core Tunnel | ✅ | ✅ | ✅ | ✅ |  |
| 32 | Navicat Premium | ✅ | ✅ | ✅ | ✅ | 借鉴 Qiuchenly |
| 33 | Permute 3 | ✅ |  | ✅ | ✅ |  |
| 34 | Eon | ✅ |  | ✅ | ✅ |  |
| 35 | UctoX 2 | ✅ |  | ✅ | ✅ |  |
| 36 | Rottenwood | ✅ |  | ✅ | ✅ |  |
| 37 | Judo | ✅ | ✅ | ✅ | ✅ | 免登录 有几个功能不能用 |
| 38 | Querious | ✅ |  | ✅ | ✅ |  |
| 39 | ForkLift | ✅ |  | ✅ | ✅ |  |
| 40 | CleanMyMac-MAS | ✅ | ✅ | ✅ | ✅ | 不包括状态栏按钮 |
| 41 | Reveal | 49 (20463) |  | ✅ |  |  |
| 42 | HoudahSpot | ✅ |  | ✅ | ✅ |  |
| 43 | Focus | ✅ |  | ✅ | ✅ | https://heyfocus.com |
| 44 | SimpleMind | ✅ | ✅ | ✅ | ✅ | 思维导图软件 |
| 45 | Flacbox | ✅ | ✅ | ✅ | ✅ | 音乐软件 |
| 46 | PDF Editor | ✅ | ✅ | ✅ | ✅ | https://apps.apple.com/gb/app/pdf-editor-for-adobe-pdf-file/id6469578160 |
| 47 | Notebooks | ✅ |  | ✅ | ✅ | https://www.notebooksapp.com/mac/ |
| 48 | Final Cut Pro Trial | ✅ |  | ✅ | ✅ | 每次打开都会提示购买，忽略就行 |
| 49 | Mp3tag | ✅ |  | ✅ |  | 输入任意激活信息点激活 |
| 50 | Ulysses | ✅ | ✅ | ✅ | ✅ |  |
