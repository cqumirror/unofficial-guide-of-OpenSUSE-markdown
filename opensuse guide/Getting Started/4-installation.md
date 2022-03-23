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

准备就绪后，插入 DVD 或 U盘并重新启动计算机。

### 开始安装

您将会看到一个启动菜单，在这里您可以选择直接安装或升级系统，也可以进入救援系统或调整其他选项，然后开始安装。

![image](<../assets/Getting Started/grub2.png>)

### 语言、键盘、许可协议

许可协议用于告知您您的权利，进行下一步默认您遵守该许可协议。请注意：

- **该许可受到美国出口管制条例（EAR）限制**
- 点击下一步默认您接受该许可
- 被限制使用的实体或个人不被允许拥有许可约定的权利

有关 openSUSE 许可文本，参见：https://en.opensuse.org/openSUSE:License ，

有关 SUSE 许可文本，参见：https://www.suse.com/company/legal/eccn/ 。

![image-20220323222137127](<../assets/Getting Started/language-keyboard-license.png>)

### 系统角色

GNU/Linux 存在各种不同的图形用户界面（桌面环境）。相当一部分的 openSUSE 用户更喜欢使用 KDE Plasma ，这也将是本指南的重点。但您也可以选择 GNOME 桌面或基于文本的服务器安装等选项。

![image-20220323222342957](<../assets/Getting Started/user-interface.png>)

### 分区建议

默认情况下，openSUSE 会建议为系统文件创建多个 BTRFS 子卷，一般为 `/boot/efi` 用于安放启动文件，`/` 用于安放系统文件，`/home` 用于安放用户文件以及 `swap` 作为物理内存的补充部分，类似于 Microsoft Windows 的页面文件。

请仔细检查分区建议是否是您想要的，如果您正在进行双系统安装，请特别注意这点，以确保一切都符合要求。

请注意，GNU/Linux 使用以下方案标记磁盘/分区:

- 对于 SATA 设备：*sda1* 是第一块磁盘上的第一个分区，*sdb3* 是第二块磁盘上的第三个分区，依此类推。
- 对于 NVME m.2 设备：nvme0p1 是第一块硬盘的第一个分区，nvme1p3 是第二块磁盘上的第三个分区，依此类推。

将被格式化的分区以红色文本书写。

![image-20220323222455310](<../assets/Getting Started/partition.png>)

### 时钟和时区

在这里设置时区。

如果您只有 GNU/Linux，建议将硬件时钟设置为 UTC，如果您使用 Microsoft Windows 进行多系统引导，请将其设置为本地时间。

![image-20220323222622958](<../assets/Getting Started/time-and-timezone.png>)

### 创建本地用户

现在是时候创建您的用户了。请注意，默认情况下，root 用户（管理员）密码与普通用户的密码相同。

如果您想增加单独的 root 密码的安全性，请考虑取消选中该复选框。您可能还需要考虑禁用自动登录，以防止人们轻松访问您的系统和数据。

![image-20220323222740606](<../assets/Getting Started/create-user.png>)

### 检查安装设置

仔细检查一切是否符合要求，安装过程没有回头路！您也可以进入各个选项进行包括软件包、防火墙、服务等的软件包及设置调整。

![image-20220323222904438](<../assets/Getting Started/check-installation-information.png>)

### 开始安装

现在执行实际安装。完成后，系统将重新启动并准备好使用。

祝您在 openSUSE 玩得愉快！

![image-20220323223039638](<../assets/Getting Started/start-installation.png>)
