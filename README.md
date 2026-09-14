# Dustline

Dustline **0.6.6 build24-public**，持续开发中的 Windows 64 位 Unity FPS 可玩版本。本仓库存放完整游戏运行文件。

## 下载并启动

完整游戏约 **1.63 GB**。两个大型游戏资源由 **Git LFS** 保存，克隆前请安装 Git 和 [Git LFS](https://git-lfs.com/)。在 PowerShell 中执行：

```powershell
git lfs install
git clone https://github.com/mmsx4717/dustline.git
cd dustline
git lfs pull
.\Dustline.exe
```

后续更新可在此目录执行 `git pull` 和 `git lfs pull`。也可在资源下载完成后，直接双击 `Dustline.exe` 启动。请保留旁边的 `Dustline_Data`、`MonoBleedingEdge`、`D3D12` 和 DLL 文件。

请使用上述方式取得完整资源。GitHub 页面中的文件预览及普通源码下载不应直接当作已经下载完整的游戏；如果两个大型资源文件只有几百字节，拿到的是 LFS 指针，请执行 `git lfs pull`。

游戏文件的逐项 SHA256 见 [SHA256SUMS.txt](SHA256SUMS.txt)，详细玩法见 [开始试玩.txt](开始试玩.txt)。

## 模式与操作

单人爆破无需联网，可选择 T / CT 并由 BOT 补位。联机可创建本地房间，或手动填写房主提供的服务器地址、端口和口令。默认端口为 **UDP 27015**；本版使用 **协议 v11**，客户端与房间服务器需保持同版。游戏没有预设私人服务器地址或口令。

| 操作 | 默认按键 |
| --- | --- |
| 移动 / 静步 / 下蹲 | WASD / Shift / Ctrl 或 C |
| 跳跃 | Space |
| 开火 / 瞄准或特殊模式 | 鼠标左键 / 右键 |
| 换弹 / 快速切枪 / 检视 | R / Q / F |
| 丢弃 / 使用 / 购买 | G / E / B |
| 记分板 / 菜单 | Tab / Esc |
| 窗口与全屏切换 | Alt + Enter |

游戏设置支持分辨率、画面比例、亮度、声音、灵敏度、准星及自定义键位。

## 版本状态

本版本仍在开发和测试中，部分表现与原版 CS:GO 有差异，不承诺逐帧一致或固定帧率。build24 已完成文件完整性和公开包检查；本次没有新增 Windows 硬件实测。
