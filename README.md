# ChinaK12BookDownLoader

[![GitHub release](https://img.shields.io/github/v/release/scott20201225/ChinaK12BookDownLoader?color=3b82f6&logo=github)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-macOS%20|%20Windows%20|%20Linux-brightgreen)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/scott20201225/ChinaK12BookDownLoader?style=social)](https://github.com/scott20201225/ChinaK12BookDownLoader)

> **国家中小学智慧教育平台（basic.smartedu.cn）K12 电子教材可视化批量下载器与版本归档管理系统**  
> 界面精简直观、极简暗黑质感，支持按学段/学科/版本/年级多维级联筛选、**一键全选批量下载**、**前置秒级核对与毫秒跳过**、**同目录下同名旧版与下架资源 History 智能归档**、**严格双并发防封限流**。

`#国家中小学智慧教育平台` `#电子教材下载器` `#电子课本` `#人教版` `#统编版` `#北师大版` `#苏教版` `#小学初中高中课本` `#教材PDF下载` `#智慧中小学`

---

## 📥 客户端最新下载地址 (Download)

> 💡 **开箱即用，无需配置任何 Node.js 运行环境**。以下直链采用 GitHub 动态重定向机制，**无论未来版本如何迭代发布，点击均会永久自动下载官方最新版本**：  
> 🔗 **全平台版本官方发布页**：👉 [**GitHub Releases 最新版本直达**](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest)

| 操作系统 (OS) | 适用设备 / 芯片架构 | 推荐安装包（点击直接下载最新版） | 便携免安装版 / 其他格式（永久最新） |
| :--- | :--- | :--- | :--- |
| **Windows** | 常见 64 位电脑（Intel / AMD） | 🚀 [**Windows x64 安装包 (.exe)**](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-win-x64-setup.exe) | [x64 免安装便携版 (.zip)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-win-x64.zip) |
| **Windows** | 骁龙 / ARM 芯片（Surface / Copilot+ PC） | 🚀 [**Windows ARM64 安装包 (.exe)**](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-win-arm64-setup.exe) | [ARM64 免安装便携版 (.zip)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-win-arm64.zip) |
| **macOS** | Apple Silicon（M1 / M2 / M3 / M4 系列） | 🚀 [**macOS ARM64 安装镜像 (.dmg)**](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-mac-arm64.dmg) | [arm64 便携版 (.zip)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-mac-arm64.zip) |
| **macOS** | Intel 处理器机型（旧款 Mac） | 🚀 [**macOS x64 安装镜像 (.dmg)**](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-mac-x64.dmg) | [x64 便携版 (.zip)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-mac-x64.zip) |
| **Linux** | 常见 64 位 PC（Ubuntu / Debian / Arch 等） | 🚀 [**Linux x86_64 通用版 (.AppImage)**](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-linux-x86_64.AppImage) | [Debian/Ubuntu (.deb)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-linux-amd64.deb) / [绿色包 (.tar.gz)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-linux-x64.tar.gz) |
| **Linux** | 统信 UOS / 银河麒麟 / 树莓派 ARM64 | 🚀 [**Linux ARM64 通用版 (.AppImage)**](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-linux-arm64.AppImage) | [Debian/麒麟 (.deb)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-linux-arm64.deb) / [绿色包 (.tar.gz)](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/chinak12-downloader-linux-arm64.tar.gz) |

> 📌 **完整性校验**：所有安装包的 SHA-256 校验和清单请参见 [SHA256SUMS.txt](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest/download/SHA256SUMS.txt)。  
> ⚠️ **首次运行安全提示**：由于未购买商业开发者证书，macOS 提示“已损坏/无法打开”或 Windows 提示“SmartScreen”请参考下方 [安装与运行说明](#-安装与运行说明) 快速放行。

---

## 📷 界面预览与功能展示

| 教材主界面与多维级联筛选 | 实时下载管理器抽屉（限并发/速率/状态管理） |
| :---: | :---: |
| ![教材主界面与多维级联筛选](assets/preview-main.png) | ![实时下载任务管理器抽屉](assets/preview-drawer.png) |

---

## 🌟 核心特性

1. **可视化目录选择与安全防护**：
   - 原生文件夹选择器，选择目录后自动生效；
   - 未设置目录时强制禁止下载并高亮预警，避免下载到错误路径。

2. **前置秒级核对与智能跳过（零重复流量）**：
   - 点击批量下载瞬间，毫秒级扫描本地磁盘与目标路径；
   - 本地已存在正版教材直接置为 `已存在(跳过)`，绝不推入排队队列空转；
   - 自动识别历史旧格式命名前缀并就地规范化为标准官方名称。

3. **严格的同目录同名教材归档（History 镜像存储）**：
   - **规则 1：同一个目录下的同名教材不是最新，归档**：新旧版本并存时，旧版课标教材自动安全迁移至 `History/` 对应镜像路径，主目录仅保留官方最新版；
   - **规则 2：官网已删除/下架但本地拥有的，归档**：历史资源自动迁移至 `History/` 镜像完整保存，绝不物理删除。

4. **一键全选与严格限并发下载**：
   - 支持勾选当前页及“全选筛选结果”，可一键将数千本课本加入下载队列；
   - 底层严格锁死 2 个并发 Worker 并引入动态随机休眠，避免冲击官方 CDN 导致 IP 封禁或 403 拒绝。

5. **实时三标签下载任务抽屉**：
   - 顶部实时展示任务统计 `(正在下载 / 失败 / 已完成)`，点击即可滑出任务抽屉；
   - 严格区分 `下载成功`（绿）、`已存在(跳过)`（紫）与 `已归档`（黄）；
   - 支持单任务与全部暂停、恢复、批量重试、删除以及在访达/资源管理器中一键高亮定位。

---

## 🚀 启动与使用方式

### 方式一：Node.js Web 模式（零配置秒开）

```bash
cd ChinaK12BookDownLoader
node server.js 8080
```
在浏览器打开：[http://127.0.0.1:8080](http://127.0.0.1:8080)

---

### 方式二：桌面客户端安装包（开箱即用，推荐）

可直接前往顶部 [**📥 客户端最新下载地址**](#-客户端最新下载地址-download) 点击对应系统直链下载，或访问 [GitHub Releases 最新发版列表](https://github.com/scott20201225/ChinaK12BookDownLoader/releases/latest)。

#### 🍎 macOS 安装与运行说明
因为个人开源项目未购买商业 Apple 开发者数字签名，若 macOS 系统提示“已损坏”或“无法打开”，请参照以下方法放行：
- 打开【系统设置】→【隐私与安全性】→【安全性】，查看是否允许“任何来源”；若无此选项，打开终端输入：
  ```bash
  sudo spctl --master-disable
  ```
  回车并输入开机密码。
- 若打开应用仍提示已损坏，在终端执行：
  ```bash
  sudo xattr -r -d com.apple.quarantine /Applications/ChinaK12BookDownLoader.app
  ```
  *(若应用放在其他路径，可输入 `sudo xattr -r -d com.apple.quarantine ` 后留一个空格，将应用图标拖入终端回车即可)*。

#### 🪟 Windows 安装与运行说明
- 若启动安装包时弹出 Windows Defender SmartScreen 提示“Windows 已保护你的电脑”：
  1. 点击提示框内的 **“更多信息”**；
  2. 点击右下角出现的 **“仍要运行”** 即可正常安装与启动。
- 提供两种格式：
  - `*-setup.exe`：标准安装向导，可自定义安装路径并自动创建桌面快捷方式。
  - `*.zip`：免安装便携版，解压后双击 `ChinaK12BookDownLoader.exe` 即可直接运行。

#### 🐧 Linux 安装与运行说明
- **AppImage 格式（推荐，全发行版通用）**：
  ```bash
  chmod +x chinak12-downloader-linux-*.AppImage
  ./chinak12-downloader-linux-*.AppImage
  ```
  *(若系统缺少 FUSE，可附加 `--appimage-extract-and-run` 参数或安装 `libfuse2`)*。
- **Debian / Ubuntu 系列（`.deb`）**：
  ```bash
  sudo dpkg -i chinak12-downloader-linux-*.deb
  ```

---

### 方式三：开发者模式与本地打包

```bash
cd ChinaK12BookDownLoader
npm install

# 运行桌面版
npm start

# 构建本地安装包
npm run build:mac:arm64    # macOS Apple Silicon
npm run build:mac:x64      # macOS Intel
npm run build:win:x64      # Windows x64
npm run build:win:arm64    # Windows ARM64
npm run build:linux:x64    # Linux x64
npm run build:linux:arm64  # Linux ARM64
```

---

## 📁 课本存放目录规范

```
China12Books/
├── 小学/
│   ├── 数学/
│   │   └── 人教版-人民教育出版社/
│   │       └── 一年级/
│   │           └── 义务教育教科书·数学一年级上册 [2022修订版].pdf
│   └── 语文/
├── 初中/
├── 高中/
└── History/                          <-- 官方下架/更新的历史版本镜像归档
    └── 小学/
        └── 数学/
            └── 人教版-人民教育出版社/
                └── 一年级/
                    └── 义务教育教科书·数学一年级上册 [2012旧课标版].pdf
```
