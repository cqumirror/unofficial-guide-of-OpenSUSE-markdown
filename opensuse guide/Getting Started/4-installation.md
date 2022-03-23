# 4. 安装 openSUSE

本节仅仅是安装过程的简略描述，详细信息请查看官方文档。

## 4.1 安装之前

在安装之前，您需要注意以下信息：

### 4.1.1 系统最低要求

- 中央处理器：Arm64 或 x86_64 的处理器
- 内存：4GB 物理内存用于桌面或 1GB 用于服务器（桌面推荐内存大小为至少 8GB，服务器为至少 2GB）
- 硬盘空间：5GB（标准桌面安装推荐 20GB 及以上）
- 声卡及显卡：大多数现代设备均支持。

### 4.1.2a 烧录 ISO 镜像到 DVD

当把下载的ISO文件刻录到 DVD 上时，需要使用 CD/DVD 刻录软件将它们刻录成 ISO/启动镜像，否则将无法从安装介质启动。

### 4.1.2b 创建可启动的 USB 设备

> ISO 也可以烧录在 U盘上，参见 Microsoft Windows、Mac OS、openSUSE 和其他 GNU/Linux 的说明：https://en.opensuse.org/Create_installation_USB_stick 。

注：针对从 Microsoft Windows 进行镜像刻录，推荐使用 [Rufus](http://rufus.ie/zh/) 进行刻录，刻录时请根据需要调整分区类型、引导类型和目标系统类型，为保证启动过程正常进行请勿更改设备卷标。

### 4.1.3 BIOS 设置

如果您的计算机并没有从 DVD 或 USB 设备启动，请检查 BIOS 设定或进入 BOOT MENU 并选择从安装介质启动，您无需关闭安全启动。

### 4.1.4 双系统（openSUSE 和 Microsoft  Windows 处于同一台计算机上）

如果 Microsoft Windows 是先被安装的，那么将 openSUSE 和 Microsoft Windows 安装在同一台电脑上通常是相当简单的。在安装过程中，openSUSE（通常是由 `os-probe`进行控制） 会检测到 Microsoft Windows 启动项，并且引导程序 `Grub2` 会在每次启动时显示一个菜单，让你选择从哪个系统启动。

如果 openSUSE 需要安装在一个单独的分区/磁盘上。建议事先用你熟悉的分区工具释放空间。但是你也可以让 openSUSE 安装程序调整你的 Microsoft Windows 分区的大小，强烈建议在这样做之前对Microsoft Windows 分区进行碎片整理。

### 4.1.5 连接网线并打开外围设备

如果你在开始安装之前连接好你的网线并打开你的打印机和其他外围设备，它们很有可能被自动检测并被配置。

## 4.2 安装流程

### 开始安装

### 语言、键盘、权力许可

### 用户环境

### 分区

### 时钟和时区

### 创建新用户

### 检查安装设置

### 开始安装

