# VoodooHDA 2.9.0-V10

### Credit: Developer Slice, Zenith432 ➠ Source: https://sourceforge.net/projects/voodoohda/

### Credit: Clover Team

### Credit: Testeurs: emax31, arcade33, MilesTEG1, PhilouFr, emilio36, fredsame, aminov41, sevan, JMB. 

### 封装: chris1111

这是一个使用PackageMaker创建的Mac OS X包
VoodooHDA是符合英特尔高保真音频（HDA）规范的设备的开源音频驱动程序。 它旨在作为Mac OS X上的AppleHDA的仅英特尔替代品，支持广泛的音频控制器和编解码器。
 
工作于 10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6


## 说明

## 方法一:通过Clover UEFI/ESP驱动
请点击下载:[VoodooHDA 2.9.0 Clover-V11.dmg](https://github.com/daliansky/VoodooHDA-2.9.0-Clover-V10/blob/master/VoodooHDA 2.9.0 Clover-V11.dmg)
这个安装程序会自动安装到`/ESP/EFI/CLOVER/kexts/`以及下面的目录里10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6
安装目录取决于你安装的macOS系统决定.
这个驱动将通过Clover加载而不需要安装到`/System/Library/Extensions/`,同时它也不会删除系统自带的`AppleHDA.kext`,您甚至无需备份`/Others/AppleALC.kext`

## 方法二:Clover传统模式

你也可以安装VoodooHDA.kext内核扩展程序到/EFI/Clover/kexts/10.12/10.11/10.10/10.9/10.8/10.7/10.6 
这个驱动将通过Clover加载.

## 方法三: 经典方法

您也可以选择10.6到10.12的Clasic方法，这将在系统库扩展上安装VoodooHDA.kext + AppleHDADisabler.kext

这将在应用程序上安装VoodooHdaSettingsLoader.app，在Library / PreferencePanes上安装VoodooHDA.prefPane 
在这两种方法中，在usr / local / bin / getdump上安装getdump。

注意：对于所有OS X系统，VoodooHDA.prefPane安装在Library / PreferancesPanes中


[![Modular Image Creation](https://i37.servimg.com/u/f37/18/50/18/69/voodoo11.png)]()


