# 7-Zip Smart Extract for Windows

English | [简体中文](#简体中文)

## English

This project is a Windows-focused modification of [7-Zip](https://github.com/ip7z/7zip), based on the 7-Zip 26.01 source release.

It is not the official 7-Zip project. The official 7-Zip website is [7-zip.org](https://7-zip.org).

### Windows changes

- Adds a top-level 7-Zip shell menu item: **Smart Extract and Open**.
- Smart extraction automatically uses 7-Zip's existing root-folder deduplication behavior, then opens the extracted destination folder.
- Adds Simplified Chinese fallback text for the modified Windows shell menu.
- The Windows installer associates common archive formats with `7zFM.exe`, so double-clicking an archive opens the 7-Zip File Manager.
- Keeps the official **Test archive** shell menu behavior.

### License

This project keeps the original 7-Zip licensing terms. 7-Zip is distributed mainly under the GNU LGPL, with the unRAR license restriction and some BSD/public-domain components. See [DOC/License.txt](DOC/License.txt) for the full license details.

The modified code must continue to follow the original license terms, including the unRAR restriction.

## 简体中文

本项目基于 [7-Zip](https://github.com/ip7z/7zip) 源码修改，基础版本为 7-Zip 26.01，当前改动只面向 Windows 版本。

本项目不是官方 7-Zip 项目。官方 7-Zip 网站是 [7-zip.org](https://7-zip.org)。

### Windows 改动

- 新增置顶的 7-Zip 右键菜单项：**智能解压并打开**。
- 智能解压会复用 7-Zip 已有的根目录去重逻辑，解压完成后自动打开目标文件夹。
- 为修改后的 Windows 右键菜单增加简体中文兜底文本。
- Windows 安装器会将常见压缩格式关联到 `7zFM.exe`，双击压缩包会打开 7-Zip File Manager。
- 保留官方 **测试压缩包 / Test archive** 右键菜单行为。

### 许可证

本项目保留原 7-Zip 的许可证条款。7-Zip 主要基于 GNU LGPL 发布，同时包含 unRAR license restriction 以及部分 BSD / public domain 组件。完整许可证说明见 [DOC/License.txt](DOC/License.txt)。

修改后的代码仍需遵守原项目许可证条款，包括 unRAR 限制。
