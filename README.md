# 古剑奇谭三 VR 模组 / Gujian 3 VR Mod

适用于 Steam Windows x64 版《古剑奇谭三》的非官方 OpenXR PCVR 模组。支持头部追踪、逐眼立体画面和可调节的游戏 UI。保留游戏原有键鼠和手柄操作。

Unofficial OpenXR PCVR mod for the Windows x64 Steam edition of **Gujian 3**. Play with head tracking, alternating-eye stereo and an adjustable HUD using the original keyboard, mouse or gamepad controls.

## 下载与安装 / Download and install

Download `Gujian3VR-v0.6.9.zip` from Releases. 退出游戏，将 ZIP 内的 `bin64` 和 `GujianVR` 解压到游戏根目录，与已有 `bin64` 合并。Close the game and extract both folders into the game root. Check that `version.dll` sits beside `Gujian3.exe`. Back up any existing mod with the same filenames first.

1. 连接头显并启动支持 D3D11 的 OpenXR runtime。Connect your headset and start a D3D11-capable OpenXR runtime.
2. 从 Steam 启动游戏。进入可操作场景后按 **F11** 切换沉浸模式，**F9** 回中。Launch through Steam. Press **F11** in gameplay to toggle immersive VR and **F9** to recenter.
3. 按 Esc 暂停，再按 **Insert** 调整 UI 宽度和距离，Enter 保存。Pause with Esc and press **Insert** to adjust HUD width and distance. Press Enter to save.

## v0.6.9 实测与已知问题 / Validation and known issues

- v0.6.8 修正了阳光效果在视野边缘形成的宽暗带，玩家在头显中确认修复有效。v0.6.9 保留该修复，已实测成功进入沉浸模式。The sunlight edge band fix was confirmed in-headset on v0.6.8. Immersive VR startup was confirmed on v0.6.9.
- 部分湖面反射仍有明显竖向分界。Some lake reflections still show a visible vertical boundary.
- 首次测试曾遇到 OpenXR 初始化失败，保持 SteamVR 运行后复测成功。One startup test failed during OpenXR initialization. A subsequent test succeeded with SteamVR running.
- 开发版通过 7 项自动测试。分发配置默认关闭水面和阳光诊断采集。The build passed seven automated tests. Optional water and sunlight capture probes are disabled by default.

完整中英文操作说明、支持的游戏指纹、卸载脚本及第三方许可位于包内 `GujianVR` 目录。See the packaged `GujianVR` folder for the bilingual guide, supported game hash, uninstall script and third-party notices.
