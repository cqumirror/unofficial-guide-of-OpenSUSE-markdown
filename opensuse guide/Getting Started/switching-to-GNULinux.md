# 2. 切换到 GNU/Linux

切换到一个新的、完全不同的操作系统要付出相当大的努力 —— 当然你没必要完全切换，没有什么可以阻止你在同一台计算机上使用多个操作系统。本章介绍了在进入 GNU/Linux 的奇妙世界之前需要考虑的一些事情。

## 2.1 为什么是 GNU/Linux?

有很多原因使得数百万人喜欢使用 GNU/Linux  —— 它们通常取决于每个人的个人观点，可以基于技术、财务、伦理或哲学等原因。这里列出了一些选择 GNU/Linux 的最常见的原因。

- 安全 ：诸如病毒、间谍软件等问题几乎不存在。
- 便于维护：忘记扫描病毒和间谍软件、碎片整理、清理注册表数据库、频繁重启等问题吧。
- 稳定性： GNU/Linux 非常稳定。个别应用程序可能会崩溃，但操作系统本身崩溃的情况非常罕见。
- 软件自由/开源：你可以按照自己的意愿运行软件，研究源代码，修改它，分享它。没有诡计多端的终端用户许可协议。
- 开放标准：GNU/Linux 及其应用程序一般都支持开放标准，这使得它可以与其他平台无缝互操作，并帮助您避免被厂商锁定。
- 社区：GNU/Linux 被描述为一个 "世界范围的团队运动"。
- 经济性：大多数 GNU/Linux 发行版可以免费下载，大量的应用程序也是如此。此外，相对较低的硬件要求意味着你不需要经常升级你的硬件。
- 合法性：合法地获得高质量的免费软件，意味着使用未经授权的非法专利软件拷贝的诱惑更少。您也不会支持一个因滥用其市场支配地位而被多次定罪的知名垄断者。
- 透明度：大多数 GNU/Linux 发行版都是公开开发的，使用公共邮件列表、公共 IRC 频道、公共错误追踪器、公共功能追踪器等。
- 多样性：有许多来自不同供应商或社区项目的不同 GNU/Linux 发行版，用于不同目的，提供非常不同的用户体验。
- 隐私：自由软件通常会尊重你的隐私，公开的源代码提供了一些保护，防止后门之类的东西。
  尝试新的东西 - 仅仅尝试新的和不同的东西本身就可以激励许多人。
- 并且......颇具乐趣!

![hardware](<../assets/Getting Started/hardware.gif>)

## 2.2 切换到 GNU/Linux 的挑战

虽然使用 GNU/Linux 有很多优势，但要切换到一个新的、不同的、不那么主流的东西，也可能是一个巨大的挑战。

- 学习曲线：你需要学习如何使用一个新的、完全不同的操作系统和一些新的应用程序 —— 你需要重新学习你在其他操作系统中可能已经习惯于使用的很多东西。
- 缺少的应用程序和游戏：你可能会错过熟悉的应用程序，通常是 Microsoft Office、Adobe Photoshop 和大多数流行的大型主流游戏。双启动、WINE 或虚拟机为这个问题提供了部分解决方案。当然，也存在高质量的本地 GNU/Linux 替代品。
- 缺乏硬件支持：通常绝大多数硬件都被支持，但并不代表是全部，因此在购买新的硬件之前，建议提前做一些研究。通常来讲硬件越新，越小众，出现问题的风险就越大。
- 更难获得帮助：通常朋友、家人和同事无法帮助你解决 GNU/Linux 相关的问题，所以你需要在网上获得帮助，但这往往不如从朋友那里 "现场"获得帮助有效。

## 2.3 切换到 GNU/Linux 的方略建议

毕竟一下子迁移到并 GNU/Linux 并不是件容易事，下面是一些简单的建议：

- 认清现实：就像你在使用你以前的操作系统 10 年或更长时间后才掌握它一样，不要期望在一两个星期内就能掌握 GNU/Linux 。也不要指望 GNU/Linux 完美无瑕。
- 循序渐进：从在其他电脑（非主力机）上安装 GNU/Linux 开始，或者与您以前的操作系统设置双系统，或者在虚拟机中运行。从学习基础知识开始，一次一次冷静地解决任何问题。
- 寻求帮助：不要害怕在网上或其他地方寻求帮助。

