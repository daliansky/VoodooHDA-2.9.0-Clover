# VoodooHDA 2.9.0-V12

## (Support macOS Mojave 10.14)

### This is a Mac OS X Package

### Credit:

- Developer Slice, Zenith432, autumnrain ➠ Source: https://sourceforge.net/projects/voodoohda/
- MountEFI Script 10.13/10.14 Clover Team
- Testeurs: emax31, arcade33, MilesTEG1, PhilouFr, emilio36, fredsame, aminov41, sevan, JMB.
- Packager chris1111

这是一个使用PackageMaker创建的Mac OS X包
VoodooHDA是符合英特尔高保真音频（HDA）规范的设备的开源音频驱动程序。 它旨在作为Mac OS X上的AppleHDA的仅英特尔替代品，支持广泛的音频控制器和编解码器。

工作于 10.14/10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6

## 说明

你需要有现成的Clover，它只会安装VoodooHDA和其他必需的组件来正常运行。

## 方法一:通过Clover UEFI/ESP驱动
请点击下载:[VoodooHDA 2.9.0 Clover-V12.dmg](https://raw.githubusercontent.com/daliansky/VoodooHDA-2.9.0-Clover/master/VoodooHDA_2.9.0_Clover-V12.dmg)
这个安装程序会自动安装到`/ESP/EFI/CLOVER/kexts/`以及下面的目录里10.14/10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6
安装目录取决于你安装的macOS系统决定.
**这个驱动将通过Clover加载而不需要安装到`/System/Library/Extensions/`,同时它也不会删除系统自带的`AppleHDA.kext`,您甚至无需备份`/Others/AppleALC.kext**`

## 方法二:Clover传统模式

你也可以安装VoodooHDA.kext内核扩展程序到/EFI/Clover/kexts/10.14/10.1310.12/10.11/10.10/10.9/10.8/10.7/10.6 
这个驱动将通过Clover加载.

## 方法三: 经典方法

您也可以选择10.6到10.12的Clasic方法，这将在系统库扩展上安装VoodooHDA.kext + AppleHDADisabler.kext

这将在应用程序上安装VoodooHdaSettingsLoader.app，在Library / PreferencePanes上安装VoodooHDA.prefPane 
在这两种方法中，在`usr/local/bin/getdump`上安装getdump。

注意：对于所有OS X系统，VoodooHDA.prefPane安装在Library / PreferancesPanes中

### 用法: 下载最新版本的发行版 [Download ➤ VoodooHDA 2.9.0-V12 ](https://github.com/chris1111/VoodooHDA-2.9.0-Clover-V12/releases/tag/V12) 勾选你希望的选项, 安装并重启.

### 对于要应用的更改，重新启动非常重要。

### 常见问题 [Common issue ➤ VoodooHDA ](http://www.insanelymac.com/forum/topic/267905-voodoohda-common-problems/)

### 任何问题请在这里回帖 [Main topic ➤ VoodooHDA ](http://www.insanelymac.com/forum/topic/314406-voodoohda-290/)

### 按照视频中的每个步骤操作

                       ⟱

[![Modular Image Creation](https://i95.servimg.com/u/f95/18/50/18/69/video_10.png)](https://youtu.be/RYHI2LGBqMc)