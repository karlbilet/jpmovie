# JavDB 番号批量搜索与磁力提取桌面工具 (Windows & macOS)

<p align="center">
  <img src="assets/icon.png" width="128" height="128" alt="App Icon" />
</p>

一款支持 **Windows** 与 **macOS** 的桌面应用工具，能够根据单个番号、多个番号、番号范围或系列前缀批量搜索 JavDB 影片并自动优选提取磁力链接。

## 📥 下载运行包 (Releases)

请前往右侧或下方 **[Releases 发布页](https://github.com/karlbilet/jpmovie/releases/latest)** 下载对应系统的运行包：

- **Windows 10/11 (64位 单文件免安装版)**：[JavDBMagnetExtractor-Windows-x64.exe](https://github.com/karlbilet/jpmovie/releases/download/v1.0.0/JavDBMagnetExtractor-Windows-x64.exe)
- **macOS (Apple Silicon 独立应用包)**：[JavDBMagnetExtractor-macOS-arm64.zip](https://github.com/karlbilet/jpmovie/releases/download/v1.0.0/JavDBMagnetExtractor-macOS-arm64.zip)

---

## ✨ 核心功能

1. **多番号与多条件混合搜索**
   - **多番号批量输入**：支持逗号、分号、空格或换行分隔输入多个具体番号（如 `ABP-984, SSNI-888, IPX-666`），支持从 `.txt` 导入番号列表。
   - **番号范围搜索**：支持如 `SSNI 001-050` 范围检索。
   - **系列前缀搜索**：支持如 `PPPD` 自动按页遍历该系列下的所有番号。
2. **账号密码直接登录 & 多格式 Cookie 导入**
   - 支持直接输入 JavDB 账号/邮箱与密码登录、内置浏览器可视化过盾登录，或导入 `.json` / `cookies.txt` / 粘贴 Cookie 字符串。
3. **同番号多结果归并 & 智能优选排序**
   - 默认按 **1. 优先破解/无码版本 -> 2. 带中文字幕优先 -> 3. 按文件体积从大到小取第 1 个**（或可选启用“目标体积±容差”区间优先）。
4. **一键复制与导出**
   - 界面表格直观展示提取结果，支持一键复制全部磁力链接，或设置输出目录后自动导出 `.txt` 与 `.csv`。