### 2.3.1 可运行于 Microsoft Windows 以及 Mac OS 上的开源应用程序*

注：该列表与原文或略有出入，排版顺序以及部分列表来自于 [List of applications（简体中文）](https://wiki.archlinux.org/title/List_of_applications_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87))，尽管如此，列表中仍尽量仅包含开源软件。一下绝大部分应用程序可不借助其他方式运行于 Microsoft Windows 甚至 Mac OS 上。

#### 文本编辑
##### 文本编辑器
- **[GNU Emacs](https://www.gnu.org/software/emacs/)** — 一个可扩展的、可定制的、自由/自由的文本编辑器。其核心是Emacs Lisp的解释器，这是一种Lisp编程语言的方言，具有支持文本编辑的扩展。
- **[Kate](https://kate-editor.org/)** — Kate 的功能很多，可以让你更容易地查看和编辑你的所有文本文件。可以让你同时编辑和查看许多文件，包括标签和分割视图，并配有各种插件，包括一个嵌入式终端，让你直接从凯特启动控制台命令，强大的搜索和替换插件，以及一个预览插件，可以实时预览你的MD、HTML甚至SVG的样子。
- **[Neovim](https://neovim.io/)** — 可扩展的基于Vim的文本编辑器。
- **[Vim](https://www.vim.org/)** — Vim 是一个高度可配置的文本编辑器，可以非常有效地创建和改变任何类型的文本。
- **[Visual Studio Code](https://code.visualstudio.com/)** — Visual Studio Code是一个为构建和调试现代网络和云应用程序而重新定义和优化的代码编辑器。该软件为闭源软件，尽管其开放了源代码。
- **[VSCodium](https://vscodium.com/)** — VSCodium 是一个社区驱动的、自由授权的微软编辑器 Visual Studio Code 的二进制发行版。（由于剔除了微软的遥测，该软件无法使用或加载相当一部分 Visual Studio Code 插件）

##### 办公套件
- **[LibreOffice](https://www.libreoffice.org/discover/libreoffice/)** — LibreOffice 是一个功能强大的免费办公套件，是 OpenOffice(.org) 的继承者，在世界各地有数百万人使用。它简洁的界面和功能丰富的工具帮助你释放你的创造力和提高你的生产力。LibreOffice 包括几个应用程序，使其成为市场上功能最全面的自由和开源办公套件。Writer（文字处理），Calc（电子表格），Impress（演示文稿），Draw（矢量图和流程图），Base（数据库），和Math（公式编辑）。
- **[OnlyOffice](https://www.onlyoffice.com/)** — ONLYOFFICE 提供一个安全的在线办公套件，与MS Office格式高度兼容。将它连接到您的网络平台，用于文档编辑和协作。
- **[WPS Office](https://www.wps.com/)** — WPS Office是一款轻量级、功能丰富、兼容性强的综合办公套件。作为一个方便和专业的办公软件，WPS Office允许你在Writer、Presentation、Spreadsheet和PDF中编辑文件，提高你的工作效率。

#### 互联网
##### VPN 客户端
- **[OpenConnect](https://wiki.archlinux.org/title/OpenConnect)** — 支持 Cisco 和 Juniper VPN.
- **[Openswan](https://wiki.archlinux.org/title/Openswan)** — 基于IPsec的VPN解决方案.
- **[OpenVPN](https://wiki.archlinux.org/title/OpenVPN)** — 用来连接到 OpenVPN VPNs.
- **[WireGuard](https://wiki.archlinux.org/title/WireGuard)** — 下一代安全网络隧道.

##### 代理服务器
- **Project V** — Project V 是一系列工具用来通过因特网帮助您构建你自己的私有网络.
- **[Shadowsocks](https://wiki.archlinux.org/title/Shadowsocks)** — 安全的 socks5 代理, 旨在保护你的因特网流量.
- **[Trojan](https://wiki.archlinux.org/title/Trojan)** — 一种无法辨别的机制，能让你绕过GFW.

##### 匿名网络
- **[GNUnet](https://wiki.archlinux.org/title/GNUnet)** — 安全的对等网络框架.
- **[I2P](https://wiki.archlinux.org/title/I2P)** — 分布式匿名网络.
- **[Tor](https://wiki.archlinux.org/title/Tor)** — 匿名覆盖网络.

##### 网络浏览器
见 [Wikipedia:Comparison of web browsers](https://en.wikipedia.org/wiki/Comparison_of_web_browsers).
- 基于 Gecko：可见 [Wikipedia:Gecko (software)](https://en.wikipedia.org/wiki/Gecko_(software)). 
	- **[Firefox](https://wiki.archlinux.org/title/Firefox)** — 来自Mozilla的支持快速渲染的可扩展浏览器.
	- **[Tor](https://wiki.archlinux.org/title/Tor) 匿名网络浏览器** — 安全便捷地下载、验证、安装和启动Tor Browser。Firefox ESR的一个分支。

- 基于Blink：也可查阅[Wikipedia:Blink (layout engine)](https://en.wikipedia.org/wiki/Blink_(layout_engine)).
	- **[Chromium](https://wiki.archlinux.org/title/Chromium)** — Google开发的网页浏览器, Google Chrome之后的开源项目.
	- **[Vivaldi](https://wiki.archlinux.org/title/Vivaldi)** — 一个高级有所有权的浏览器，以强大的用户为中心.

- 基于qt5-web引擎的浏览器
	- **[Eric](https://en.wikipedia.org/wiki/Eric_Python_IDE)** — 基于QTWEB引擎的HTML浏览器,是eric6开发工具集的一部分, 能用 `eric6_browser`命令启动.
	- **[Falkon](https://en.wikipedia.org/wiki/Falkon)** — 基于QtWeb引擎，用Qt框架写的浏览器.
	- **[Konqueror](https://en.wikipedia.org/wiki/Konqueror)** — 基于Qt工具集和Qtweb引擎(或者KHTML布局引擎)的浏览器,是[kde-network](https://archlinux.org/groups/x86_64/kde-network/)的一部分.

#### 文件分享
##### 下载管理器
也可查阅 [Wikipedia:Comparison of download managers](https://en.wikipedia.org/wiki/Comparison_of_download_managers).

##### 终端程序
- **[aria2](https://wiki.archlinux.org/title/Aria2)** — 轻量的下载工具，支持HTTP、FTP、SFTP、BitTorrent和MetaLink. 它是作为守护进程运行的，通过内置的JSON-RPC 或 XML-RPC 界面控制.
- **mps-youtube** — 基于终端的、带有播放列表管理的YouTube点唱机。 通过mplayer/mpv播放音频/视频.
- **Plowshare** — 一系列命令行工具，用来管理文件分享网站(aka Hosters).
- **[youtube-dl](https://wiki.archlinux.org/title/Youtube-dl)** — 从 YouTube 和其它网站下载视频.

##### 图形界面
- **ClipGrab** — YouTube, Vimeo 和许多其它在线视频站点的下载器和转换器.
- **Gydl** — 对已存在的youtube-dl程序的GUI 封装来从类似YouTube的网站下载内容.
- **[JDownloader](https://wiki.archlinux.org/title/JDownloader)** — 基于Java的针对一键托管网站的下载器.
- **Xtreme Download Manager** — 提升下载速度至多500%的强力工具. 支持 HTTP and FTP. 视频采集器能以普通方式运行并且不限于特定网站.

##### 云存储服务器
- **[Nextcloud](https://wiki.archlinux.org/title/Nextcloud)** — 一款将文件集中存储在由你掌控的硬件上的云服务器.
- **[Seafile](https://wiki.archlinux.org/title/Seafile)** — 一种在线文件存储和协作的工具，具有对文件同步、隐私保护和团队协作的高级支持.

##### 云同步客户端
- **aws-cli** — 针对亚马逊Web服务(Amazon Web Service)的CLI, 包括高效的从亚马逊S3上传或下载的文件传输.
- **Backblaze B2** — 开源的命令行客户端.
- **CloudCross** — 将本地文件和文件夹同步到许多云服务器提供商. Mail.ru Cloud, Yandex Disk, Google Drive, OneDrive 和 Dropbox 的服务都是支持的.
- **[Mail.ru](https://en.wikipedia.org/wiki/Mail.Ru) Cloud** — 针对Mail.ru云存储服务的专有.
- **[Mega](https://en.wikipedia.org/wiki/Mega_(service)) Sync Client** — 同步 Mega的文件的桌面客户端.
- **[Nextcloud](https://wiki.archlinux.org/title/Nextcloud) Client** — 针对Nextcloud的桌面客户端.
- **坚果云** — 坚果云的客户端.
- **OneDrive** — 针对 [OneDrive](https://onedrive.live.com/about/)的服务.
- **[ownCloud](https://en.wikipedia.org/wiki/ownCloud) Desktop Client** — 针对 ownCloud的桌面同步客户端.
- **[Seafile](https://wiki.archlinux.org/title/Seafile) Client** — 针对Seafile的GUI.
- **[Yandex Disk](https://wiki.archlinux.org/title/Yandex_Disk)** — 针对Yandex Disk的专有CLI.

##### FTP
###### FTP客户端
也可查阅 [Wikipedia:Comparison of FTP client software](https://en.wikipedia.org/wiki/Comparison_of_FTP_client_software). 注：FTP 协议不再受到主流浏览器以及文件管理器支持，请使用 FTP 客户端程序。
- **[FileZilla](https://en.wikipedia.org/wiki/FileZilla)** — 快速和可靠的FTP, FTPS 和 SFTP 客户端.
- **ncftp** — 实现FTP的一系列免费应用程序.
一些文件管理器像 [Dolphin](https://wiki.archlinux.org/title/Dolphin), [GNOME Files](https://wiki.archlinux.org/title/GNOME_Files) 也提供FTP功能.

##### BitTorrent客户端
一些[download managers](https://wiki.archlinux.org/title/List_of_applications_(简体中文)#下载管理器)也能连接到Bittorrent网络: [Aria2](https://wiki.archlinux.org/title/Aria2), [LFTP](https://en.wikipedia.org/wiki/Lftp), [MLDonkey](https://en.wikipedia.org/wiki/MLDonkey).
也可查阅 [Wikipedia:Comparison of BitTorrent clients](https://en.wikipedia.org/wiki/Comparison_of_BitTorrent_clients).

- **[Transmission](https://wiki.archlinux.org/title/Transmission) CLI** — 简单易用的BitTorrent client带有一个守护进程版本和多前端. 这个包包括了后端、守护进程、命令行界面和一个web UI界面.
- **[Deluge](https://wiki.archlinux.org/title/Deluge)** — 用户友好的BitTorrent客户端，用PyGTK写成，能以守护进程运行.
- **[qBittorrent](https://en.wikipedia.org/wiki/qBittorrent)** — 开源的(GPLv2许可证) BitTorrent 客户端，非常像 µtorrent.
- **[Vuze](https://en.wikipedia.org/wiki/Vuze)** — 用Java写的功能丰富的Bittorrent客户端(之前是 Azureus).

注：为了维护 BitTorrent 下载环境，请勿使用迅雷以及同系列软件。

##### 其他端到端（P2P）网络
- **[MLDonkey](https://en.wikipedia.org/wiki/MLDonkey)** — 多协议的P2P客户端，支持HTTP, FTP, BitTorrent, Direct Connect, eDonkey 和 FastTrack.
- **Valknut** — 直连客户端(像 DC++)带有断电续传功能.

#### 通信
##### 邮件客户端
也可查阅[Wikipedia:Comparison of email clients](https://en.wikipedia.org/wiki/Comparison_of_email_clients)
- **email-securely-app** — 非官方的桌面程序提供许多加密邮件提供商的服务 (比如 ProtonMail, Tutanota). 基于 [Electron](https://electronjs.org/) 平台.
- **Inboxer** — 非官方，免费，开源的Google Inbox桌面程序. 基于 [Electron](https://electronjs.org/) 平台.
- **[Kmail](https://en.wikipedia.org/wiki/Kmail)** — 成熟且功能丰富的邮件客户端. 是 [kdepim](https://archlinux.org/groups/x86_64/kdepim/)[[损坏的链接](https://wiki.archlinux.org/title/Help:Procedures#Fix_broken_package_links)：package not found]的一部分.
- **openWMail** — 针对Gmail & Google Inbox的令人想念的邮件客户端. 基于 [Electron](https://electronjs.org/) 平台.
- **Protonmail Desktop** — 非官方的程序，模拟ProtonMail邮件服务的本地客户端. 基于 [Electron](https://electronjs.org/) 平台.
- **[SeaMonkey Mail & Newsgroups](https://en.wikipedia.org/wiki/SeaMonkey#Mail)** — 包括SeaMonkey套件的邮件客户端.
- **[Thunderbird](https://wiki.archlinux.org/title/Thunderbird)** — 来自Mozilla的由GTK+写成的功能丰富的邮件客户端.

##### 即时通信客户端
也可查阅 [Wikipedia:Comparison of instant messaging clients](https://en.wikipedia.org/wiki/Comparison_of_instant_messaging_clients) 和 [Wikipedia:Comparison of VoIP software](https://en.wikipedia.org/wiki/Comparison_of_VoIP_software).

这个部分在 [instant messaging](https://en.wikipedia.org/wiki/Instant_messaging)的支持下列出了所有客户端软件.

###### 多协议客户端
- **[Empathy](https://en.wikipedia.org/wiki/Empathy_(software))** — GNOME的即时消息客户端，使用 [Telepathy](https://en.wikipedia.org/wiki/Telepathy_(software))框架，支持音频/视频.
- **[Jitsi](https://en.wikipedia.org/wiki/Jitsi)** — 音频/视频VoIP手机和即时通信客户端，用Java写成，支持SIP, XMPP, ICQ, IRC协议和许多其它有用的特性.
- **[Pidgin](https://wiki.archlinux.org/title/Pidgin)** — 多协议即时通信客户端并有音频支持，使用的libpurple并支持所以它的协议 (Bonjour, Gadu-Gadu, Groupwise, ICQ, IRC, SIMPLE, XMPP, Zephyr).
- **[Thunderbird](https://wiki.archlinux.org/title/Thunderbird)** — 功能丰富的email客户端，支持用IRC，XMPP和Twitter的即时通信.
- **[Yate Client](https://en.wikipedia.org/wiki/Yate_(telephony_engine))** — 即时通信客户端和软件电话，支持XMPP, SIP and H.323.

###### IRC客户端
也可查阅 [Wikipedia:Comparison of Internet Relay Chat clients](https://en.wikipedia.org/wiki/Comparison_of_Internet_Relay_Chat_clients).

- 命令行
	- **[WeeChat](https://wiki.archlinux.org/title/WeeChat)** — 模块化，轻量级，基于ncurses库的IRC客户端。

- 图形界面
	- **HexChat** — 适用于Linux和Windows的XChat的分支。
	- **[Quassel](https://wiki.archlinux.org/title/Quassel)** — 现代且跨平台的分布式IRC客户端。

###### XMPP客户端
请参考 [Wikipedia:XMPP](https://en.wikipedia.org/wiki/XMPP) 和 [Wikipedia:Comparison of instant messaging clients#XMPP-related features](https://en.wikipedia.org/wiki/Comparison_of_instant_messaging_clients#XMPP-related_features).

- **Converse.js** — 基于web的XMPP会话客户端，使用JavaScript开发。
- **Nextcloud JavaScript XMPP Client** — 使用XMPP的Nextcloud的聊天应用程序，有端到端加密，视频电话，文件传输和小组交流的功能。
- **[Psi](https://en.wikipedia.org/wiki/Psi_(instant_messaging_client))** — 基于QT开发的XMPP客户端。
- **[Spark](https://en.wikipedia.org/wiki/Spark_(XMPP_client))** — 针对企业和组织优化的跨平台实时XMPP协作客户端。
- **Swift** — 使用C++编写的基于QT和Swiften的XMPP客户端。
- **[Tkabber](https://en.wikipedia.org/wiki/Tkabber)** — 由ejabberd XMPP服务的作者开发的易于快速开发、功能丰富的XMPP客户端。
- **Vacuum IM** — 全功能的跨平台XMPP客户端。

###### SIP客户端
另参见[Wikipedia:List of SIP software#Clients](https://en.wikipedia.org/wiki/List_of_SIP_software#Clients).

- **[Blink](https://en.wikipedia.org/wiki/Blink_(SIP_client))** — 最先进的，易用的SIP客户端。
- **[Linphone](https://en.wikipedia.org/wiki/Linphone)** — 为通过音频、视频、文字即时消息和互联网上的人们自由交谈而开发的VoIP电话应用程序(SIP 客户端)。
- **[Twinkle](https://en.wikipedia.org/wiki/Twinkle_(software))** — 用QT开发的软件电话，使用SIP协议进行Voip和IM通话。

##### Matrix客户端
另请参见 [Matrix](https://wiki.archlinux.org/title/Matrix).

- **Quaternion** — 支持Matrix协议的基于QT5开发的IM客户端。
- **Element** — 漂亮的Matrix客户端，侧重于性能和可用性。Web版和桌面版基于[Electron](https://electronjs.org/)平台开发。
- **Tensor** — 基于QT5/QML的Matrix客户端。

#### 多媒体

##### 解码器

另外参阅: [Codecs](https://wiki.archlinux.org/title/Codecs).

##### 图形和图像处理
- 位图编辑器
	- **[GIMP](https://en.wikipedia.org/wiki/GIMP)** — GIMP 是 [GNU](https://wiki.archlinux.org/title/GNU) Image Manipulation Program（GNU图像处理程序）的缩写。成立于20世纪90年代中期的GIMP是一个与 Adobe Photoshop 相似的图像编辑套件。
	- **Krita (瑞典语言版本中称为crayon)** — 基于KDE平台和Koffice库创建的数字绘画设计软件
	- **[ImageMagick](https://en.wikipedia.org/wiki/ImageMagick)** — ImageMagick 是一个命令行图像处理程序。 它因为其支持超过100多种格式的精确格式转换而知名。它的API使得它非常易于融入脚本之中，而且它也被用作很多软件的后台处理器——比如创建MediaWiki的图片缩略图。
	- **[GraphicsMagick](https://en.wikipedia.org/wiki/GraphicsMagick)** — GraphicsMagick 于2002年基于ImageMagick的设计创建，继承了它的API和命令行稳定性。 而且它还支持多核CPU以增强性能，因为如此它被许多大型机构网站（如Flickr、etsy等）使用。
	- **[digiKam](https://en.wikipedia.org/wiki/digiKam)** — digiKam是一个基于KDE的图像/照片管理器。借助插件架构，它内置了大量的图像处理功能。digiKam声称自己比其他很多的图像处理工具拥有更多的图像处理功能，包括RAW格式图像的导入和处理。

- 矢量图形-图表
	另请参见：[Wikipedia:Comparison of vector graphics editors](https://en.wikipedia.org/wiki/Comparison_of_vector_graphics_editors)。
	- **[Asymptote](https://en.wikipedia.org/wiki/Asymptote_(vector_graphics_language))** — 一个描述性的矢量图形语言(比如PGF / TikZ和Metapost)，具有类c语法和LaTex支持。
	- **Dia** — 一个基于GTK+的创意软件。
	- **Gravit** — 专业的矢量图形设计工具。
	- **[Inkscape](https://en.wikipedia.org/wiki/Inkscape)** — 一个开源的矢量图编辑器，功能类似于Illustrator、CorelDraw以及Xara X。它使用W3C标准可放大矢量图格式（SVG）。Inkscape支持众多的高级SVG功能（如标记、克隆、Alpha通道混合等）。并且具有一套认真设计的基于工作流程的界面。它可以很方便地编辑节点，执行复杂的路径操作，描绘位图等等等等。其开发者以其社区维护的开发方法致力于维护一个正在发展中的用户与开发者社区。
	- **Mockingbot** — 中文名：墨刀，一个可协作的原型图设计工具。
	- **qasm2circ** — latex的量子电路生成工具
	- **[yEd](https://en.wikipedia.org/wiki/yEd)** — 通用绘图程序流程图、网络图、UML图,BPMN图、思维导图、组织图、实体关系图。

##### 矢量图处理 - CAD
另外参阅 [Wikipedia:List of computer-aided design editors](https://en.wikipedia.org/wiki/List_of_computer-aided_design_editors).
- **DraftSight** — 专业级免费CAD软件。DraftSight让专业CAD用户、学生和教育工作者能够创建、编辑和查看DWG文件。

###### 三维建模与渲染
另外参阅 [Wikipedia:Comparison of 3D computer graphics software](https://en.wikipedia.org/wiki/Comparison_of_3D_computer_graphics_software).
- **Blender** — 一个全能的三维在图形创意工具。功能包括三维建模、材质设计、三维动画、后期合成等等功能。同时它也有大量的附加不定和工具扩展它的功能。另外可见:
	- [Blender homepage](https://www.blender.org/)
	- [Blender Wiki](https://wiki.blender.org/index.php/Main_Page)
	- [Blender walkthrough on wikibooks](https://en.wikibooks.org/wiki/Blender_3D)

#### 音频
##### 音乐播放器守护进程和客户端 (Client)
- **[Music Player Daemon](https://wiki.archlinux.org/title/Music_Player_Daemon)** — 轻量、可伸缩音乐播放器，C/S结构，MPD 作为一个守护程序运行于后台， 管理播放列表和音乐数据库
- [MPD客户端程序清单](https://wiki.archlinux.org/title/Music_Player_Daemon#Clients)
- **[Clementine](https://en.wikipedia.org/wiki/Clementine_(software))** — Amarok 1.4 的复刻，目前已经切换到 Qt5。
- **[VLC](https://en.wikipedia.org/wiki/VLC_media_player)** — 高度便携的多媒体播放器和多媒体框架，能够读取大多数音频和视频格式，以及DVD、音频CD、VCD和各种流媒体协议。

##### 音频标签编辑器
- **[EasyTag](https://en.wikipedia.org/wiki/EasyTag)** — 用于查看、编辑和编写你的MP3文件的ID3标签的工具。
- **Kid3** — MP3、Ogg/Vorbis、FLAC、MPC、MP4/AAC、MP2、Speex、TrueAudio、WavPack、WMA、WAV和AIFF文件标签编辑工具。
- **MP3Info** — MP3技术信息查看器和ID3 1.x标记编辑器。

##### 声音编辑
- **[Audacity](https://en.wikipedia.org/wiki/Audacity_(audio_editor))** — 可以让你操作数字音频波形的程序。
- **easytag** — 查看和编辑多种音频格式的 tag

#### 视频
##### 视频播放器
另外参见 [Wikipedia:Comparison of video player software](https://en.wikipedia.org/wiki/Comparison_of_video_player_software).

- **[MPlayer](https://wiki.archlinux.org/title/MPlayer)** — 视频播放器，支持完整而多样的视频和音频格式。
- **[mpv](https://wiki.archlinux.org/title/Mpv)** — 基于 MPlayer 的现代视频播放程序。
- **bomi** — 强大易用的视频播放程序，基于 mpv 后端。
- **[VLC media player](https://en.wikipedia.org/wiki/VLC_media_player)** — 中量级视频播放器，支持多种音频和视频格式。

##### 视频编辑器
参见 [Wikipedia:Comparison of video editing software](https://en.wikipedia.org/wiki/Comparison_of_video_editing_software).

- **[Davinci Resolve]** — 一款专业级别的视频调色工具，同时带有业内级别的视频音频剪辑支持。
- **[ffmpeg](https://ffmpeg.org/)** — 一个完整的、跨平台的音频和视频录制、转换和流媒体解决方案。市面上几乎全部或大部分中小型视频编解码软件、播放器、编辑工具等均基于 ffmepg，堪称音频、视频、图像处理的全能手。
- **[HandBrake](https://en.wikipedia.org/wiki/HandBrake)** — 简单而强大的视频转码器，是批量转码 mkv/x264 的理想选择。
- **[Kdenlive](https://en.wikipedia.org/wiki/Kdenlive)** — 非线性，专业级别的视频编辑工具。
- **[Lightworks](https://en.wikipedia.org/wiki/Lightworks)** — 非线性，专业级别，支持广泛编码。
- **[LiVES](https://en.wikipedia.org/wiki/LiVES)** — VJ (live performance) 平台。
- **[Open Shot](https://en.wikipedia.org/wiki/OpenShot_Video_Editor)** — 非线性，基于 MLT 框架。


##### 视频推流以及屏幕录制

- **[OBS Studio](https://obsproject.com/)** — 使用最为广泛的屏幕录制以及视频推流软件，具有非常强大的扩展功能以及自定义场景。

#### 集成式开发环境（IDE）
另外参见 [Wikipedia:Comparison of integrated development environments](https://en.wikipedia.org/wiki/Comparison_of_integrated_development_environments).

- **[Android Studio](https://developer.android.com/studio)** — 谷歌推荐使用的安卓集成开发环境，基于 Intelij idea。
- **[Anjuta](https://wiki.archlinux.org/title/Anjuta)** —  多功能的集成开发环境，具有项目管理、应用向导、交互式调试器、源码编辑器、版本控制支持和许多其他工具。
- **[Aptana Studio](https://en.wikipedia.org/wiki/Aptana#Aptana_Studio)** — 基于Eclipse的IDE，但面向Web开发，支持HTML、CSS、Javascript、Ruby on Rails、PHP、Adobe AIR和其他。
- **[BlueGriffon](https://en.wikipedia.org/wiki/BlueGriffon)** — 一个所见即所得的万维网内容编辑器。它由火狐浏览器的渲染引擎Gecko支持，可以按照网络标准编辑网页。它可以在Mac OS X、Windows和Linux上运行。
- **[Brackets](https://en.wikipedia.org/wiki/Brackets_(text_editor))** — 一个用HTML、CSS和Javascript编写的免费开源编辑器，主要关注于网络开发。它是由Adobe Systems创建的，在MIT许可下授权，目前在GitHub上维护。
- **[Code::Blocks](https://en.wikipedia.org/wiki/Code::Blocks)** — 开源和跨平台的C/C++ IDE。
- **[Eclipse](https://wiki.archlinux.org/title/Eclipse)** — 开源社区项目，旨在提供一个通用的开发平台。
- **[IntelliJ IDEA](https://en.wikipedia.org/wiki/IntelliJ_IDEA)** — 适用于Java、Groovy和其他编程语言的IDE，具有高级重构功能。
- **[Lazarus](https://en.wikipedia.org/wiki/Lazarus_(IDE))** — 适用于Object Pascal的跨平台集成开发环境。
- **LiteIDE** — 一个简单的、开源的、跨平台的Go集成开发环境。
- **[MonoDevelop](https://en.wikipedia.org/wiki/MonoDevelop)** — 针对Mono和.NET框架的跨平台集成开发环境。
- **[NetBeans](https://wiki.archlinux.org/title/Netbeans)** — 使用Java、JavaScript、PHP、Python、Ruby、Groovy、C、C++、Scala、Clojure和其他语言开发的集成开发环境。
- **[Ninja-IDE](https://en.wikipedia.org/wiki/Ninja-IDE)** —  来自递归的缩写："Ninja-IDE不只是另一个IDE"，是一个跨平台的集成开发环境，可在 Linux/X11、Mac OS X和Windows操作系统上运行。例如，用于Python开发。
- **[Phpstorm](https://en.wikipedia.org/wiki/PhpStorm)** — JetBrains PhpStorm是一个建立在JetBrains的IntelliJ IDEA平台上的商业化、跨平台的PHP集成开发环境，为PHP、HTML和JavaScript提供一个编辑器，对PHP和JavaScript代码进行即时的代码分析、错误预防和自动重构。
- **[PyCharm](https://en.wikipedia.org/wiki/PyCharm)** — 用于Python编程的IDE，支持代码分析、调试、单元测试、版本控制和使用Django的Web开发。
- **[Qt Creator](https://en.wikipedia.org/wiki/Qt_Creator)** — 轻量级、跨平台的C++集成开发环境，专注于Qt。

