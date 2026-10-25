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

Winlator 是一款 Android 應用，讓你能用 Wine 和 Box86/Box64 執行 Windows (x86_64) 應用程式。

# 安裝

1. 從 [GitHub Releases](https://github.com/brunodev85/winlator/releases) 下載並安裝 APK（Winlator_11.2.apk）
2. 啟動應用並等待安裝過程完成

----

[![Play on Youtube](https://img.youtube.com/vi/ETYDgKz4jBQ/3.jpg)](https://www.youtube.com/watch?v=ETYDgKz4jBQ)
[![Play on Youtube](https://img.youtube.com/vi/9E4wnKf2OsI/2.jpg)](https://www.youtube.com/watch?v=9E4wnKf2OsI)
[![Play on Youtube](https://img.youtube.com/vi/czEn4uT3Ja8/2.jpg)](https://www.youtube.com/watch?v=czEn4uT3Ja8)
[![Play on Youtube](https://img.youtube.com/vi/eD36nxfT_Z0/2.jpg)](https://www.youtube.com/watch?v=eD36nxfT_Z0)
[![Play on Youtube](https://img.youtube.com/vi/GHBKmzGmhoo/1.jpg)](https://www.youtube.com/watch?v=GHBKmzGmhoo)

----

# 實用技巧

- 如果遇到穩定性問題，嘗試在 容器設定 -> 進階 索引標籤中變更 Box64 預設。
- 對於使用 .NET Framework 的應用程式，嘗試安裝 開始功能表 -> 系統工具 -> 安裝程式 中的 Wine Mono。
- 如果某些老遊戲無法開啟，嘗試在 容器設定 -> 環境變數 中新增環境變數 `MESA_EXTENSION_MAX_YEAR=2003`。
- 嘗試透過 Winlator 主螢幕上的捷徑執行遊戲，在那裡你可以為每個遊戲單獨定義設定。
- 要正確顯示低解析度遊戲，嘗試在捷徑設定中啟用 強制全螢幕 選項。
- 為了提高使用 Unity 引擎的遊戲穩定性，嘗試將 Box64 預設改為 `Stability`，或在捷徑設定中新增 exec 參數 `-force-gfx-direct`。
- 如果遇到音訊爆音，嘗試增加 ALSA/PulseAudio 設定中的平均延遲。像 Unreal Gold 這樣的老遊戲，把該值增加到 90ms 即可解決音訊問題。

# 致謝與第三方應用

- GLIBC 修補程式來自 [Termux Pacman](https://github.com/termux-pacman/glibc-packages)
- Wine（[winehq.org](https://www.winehq.org/)）
- Box86/Box64 來自 [ptitseb](https://github.com/ptitSeb)
- Mesa（Turnip/Zink/VirGL）（[mesa3d.org](https://www.mesa3d.org)）
- DXVK（[github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk)）
- VKD3D（[gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d)）
- CNC DDraw（[github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw)）

特別感謝參與這些專案的所有開發者。<br>
感謝所有相信這個專案的人。
