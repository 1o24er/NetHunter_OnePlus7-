# NetHunter_OnePlus7+

# 准备
NetHunter||OnePlus7Plus

1.一加7Pro手机

2.谷歌的adb和fastboot工具集（platform-tools）
https://developer.android.google.cn/studio/releases/platform-tools

3.氧OS线刷包
OxygenOS 10.3.0 (non-EU only)
OnePlus 7 Pro: OnePlus7ProOxygen_21.P.24_OTA_024_all_1912142025_acd8caa52e0b.zip
https://otafsg1.h2os.com/patch/amazone2/GLO/OnePlus7ProOxygen/OnePlus7ProOxygen_21.P.24_GLO_024_1912142025/OnePlus7ProOxygen_21.P.24_OTA_024_all_1912142025_acd8caa52e0b.zip

其他版本可用地址：
https://yun.daxiaamu.com/%E4%B8%80%E5%8A%A0%E6%89%8B%E6%9C%BA%E5%AE%98%E6%96%B9ROM/
https://www.androidsage.com/2020/02/15/download-oxygen-os-10-3-1-ota-update-oneplus-7-7-pro-7t-7t-pro/
https://www.thecustomdroid.com/download-oneplus-7-pro-oxygenos-android-10-update/#oxygenos-1030-non-eu-only

4.Twrp 
img后缀的临时刷机包：https://sourceforge.net/projects/mauronofrio-twrp/files/Guacamole-Guacamoleb-Guacamolec/twrp-3.4.0-10-guacamole-unified-Q-mauronofrio.img/download
zip后缀的永久刷机包：https://sourceforge.net/projects/mauronofrio-twrp/files/Guacamole-Guacamoleb-Guacamolec/twrp-3.4.0-10-guacamole-unified-installer-mauronofrio.zip/download
XDA非官方版本：https://forum.xda-developers.com/t/recovery-3-4-0-10-unified-official-unofficial-twrp-for-oneplus-7-7-pro-5g-stable.3932943/

5.Magisk
https://github.com/topjohnwu/Magisk/releases
Magisk-v21.4.zip
Magisk-v23.0.apk

6.Disable_Dm-Verity_ForceEncrypt
https://wwx.lanzoui.com/i8t6Dql0igb

7.Kali Nethunter刷机包
https://www.kali.org/get-kali/#kali-mobile

# 步骤

### 第一步：刷机（OxygenOS 10.3.0）
1. 
运行“gpedit.msc”-打开本地组策略编辑器
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

