本笔记旨在收录一些能打造高生产力和舒适 macOS 环境的软件。

目录
- [软件](#%E8%BD%AF%E4%BB%B6)
    - [生产力](#%E7%94%9F%E4%BA%A7%E5%8A%9B)
    - [系统](#%E7%B3%BB%E7%BB%9F)
    - [开发](#%E5%BC%80%E5%8F%91)
    - [写作](#%E5%86%99%E4%BD%9C)
    - [功能](#%E5%8A%9F%E8%83%BD)
    - [非必要](#%E9%9D%9E%E5%BF%85%E8%A6%81)
- [命令行](#%E5%91%BD%E4%BB%A4%E8%A1%8C)
- [参考](#%E5%8F%82%E8%80%83)
- [技巧](#%E6%8A%80%E5%B7%A7)

## 软件

### 生产力

[Alfred](https://www.alfredapp.com/) - 启动器

- 自定义唤醒快捷键 `⌥<空格>`，Spotlight 的快捷键改成 `⇧⌥<空格>`。
- [Amazing Alfred Workflows](https://github.com/learn-anything/alfred-workflows#readme)
- [这篇文章](https://medium.com/@nikitavoloboev/writing-alfred-workflows-in-go-2a44f62dc432) 教你怎么用 Go 语言和 [AwGo](https://github.com/deanishe/awgo) 库开发 workflow。

[iTerm2](https://www.iterm2.com/) - 终端利器

- 自定义唤醒快捷键 `⌘.`。
- 搭配 Zsh 使用更佳，可用 [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) 配置。
- [Zsh Plugins List](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#git)

[Contexts](https://contexts.co/) - 窗口切换器（[软件介绍](https://www.zhihu.com/question/19897698/answer/376711117)）

- 自定义搜索快捷键 `⇧⌘'`。

[Moom](https://manytricks.com/moom/) - 窗口管理

[1Password](https://1password.com/) - 密码管理

[Fantastical](https://flexibits.com/fantastical) - 日历

- 管理有明确开始时间的日程性事件，如会议。
- 用 iCloud 同步日历。

[Things3](https://culturedcode.com/) - 任务管理

- 管理时间上可安排的任务性事件；收集碎片时间下可做的事件。
- 苹果自带的 Reminer 辅助闹钟提醒。

[Noizio](http://noiz.io/) - 白噪音软件

- 写代码或阅读时听，有利于集中注意力。

[PDF Expert](https://pdfexpert.com/) - PDF 阅读器和编辑器

[MindNode](https://mindnode.com/) - 制作思维导图

[Reeder](http://reederapp.com/) - RSS 阅读器

- 个人选择 [inoreader](https://www.inoreader.com/) 服务。
- 配合 [RSSHub](https://github.com/DIYgod/RSSHub)，几乎可以订阅任何网站。

### 系统

[Bartender](https://www.macbartender.com/) - 顶部菜单栏管理

[Popclip](https://pilotmoon.com/popclip/) - 文本操作菜单

- 主要用来搜索和添加事务到 Fantastical 和 Things3 中。
- [PopClip Extensions](https://pilotmoon.com/popclip/extensions/)

[The Unarchiver](https://theunarchiver.com/) - 压缩软件

[Hazel](https://www.noodlesoft.com/) - 管理文件的自动化软件

[CleanMyMac](https://cleanmymac.com/) - 系统清理

[Shadowsocks](https://github.com/shadowsocks/ShadowsocksX-NG) - 不解释

### 开发

[Visual Studio Code](https://code.visualstudio.com/) - 宇宙级编辑器

[macVim](http://macvim-dev.github.io/macvim/) - GUI Vim

- [这里](https://github.com/fjchen7/vimrc) 可以查看我的 Vim 配置

[Dash](https://kapeli.com/dash) - API 文档浏览器

- 将 Markdown 做成文档，必须先生成 HTML 文件，再用工具 [dashing](https://github.com/technosophos/dashing) 做成 Docset。
- 同类工具：[devdocs.io](http://devdocs.io/)

[SnippetsLab](https://www.renfei.org/snippets-lab/) - 代码片段管理

- 支持将代码片段同步到 GitHub Gists 上。

[Astral](https://astralapp.com/) - 一个管理 GitHub  Stars 的网站

### 写作

[Typora](https://typora.io/) - 个人比较喜欢的 Markdown 编辑软件

- 可用 VSCode 插件 [Markdown TOC](https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc) 自动生成目录。
- `tree -N` 可以生成文件目录树，在 GitHub 上表示项目结构时常用到。
- [shields.io](https://shields.io) 可以在 Markdown 中插入 Metadata 标签。
- 中文写作排版指导： [document-style-guide](https://github.com/ruanyf/document-style-guide) 和 [中文文案排版指北](https://github.com/mzlogin/chinese-copywriting-guidelines) 

[Day One](http://dayoneapp.com/) -  日记

- 存放个人所想所感，包括生活与工作。
- 记录个人的阶段性状态、不足与成就，进行反思与总结。
- 应该时常回顾。

[印象笔记](https://www.yinxiang.com/) - 云笔记本

- 存放学习笔记，包括技术和人文的学习。这些笔记会被经常修改和翻阅。
- 收集碎片阅读的文章，并集中整理。
- 支持 Markdown 后，编辑就变得好用了。

[Marked 2](http://marked2app.com/) - Markdown 浏览器

[PicGo](https://github.com/Molunerfinn/PicGo) - 图床上传工具，支持国内主流图床服务

### 功能

[IINA](https://github.com/lhc70000/iina) - 最好看的视频播放器

[Kap](https://getkap.co/) - 录屏（[软件介绍](https://sspai.com/post/43212)）

- 同类软件：[LICEcap](https://www.cockos.com/licecap/)（小巧简单）和 [GIF Brewery](http://gifbrewery.com/)（可将视频片段截取成 GIF）

[欧陆词典](https://www.eudic.net/) - 英文词典

[Aria2GUI](https://github.com/yangshun1029/aria2gui) - 下载工具 Aria2 的 GUI 客户端

[carbon](https://github.com/dawnlabs/carbon) - 生成展示代码片段的精美图片

- 也可以 [在线生成](https://carbon.now.sh)

### 非必要

这些软件在特定场景下可能用得到，但不是平时必备的。

[Irvue](https://itunes.apple.com/us/app/irvue/id1039633667) - 壁纸更换

- 同类软件：Kuvva 和 Pap.er

[Snipaste](https://zh.snipaste.com/) - 功能强大的截图工具

[XnConvert](https://www.xnview.com/en/xnconvert/#downloads) - 照片批量处理（[软件介绍](https://sspai.com/post/45283)）

[RDM](https://github.com/avibrazil/RDM) - 改变屏幕分辨率

[kcptun](https://github.com/xtaci/kcptun) - UDP 传输

[Transmission](https://www.transmissionbt.com/) - BitTorrent 客户端

[PPRows](https://github.com/jkpang/PPRows) - 统计代码数量

## 命令行

主要是一些第三方命令行工具，默认的 UNIX/Linux 命令在这里就不列举了。

- [fzf](https://github.com/junegunn/fzf) - 模糊搜索。
- [homebrew](https://brew.sh/) - macOS 的包管理工具。
- [m-cli](https://github.com/rgcr/m-cli) - 提供 macOS 系统级别的实用功能。
- [mas](https://github.com/mas-cli/mas) - 用 CLI 方式操作 Mac App Store。[介绍](https://sspai.com/post/43239)。
- [tldr](https://github.com/tldr-pages/tldr) - 速查命令。同类的还有 [cheat.sh](https://github.com/chubin/cheat.sh) 和 [Rico's cheatsheets](https://devhints.io/)。
- [fd](https://github.com/sharkdp/fd) - 简单、快速、友好的 `find` 替代命令。
- [jq](https://github.com/stedolan/jq) - JSON 处理器。
- [bat](https://github.com/sharkdp/bat) - `cat` 的加强版，带高亮和分页，并且与 Git 集成。
- [thefuck](https://github.com/nvbn/thefuck) - 打一句 `fuck` 就会自动更正命令。
- [httpie](https://httpie.org/) - 非常友好的 HTTP 客户端。
- [htop](https://github.com/hishamhm/htop) - 提供更美观、更方便的进程监控工具。同类的 [glances](https://github.com/nicolargo/glances) 也不错。
- [screenfetch](https://github.com/KittyKatt/screenFetch) - 打印系统信息。
- [tmux](https://github.com/tmux/tmux) - 终端复用工具。

## 参考

- [Awesome Mac](https://github.com/jaywcjlove/awesome-mac/blob/master/README-zh.md)
- [open-source-mac-os-apps](https://github.com/serhii-londar/open-source-mac-os-apps)
- [my-mac-os](https://github.com/nikitavoloboev/my-mac-os)
- [有哪些命令行的软件堪称神器？](https://www.zhihu.com/question/59227720)
- [磨刀不误砍柴 - 配置适合工作学习的桌面环境](https://juejin.im/post/5ba294ef5188255c775d97c2)

## 技巧

- [MacOS 的安全和隐私指南](https://github.com/drduh/macOS-Security-and-Privacy-Guide/blob/master/README-cn.md)：介绍如何用企业级标准保护自己的数据。觉得太长可以直接看「病毒和恶意软件」小节。
- [云备份 macOS 软件列表](https://sspai.com/post/43265)：用脚本维护 App 列表，再借助 homebrew 和 mas 一键恢复。
- [开启 macOS 系统隐藏功能 ](https://sspai.com/post/41695)
- [AppScript 教程入门](https://sspai.com/post/46912)
- [用 rsync  备份 macOS 的文件](https://sspai.com/post/41967)

清洁

- [了解如何清洁您的 Mac 笔记本电脑](https://support.apple.com/zh-cn/HT204172#portables)
- [如何清洁 MacBook 或 MacBook Pro 的键盘](https://support.apple.com/zh-cn/HT205662)
- [电子设备清理指南](https://sspai.com/post/43886)