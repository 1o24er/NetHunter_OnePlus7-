# NetHunter_OnePlus7+

# 准备
NetHunter||OnePlus7Plus

1.[一加7Pro手机](https://www.oneplus.com/pt/7pro)

2.[platform-tools: adb和fastboot工具](https://developer.android.google.cn/studio/releases/platform-tools)

3.[氧OS线刷包 OxygenOS 10.3.0](https://otafsg1.h2os.com/patch/amazone2/GLO/OnePlus7ProOxygen/OnePlus7ProOxygen_21.P.24_GLO_024_1912142025/OnePlus7ProOxygen_21.P.24_OTA_024_all_1912142025_acd8caa52e0b.zip)

[其他下载地址:]()

[daxiaamu](https://yun.daxiaamu.com/)

[androidsage](https://www.androidsage.com/2020/02/15/download-oxygen-os-10-3-1-ota-update-oneplus-7-7-pro-7t-7t-pro/)

[thecustomdroid](https://www.thecustomdroid.com/download-oneplus-7-pro-oxygenos-android-10-update/#oxygenos-1030-non-eu-only)

4.[Twrp:非官方版本](https://forum.xda-developers.com/t/recovery-3-4-0-10-unified-official-unofficial-twrp-for-oneplus-7-7-pro-5g-stable.3932943/)

[img后缀的临时刷机包](https://sourceforge.net/projects/mauronofrio-twrp/files/Guacamole-Guacamoleb-Guacamolec/twrp-3.4.0-10-guacamole-unified-Q-mauronofrio.img/download)

[zip后缀的永久刷机包](https://sourceforge.net/projects/mauronofrio-twrp/files/Guacamole-Guacamoleb-Guacamolec/twrp-3.4.0-10-guacamole-unified-installer-mauronofrio.zip/download)

5.[Magisk: Magisk-v21.4.zip + Magisk-v23.0.apk](https://github.com/topjohnwu/Magisk/releases)

6.[Disable_Dm-Verity_ForceEncrypt](https://wwx.lanzoui.com/i8t6Dql0igb)

7.[Kali Nethunter刷机包](https://www.kali.org/get-kali/#kali-mobile)

# 步骤

### 第一步：刷机（OxygenOS 10.3.0）
#### 禁用驱动程序签名
运行-“gpedit.msc”-打开本地组策略编辑器-用户配置-管理模板-系统-驱动程序安装-代码签名-双击（已启用-警告）
#### 安装底层驱动
手机：左侧音量+按住不动，插入数据线
电脑：此电脑-右键管理-计算机管理-设备管理-等待PC识别到QHSUSB BULCK设备
      在QHSUSB BULCK上点右键-更新驱动程序
### 第二步：解锁

### 第三步：刷Twrp

### 第四步：格式化Data分区

### 第五步：刷解密包（Disable_Dm-Verity_ForceEncrypt）

### 第六步：刷Magisk（Magisk-v21.4.zip）

### 第七步：重启设置后，刷新Magisk（Magisk-v23.0.apk）

### 第八步：进Twrp刷入kali nethunter包重启

### 第九步：NetHunter->允许权限->Kali Chroot Manager-> START KALI CHROOT

# 参考
https://forum.xda-developers.com/t/rom-official-kali-nethunter-for-the-oneplus-7-oneplus-7-pro.3976357/
https://unix.stackexchange.com/questions/644512/no-matching-vnc-server-running-for-this-user
https://blog.csdn.net/Qwertyuiop2016/article/details/118105155

