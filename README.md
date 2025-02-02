# DouyinDownloader

一款跨平台的抖音下载器GUI，支持抖音无水印视频批量下载，基于Electron和React开发。

## 👋🏻 快速开始

请注意，DouyinDownloader目前正在积极开发中，遇到任何问题欢迎反馈及提交Issue。

## ✨ 功能

#### `1` 抖音无水印视频批量下载

DouyinDownloader 现在支持通过简单的GUI交互下载抖音无水印视频。

|                              链接形式                              | 是否支持 |
| :----------------------------------------------------------------: | :------: |
|    https://www.douyin.com/discover?modal_id=7317901979785694475    |    ✅    |
| https://www.douyin.com/user/xxxxxxxxx?modal_id=7286026282956000575 |    ✅    |

> \[!Note]
>
> 此功能正在开发中，请确保您已阅读源代码以了解如何使用。

> \[!TIP]
>
> DouyinDownloader 支持全局快捷键。
>
> |     功能     |   快捷键   |
> | :----------: | :--------: |
> | 新建链接下载 | `CTRL + N` |

设置 Cookie

> \[!Note]
>
> 在下载前请保证正确设置了 Cookie，否则将无法正确的解析资源。

![设置 Cookie](https://github.com/ppxb/DouyinDownloader/blob/master/screenshots/setcookie.png?raw=true)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fppxb%2FDouyinDownloader.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fppxb%2FDouyinDownloader?ref=badge_shield)

主界面

![主界面](https://github.com/ppxb/DouyinDownloader/blob/master/screenshots/mainwindow.png?raw=true)

设置

![设置](https://raw.githubusercontent.com/ppxb/DouyinDownloader/master/screenshots/settings.png)

批量下载链接

![批量下载链接](https://raw.githubusercontent.com/ppxb/DouyinDownloader/master/screenshots/batchurls.png)

下载前预览

![下载前预览](https://raw.githubusercontent.com/ppxb/DouyinDownloader/master/screenshots/batchurlspreview.png)

## ⚡️ 开发

```bash
$ git clone this repo
$ cd the repo
$ pnpm install
$ pnpm dev -w
```

## 🛠 构建(WIP)

> \[!Note]
>
> 现阶段未对任何平台的分发进行测试，请使用开发模式进行调试。


```bash
$ git clone this repo
$ cd the repo
$ pnpm install

# For windows
$ pnpm build:win

# For macOS
$ pnpm build:mac

# For Linux
$ pnpm build:linux

```

## 📃 License

MIT © [ppxb](https://github.com/ppxb/DouyinDownloader/blob/master/LICENSE)


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fppxb%2FDouyinDownloader.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fppxb%2FDouyinDownloader?ref=badge_large)