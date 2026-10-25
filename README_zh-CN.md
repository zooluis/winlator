<p align="center">
	<img src="logo.png" width="376" height="128" alt="Winlator Logo" />
</p>

<p align="center">
	<a href="https://winlator.org/">
		<img src="https://img.shields.io/badge/winlator-website-42a5f5?style=flat-square" />
	</a>
	<a href="https://github.com/brunodev85/winlator/releases">
		<img src="https://img.shields.io/github/downloads/brunodev85/winlator/v11.2.0/total.svg?style=flat-square&label=downloads@v11.2" />
	</a>
	<a href="https://github.com/brunodev85/winlator/stargazers">
		<img src="https://img.shields.io/github/stars/brunodev85/winlator?style=flat-square&logo=github&color=ffb300" />
	</a>
</p>

# Winlator

Winlator 是一款 Android 应用，让你能用 Wine 和 Box86/Box64 运行 Windows (x86_64) 应用程序。

# 安装

1. 从 [GitHub Releases](https://github.com/brunodev85/winlator/releases) 下载并安装 APK（Winlator_11.2.apk）
2. 启动应用并等待安装过程完成

----

[![Play on Youtube](https://img.youtube.com/vi/ETYDgKz4jBQ/3.jpg)](https://www.youtube.com/watch?v=ETYDgKz4jBQ)
[![Play on Youtube](https://img.youtube.com/vi/9E4wnKf2OsI/2.jpg)](https://www.youtube.com/watch?v=9E4wnKf2OsI)
[![Play on Youtube](https://img.youtube.com/vi/czEn4uT3Ja8/2.jpg)](https://www.youtube.com/watch?v=czEn4uT3Ja8)
[![Play on Youtube](https://img.youtube.com/vi/eD36nxfT_Z0/2.jpg)](https://www.youtube.com/watch?v=eD36nxfT_Z0)
[![Play on Youtube](https://img.youtube.com/vi/GHBKmzGmhoo/1.jpg)](https://www.youtube.com/watch?v=GHBKmzGmhoo)

----

# 实用技巧

- 如果遇到稳定性问题，尝试在 容器设置 -> 高级 选项卡中更改 Box64 预设。
- 对于使用 .NET Framework 的应用程序，尝试安装 开始菜单 -> 系统工具 -> 安装程序 中的 Wine Mono。
- 如果某些老游戏无法打开，尝试在 容器设置 -> 环境变量 中添加环境变量 `MESA_EXTENSION_MAX_YEAR=2003`。
- 尝试通过 Winlator 主屏幕上的快捷方式运行游戏，在那里你可以为每个游戏单独定义设置。
- 要正确显示低分辨率游戏，尝试在快捷方式设置中启用 强制全屏 选项。
- 为了提高使用 Unity 引擎的游戏稳定性，尝试将 Box64 预设改为 `Stability`，或在快捷方式设置中添加 exec 参数 `-force-gfx-direct`。
- 如果遇到音频爆音，尝试增加 ALSA/PulseAudio 配置中的平均延迟。像 Unreal Gold 这样的老游戏，把该值增加到 90ms 即可解决音频问题。

# 致谢与第三方应用

- GLIBC 补丁来自 [Termux Pacman](https://github.com/termux-pacman/glibc-packages)
- Wine（[winehq.org](https://www.winehq.org/)）
- Box86/Box64 来自 [ptitseb](https://github.com/ptitSeb)
- Mesa（Turnip/Zink/VirGL）（[mesa3d.org](https://www.mesa3d.org)）
- DXVK（[github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk)）
- VKD3D（[gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d)）
- CNC DDraw（[github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw)）

特别感谢参与这些项目的所有开发者。<br>
感谢所有相信这个项目的人。
