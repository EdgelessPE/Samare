<div align="center">
  <img src="Logo - Light – 1.png" alt="Samare" width="50%" />
</div>

# [Samare](https://firless.cc/)
[中文简体](./README.md)

> Notice: The original name is `Firless`

> Thank you for choosing `Samare`!

`Samare` is positioned as experimental and extensible, with functions between `WinPE` and `RamOS`, and may not be suitable for long-term use or daily maintenance (except for the stable version).

## Features
- MTP (USB connect to mobile phone for file sharing)
- Network card, sound card driver
- Bitlocker
- VC++ 8,9 runtime library
- Partially supported by MSI (Micrsoft Windows Installer)
- RNDIS (USB connect to mobile phone to use mobile phone to share network)
- PPPoE (ADSL dial-up)
- DISM
- Photo viewer (included in the system)
- Picture, WordPad, Notepad3, etc.
- Essential maintenance kit (WinNTSetup, boot repair, DG partition, input method...)
- Edgeless plug-in support (free to add software, drivers, runtime libraries, no need to unpack)
- Ventoy startup compatible

## Download
Join in our telegram! [Official Group](https://t.me/samarepe_group) [Official Channel](https://t.me/samarepe)
You can download the image file in the format of `iso` or `wim` from [Release](https://github.com/EdgelessPE/Firless/releases) of this project to install it.

### Other publishing addresses
[Wuyou Forum](http://bbs.wuyou.net/forum.php?mod=viewthread&tid=426094)

## Version

### Version Number
The currently supported Samare version numbers are `2.x (based on Windows 10)` and `3.x (based on Windows 11)`.

### Branch
Samare has many branch versions. The version number is generally `<version number>+<branch>` or `<version number>_<build date>+<branch>`.

-`stable` stable version: After rigorous testing, the function is stable, suitable for normal use or elderly care.
-`stable_rc` stable candidate version: After general testing, the function is relatively stable, close to `stable`, but there may be some minor flaws.
-`beta` test version: After the virtual machine test, the function is not stable. It is recommended to report the problems encountered during use, so that they can be solved more quickly.
-`nightly`: Built on the latest preview version of Windows, it has not been tested, and the function may be unstable. It is recommended to use the same as above.

## Other

### Precautions
-`Samare` will support `arm64` architecture, but not `ia32` and `ia64` architectures.
-Starting from `Samare 3.1.x`, the `iso` release package of `3.x` no longer provides `Legacy BIOS` boot support.
-`Samare 3.x` requires at least a mobile storage device of `USB 3.x+`.
-From `Samare 3.1.x`, `Illegal Version Checker (Illegal Version Checker)` will be built-in and the boot image will be signed. If the boot image is modified, the `Product Protect` mechanism may be triggered.

### Other options
If you are not in line with your taste, we also provide you with some better options:
1. **FirPE**: Maybe it is the third-party WinPE most suitable for young people, no need to say more. Many of them can communicate with each other, maintain active, and have high compatibility. [Official Website](https://firpe.cn/)
2. **Edgeless**: A new generation of PE toolbox, elegant, powerful, and full of vitality. With powerful plug-in functions and strong playability, FirPE and Firless also support Edgeless plug-ins. [Official Website](https://home.edgeless.top/)
3. **Hikari PE**: Unlike industry benchmarks such as micro PE, Hikari PE keeps up with the forefront of the times while ensuring stable functions, exploring more possibilities for using PE to maintain PCs. It also supports Edgeless plug-ins, suitable for Users with a certain foundation. [Official Website](https://hikaripe-sc.hikaricalyx.com/)
4. **We PE**: Classic, easy to use without a lot of words. [Official Website](http://www.wepe.com.cn/)
5. **EasyU**: Widely compatible, stable and durable, quick start. [Official Website](https://www.itsk.com/thread-417902-1-1.html)

### Translation
Of course, if you feel that the document translation is improper, you can modify it and initiate a Pull Request to this repository. We welcome this.
