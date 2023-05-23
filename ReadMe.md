# OpenCore： i7 8700k + z370p配置

- CPU：i7 8700K
- 主板：z370p
- 显卡: gtx1060 直接禁用，开机的时候把显示器线插主板上
- 蓝牙+Wifi懒得折腾
- 系统：MacOS Ventura 13.4

# OpenCore主页：

https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html

# 原版MacOS系统镜像下载方法：

[Making the installer in Windows | OpenCore Install Guide (dortania.github.io)](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)



# 安装方法：

- 准备一个U盘，分区方式改成GPT/GUID格式，并格式化为FAT32格式（如果已经是，无需操作）
- 将EFI目录复制到U盘中；
- 将下载后MacOS系统目录放入U盘中；

如下

```
- U盘
 |- EFI
   |- BOOT
   |- OC
 |- com.apple.recovery.boot
   |- BaseSystem.chunklist
   |- BaseSystem.dmg
```



