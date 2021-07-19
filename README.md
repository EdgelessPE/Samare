<div align="center">
  <img src="Logo - Light- Square – 1.svg" alt="Firless" width="40%" />
</div>

# Firless
[English (unavailable)](./README-en.md)

> 感谢您选择 `Firless` !

`Firless` 定位为实验性、可拓展，功能介于 `WinPE` 和 `RamOS` 之间，可能并不适合养老或日常维护（除正式版外）。

## 功能
- MTP (USB连接手机进行文件共享)
- 网卡、声卡驱动
- Bitlocker
- VC++ 8,9 运行库
- MSI(Micrsoft Windows Installer) 部分支持
- RNDIS (USB连接手机使用手机共享网络)
- PPPoE (ADSL拨号)
- DISM
- 照片查看器(系统自带)
- 图画、写字板、Notepad3等
- 必备维护工具包（WinNTSetup, 引导修复, DG分区，输入法....）
- Edgeless 插件支持 （可自由添加软件、驱动、运行库，无需解包）
- Ventoy 启动兼容

## 下载
您可以从本项目的 [Release](https://github.com/EdgelessPE/firless-release/releases) 下载格式为 `iso` 或者 `wim` 的镜像文件进行安装。

## 版本

### 版本号
目前受支持的 Firless 版本号为 `2.x (基于 Windows 10)` 和 `3.x (基于 Windows 11)`。

### 分支
Firless 有许多分支版本。版本号一般是 `<版本号>+<分支>` 或 `<版本号>_<构建日期>+<分支>`。

- `stable` 稳定版: 经过严格测试，功能稳定，适合平常使用或养老。
- `stable_rc` 稳定候选版: 经过普遍测试，功能较为稳定，接近 `stable`，但可能会有一些小瑕疵。
- `beta` 测试版: 经过虚拟机测试，功能较不稳定。使用时建议将遇到的问题上报，以便更快地解决。
- `nightly` 每夜版: 基于最新预览版 Windows 构建，未经过测试，功能可能会很不稳定。使用时建议同上。

## 其他
### 注意事项
- `Firless` 将会支持 `arm64` 架构，但不支持 `ia32` 以及 `ia64` 架构。
- `Firless 3.1.x` 起，`3.x` 的 `iso` 发行包不再提供 `Legacy BIOS` 启动支持。
- `Firless 3.x` 至少需要 `USB 3.x+` 的移动储存设备。
- `Firless 3.1.x` 起，将内置 `Illegal Version Checker (非法版本检测器)`，并对启动镜像进行签名。如对启动镜像进行修改，可能会触发 `Product Protect (产品保护)` 机制。

### 其他选择
如果您不太符合您的口味，我们也提供了一些较好的选择给您: 
1. **FirPE**: 也许是最适合年轻人使用的第三方WinPE，不必多言。和 Firless 一家，很多都可以互通，维护活跃，高兼容度。 [官网](https://firpe.cn/) 
2. **Edgeless**: 新生代的PE工具箱，优雅强大，充满活力。拥有强大的插件功能，可玩性强，FirPE 和 Firless 也支持 Edgeless 插件。 [官网](https://home.edgeless.top/) 
3. **Hikari PE**: 和微PE这样的行业标杆不同，Hikari PE 在保证功能稳定的情况下，紧跟时代前沿，探索使用 PE 维护 PC 的更多可能性，也支持 Edgeless 插件，适合有一定基础的用户。[官网](https://hikaripe-sc.hikaricalyx.com/) 
4. **微 PE**: 经典，好用无需多言。[官网](http://www.wepe.com.cn/) 
5. **EasyU 优启通**: 广泛兼容、稳定耐用、快速启动。 [官网](https://www.itsk.com/thread-417902-1-1.html)
