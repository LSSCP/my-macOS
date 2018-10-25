# My macOS

本笔记旨在收录一些能打造高生产力和舒适 macOS 环境的软件。

目录

- [参考](#参考)
- [生产力](#生产力)
- [系统](#系统)
- [开发](#开发)
    - [工具](#工具)
    - [命令行](#命令行)
    - [misc](#misc)
- [写字](#写字)
- [日常](#日常)
    - [Chrome](#chrome)
    - [下载](#下载)
    - [特定用途](#特定用途)
- [无用](#无用)
- [技巧](#技巧)

## 参考

- [HelloGitHub](https://github.com/521xueweihan/HelloGitHub) - 好玩、有意义的开源项目集合收集。
- [open-source-mac-os-apps](https://github.com/serhii-londar/open-source-mac-os-apps) - macOS 开源应用程序列表。
- [awesome-mac](https://github.com/jaywcjlove/awesome-mac)
- [my-mac-os](https://github.com/nikitavoloboev/my-mac-os)
- [awesome-opensource-apps](https://github.com/unicodeveloper/awesome-opensource-apps)  - 开源应用整理。
- [Best-App](https://github.com/hzlzh/Best-App) - 收集&推荐优秀的 Apps/硬件/技巧/周边等
- [堪称神器的命令行软件](https://www.zhihu.com/question/59227720)
- [配置适合工作学习的桌面环境](https://juejin.im/post/5ba294ef5188255c775d97c2)

## 生产力

- [Alfred](https://www.alfredapp.com/) - 启动器
    - 自定义唤醒快捷键 `⌥<空格>`，Spotlight 的快捷键改成 `⇧⌥<空格>`。
    - [Amazing Alfred Workflows](https://github.com/learn-anything/alfred-workflows#readme) - Workflow 整理
    - [这篇文章](https://medium.com/@nikitavoloboev/writing-alfred-workflows-in-go-2a44f62dc432) 教你怎么用 Go 语言和 [AwGo](https://github.com/deanishe/awgo) 库开发 workflow。
- [iTerm2](https://www.iterm2.com/) - 终端利器
    - 自定义唤醒快捷键 `⌘.`。
    - 搭配 Zsh 使用更佳，可用 [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) 配置。
    - [Zsh Plugins List](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#git) - zsh 插件列表
- [Karabiner](https://pqrs.org/osx/karabiner) - 自定义键盘映射
    - 可以将键盘映射成你想要的任意样子，还支持外接键盘。
    - 我将 `caps lock` 映射成了 Hyper 键，用于唤醒常用软件和导航。如何设置可以参考 [这里](https://github.com/Vonng/Capslock)
- [Contexts](https://contexts.co/) - 窗口切换器（[软件介绍](https://www.zhihu.com/question/19897698/answer/376711117)）
    - 自定义搜索快捷键 `⇧⌘'`。
- [Moom](https://manytricks.com/moom/) - 窗口管理
- [1Password](https://1password.com/) - 密码管理
- [Fantastical](https://flexibits.com/fantastical) - 日历
    - 管理有明确开始时间的日程性事件，如会议。
    - 用 iCloud 同步日历。
- [Things3](https://culturedcode.com/) - 任务管理
    - 管理时间上可安排的任务性事件；收集碎片时间下可做的事件。
    - 苹果自带的 Reminer 辅助闹钟提醒。
- [Noizio](http://noiz.io/) - 白噪音软件
    - 写代码或阅读时听，有利于集中注意力。
- [PDF Expert](https://pdfexpert.com/) - PDF 阅读器和编辑器
- [MindNode](https://mindnode.com/) - 制作思维导图
- [Reeder](http://reederapp.com/) - RSS 阅读器
    - 个人选择 [inoreader](https://www.inoreader.com/) 服务。
    - 配合 [RSSHub](https://github.com/DIYgod/RSSHub) 和 [即刻](https://www.ruguoapp.com/)，几乎可以订阅任何网站。

## 系统

- [Bartender](https://www.macbartender.com/) - 顶部菜单栏管理
- [Popclip](https://pilotmoon.com/popclip/) - 文本操作菜单
    - [PopClip Extensions](https://pilotmoon.com/popclip/extensions/) - 插件列表
- [The Unarchiver](https://theunarchiver.com/) - 压缩软件
- [Hazel](https://www.noodlesoft.com/) - 管理文件的自动化软件
- [CleanMyMac](https://cleanmymac.com/) - 系统清理
- [Shadowsocks](https://github.com/shadowsocks/ShadowsocksX-NG) - 不解释

## 开发

### 工具

- [Visual Studio Code](https://code.visualstudio.com/) - 宇宙级编辑器
- [macVim](http://macvim-dev.github.io/macvim/) - GUI Vim
    - [这里](https://github.com/fjchen7/vimrc) 可以查看我的 Vim 配置
- [Dash](https://kapeli.com/dash) - API 文档浏览器
    - 将 Markdown 做成文档，必须先生成 HTML 文件，再用工具 [dashing](https://github.com/technosophos/dashing) 做成 Docset。
    - 同类工具：[devdocs.io](http://devdocs.io/)
- [SnippetsLab](https://www.renfei.org/snippets-lab/) - 代码片段管理
    - 支持将代码片段同步到 GitHub Gists 上。
- [TabPlus](https://tableplus.io/)  - SQL 数据库管理软件。 [软件介绍](https://www.waerfa.com/tableplus-review) 。
    - [sequelpro](https://github.com/sequelpro/sequelpro) - 同类工具，但只支持 MySQL
- [octotree](https://github.com/buunguyen/octotree) - Chrome 插件，在 GitHub 和 GitLab 网站上显示项目目录结构。
    - [GayHub](https://github.com/jawil/GayHub) - 同类插件。

### 命令行

主要是一些第三方命令，Linux 的基本命令就不收集了。

- [fd](https://github.com/sharkdp/fd) - 简单、快速、友好的 `find` 替代命令。
- [jq](https://github.com/stedolan/jq) - JSON 处理。
- [bat](https://github.com/sharkdp/bat) - `cat` 的加强版，带高亮和分页，并且与 Git 集成。
- [fzf](https://github.com/junegunn/fzf) - 模糊搜索。
- [m-cli](https://github.com/rgcr/m-cli) - 提供 macOS 系统级别的实用功能。
- [mas](https://github.com/mas-cli/mas) - 用 CLI 操作 Mac App Store。[介绍](https://sspai.com/post/43239)。
- [tldr](https://github.com/tldr-pages/tldr) - 速查命令。同类的还有 [cheat.sh](https://github.com/chubin/cheat.sh) 和 [Rico's cheatsheets](https://devhints.io/)。
- [thefuck](https://github.com/nvbn/thefuck) - 打一句 `fuck` 就会自动更正命令。
- [httpie](https://httpie.org/) - 友好的 HTTP 客户端。
    - [httpstat](https://github.com/reorx/httpstat) - 同类工具。无依赖单 Python3 文件实现，适合学习。
- [htop](https://github.com/hishamhm/htop) - 比 `top` 美观方便的进程监控工具。同类的 [glances](https://github.com/nicolargo/glances) 也不错。
- [ctop](https://github.com/bcicen/ctop) - 类 `top` 展示效果的 docker 容器监控工具
- [screenfetch](https://github.com/KittyKatt/screenFetch) - 打印系统信息。
- [tmux](https://github.com/tmux/tmux) - 终端复用工具。
- [lazygit](https://github.com/jesseduffield/lazygit) - 在终端提供 Git 的 UI 界面。
- [archey-osx](https://github.com/obihann/archey-osx) - 在终端显示 macOS 的基本信息

### misc

- [PPRows](https://github.com/jkpang/PPRows) - 统计代码数量
- [codeshare](https://codeshare.io/) 和 [Snipper.io](https://snipper.io/) - 在浏览器中实时共享代码，电话面试时很方便。
- [StackBlitz](https://stackblitz.com/) 和 [CodeSandbox](https://codesandbox.io/) - 前端语言的在线 IDE

## 写字

- [Typora](https://typora.io/) - 个人比较喜欢的 Markdown 编辑软件
    - 可用 VSCode 插件 [Markdown TOC](https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc) 自动生成目录。
    - `tree -N` 可以生成文件目录树，在 GitHub 上表示项目结构时常用到。
    - [shields.io](https://shields.io) 可以在 Markdown 中插入 Metadata 标签。
- [Day One](http://dayoneapp.com/) -  日记
- [Bear](https://www.yinxiang.com/) - 存放技术笔记
- [Marked 2](http://marked2app.com/) - Markdown 浏览器
- [PicGo](https://github.com/Molunerfinn/PicGo) - 图床上传工具，支持国内主流图床服务
- [carbon](https://github.com/dawnlabs/carbon) - 将代码片段用图片生成出来。[在线生成](https://carbon.now.sh)。

GIF 制作

- [termtosvg](https://github.com/nbedos/termtosvg) - 将终端命令会话录制成SVG动画。[效果](https://svgur.com/s/7t5)。
- [Kap](https://getkap.co/)（[介绍](https://sspai.com/post/43212)） 和 [LICEcap](https://www.cockos.com/licecap/) - 录屏。
- [gifify](https://github.com/vvo/gifify) 和 [GIF Brewery](http://gifbrewery.com/) - 将视频片段做成 GIF

中文写作排版指导

- [document-style-guide](https://github.com/ruanyf/document-style-guide)
- [中文文案排版指北](https://github.com/mzlogin/chinese-copywriting-guidelines)

## 日常

- [IINA](https://github.com/lhc70000/iina) - 最好看的视频播放器
- [欧陆词典](https://www.eudic.net/) - 英文词典

### Chrome

- [Steward](https://chrome.google.com/webstore/detail/steward-a-command-launche/dnkhdiodfglfckibnfcjbgddcgjgkacd) - Chrome 的  Alfred
- [OneTab](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall?hl=zh-CN) - 标签整理
- DuckDuckGo Privacy Essentials - DuckDuckGo 不收集隐私的搜索
- [书签侧边栏](https://chrome.google.com/webstore/detail/bookmark-sidebar/jdbnofccmhefkmjbkkdkfiicjkgofkdh) - 将书签移动到浏览器两侧
- [Imagus](https://chrome.google.com/webstore/detail/imagus/immpkjjlgappgfkkfieppnmlhakdmaab) - 把鼠标放在想看的图片上，它就会自动被放大。
- [Save Page WE](https://chrome.google.com/webstore/detail/save-page-we/dhhpefjklgkmgeafimnjhojgjamoafof) - Chrome 默认保存的单 html 文件会丢失格式，而这个插件保存的不丢失。
- [Extension Manager](https://chrome.google.com/webstore/detail/extension-manager/gjldcdngmdknpinoemndlidpcabkggco) - 插件管理，同类中比较好看的。但 Steward 可取代。

B 站（[参考](https://sspai.com/post/45860)）

- Pakku - 合并相同弹幕
- 哔哩哔哩助手 - B 站扩展辅助
- [Bilibili 屏蔽词分享平台](http://static.sspai.com/post/45860) - 同步屏蔽词

### 下载

- [Aria2GUI](https://github.com/yangshun1029/aria2gui) - 下载工具 Aria2 的 GUI 客户端
    - 可突破百度云限速，配合 Chrome 插件 [BaiduExporter](https://github.com/acgotaku/BaiduExporter) 使用更佳。
- [kcptun](https://github.com/xtaci/kcptun)  - UDP 传输
- [annie](https://github.com/iawia002/annie) - 视频下载程序，支持国内大部分视频网站：[列表](https://github.com/iawia002/annie#supported-sites)
- [youtube-dl](https://github.com/rg3/youtube-dl) - 视频下载工具，功能比 annie 全。
    - 支持几百个国内外主流视频网站：[列表](https://github.com/rg3/youtube-dl/blob/master/docs/supportedsites.md)
    - [使用示例](https://hellogithub.com/periodical/volume/21/#youtube-dl)
- [Transmission](https://www.transmissionbt.com/) - BitTorrent 客户端

### 特定用途

- [XnConvert](https://www.xnview.com/en/xnconvert/#downloads) - 照片批量处理（[软件介绍](https://sspai.com/post/45283)）
- [syncPlaylist](https://github.com/Denon/syncPlaylist) - 在网易云音乐与 QQ 音乐之间同步歌单。使用简单。
- [musicbox](https://github.com/darknessomi/musicbox) - 网易云音乐命令行版本
- [Convertio](https://convertio.co/zh/) 和 [Office Converter](http://cn.office-converter.com/) - 各种文件的格式转换，包括 office 文件、图片、视频音频、电子书等

壁纸更换

- [Irvue](https://itunes.apple.com/us/app/irvue/id1039633667)
- Kuvva
- Pap.er
- [好壁纸尽在此处](https://sspai.com/topic/101) - 少数派壁纸专题

图片与 PDF 处理

- [TinyPNG](https://tinypng.com) 和 [Optimizilla](https://imagecompressor.com/zh/) - 图片压缩
- [Smallpdf](https://smallpdf.com/cn)、[iLovePDF](http://www.ilovepdf.com/) 和 [iLoveIMG](http://www.iloveimg.com/zh_cn) - 图片与 PDF 在线编辑与格式转换

## 无用

似乎有一点用

- [kitty](https://sw.kovidgoyal.net/kitty/) - 使用 GPU 渲染的终端模拟器，视觉效果顺滑。
- [plus1s.live](https://github.com/HFO4/plus1s.live) - 用 ASCII 字符在终端展现视频
- [browsh](https://github.com/browsh-org/browsh) - 基于文本的浏览器，可降低带宽，提高连接稳定性。
- [unimatrix](https://github.com/will8211/unimatrix) - 模拟「黑客帝国」的终端动画。
- [Cartoonify](https://github.com/danmacnish/cartoonify) - 使用 Goolge AI 将图片变为手绘涂鸦风格。

没什么用

- [stacksort](https://github.com/gkoberger/stacksort) - 一个自动去 StackOverflow 上搜代码的排序算法，会一个个试直到跑对为止。
- [nbg-go](https://github.com/xxhomey19/nba-go) - 在终端观看 NBA。
- [Re - scam](https://www.rescam.org/) - 使用电子邮件聊天的机器人，它被设计用来与邮件诈骗犯聊天。
- [ChatBotCourse](https://github.com/warmheartli/ChatBotCourse) - 动手做聊天机器人的教程
- [itunes-artwork-finder](https://github.com/bendodson/itunes-artwork-finder) - 获取高清商品封面，包括影视剧、应用程序、书籍、播客、专辑等。
- [Proton](https://github.com/ValveSoftware/Proton) - 允许 Linux 和 MacOS 运行 Windows 独占的 Steam 游戏，基于 Wine 开发。

## 技巧

- [Chrome 原生截图方式](https://segmentfault.com/a/1190000011623185)
- [MacOS 的安全和隐私指南](https://github.com/drduh/macOS-Security-and-Privacy-Guide/blob/master/README-cn.md) - 用企业级标准保护私人数据。
- [开启 macOS 系统隐藏功能](https://sspai.com/post/41695)
- [AppScript 教程入门](https://sspai.com/post/46912)
- [云备份 macOS 软件列表](https://sspai.com/post/43265) - 用脚本维护 App 列表，再借助 homebrew 和 mas 一键恢复。
- [用 rsync  备份 macOS 的文件](https://sspai.com/post/41967)

清洁

- [了解如何清洁您的 Mac 笔记本电脑](https://support.apple.com/zh-cn/HT204172#portables)
- [如何清洁 MacBook 或 MacBook Pro 的键盘](https://support.apple.com/zh-cn/HT205662)
- [电子设备清理指南](https://sspai.com/post/43886)