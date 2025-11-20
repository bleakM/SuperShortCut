# The latest word -- the SUPER-SHORTCUT!
## Version 3.1 is released, with enhanced detail design, increased flexibility, and the addition of local backup and global lock functions (which can disable input when the computer is not locked).
## Now, English, Japanese and French are all fully supported!
# 最新消息！
## 3.1 版本已发布，具有更精细的细节设计、更高的灵活性，并新增了本地备份和全局锁定功能（当电脑未锁定时，该功能可禁用输入）。
## 全新支持中、英、日、法！


# 中文版本Chinese

一个轻量级文件快捷方式管理器，帮助你快速访问常用文件夹，支持别名设置、深色模式等功能，提升文件管理效率。
有了shortCut，原本桌面上乱糟糟的文件都会变得整洁，所有重要文件也触手可及！

## 功能特点

- 🚀 **快捷方式管理**：添加、重命名、移除常用文件夹快捷方式，一键访问
- 🔖 **别名设置**：为文件夹自定义别名，隐藏复杂路径
- 🌙 **深色/浅色模式**：根据使用习惯切换界面风格
- 📋 **路径操作**：快速复制文件/文件夹路径、打开所在位置
- 📁 **文件操作**：支持新建、重命名、删除文件/文件夹（移至回收站）
- 🔄 **自动展开**：设置常用文件夹默认展开，无需手动点击

## 安装方法

1. 下载最新版本的 `shortCut2Files.exe`（或压缩包）
2. 创建快捷方式，放置到桌面上双击运行即可

> 注意：仅支持 Windows 系统（Windows 10/11 测试通过）

## 使用说明

### 1. 管理快捷方式
- **添加**：点击「管理快捷方式」→「添加」，选择需要添加的文件夹
- **重命名/移除**：在快捷方式上右键，选择「重命名」或「从库中移除」
- **默认展开**：右键快捷方式，勾选「默认展开」，下次启动自动展开该文件夹

### 2. 文件夹别名
- 右键文件夹 →「设置别名」，输入自定义名称（如将“D:/Work/Project2025”设为“我的项目”）
- 别名会显示在树形视图中，原路径保持不变

### 3. 常用操作
- **打开位置**：选中文件/文件夹，点击「显示选中位置」快速跳转
- **复制路径**：点击「复制选中路径」，将完整路径复制到剪贴板
- **新建文件/文件夹**：右键父文件夹 →「新建」→ 选择类型并输入名称

## 界面截图

### 浅色模式
<img width="1193" height="1461" alt="image" src="https://github.com/user-attachments/assets/7bac9530-3478-4145-aba4-57f1624a492b" />


### 深色模式
<img width="1194" height="1472" alt="image" src="https://github.com/user-attachments/assets/fc6d57d3-3182-42f5-a122-0f4738499328" />


### 快捷方式管理
<img width="1124" height="792" alt="image" src="https://github.com/user-attachments/assets/72ea1265-8e5b-43a1-81c3-e7148131380f" />


## 更新日志

### v1.0.0（首次发布）(i2.0)
- 支持文件夹快捷方式添加/删除/重命名
- 实现文件夹别名功能
- 深色/浅色模式切换
- 基础文件操作（新建/删除/重命名）

## 开发说明

本项目基于 Python 的 Tkinter 库开发，主要依赖：
- `tkinter`：图形界面框架
- `json`：配置文件存储
- `ctypes`：Windows 系统交互（如回收站功能）

如需二次开发：
1. 克隆仓库：`git clone https://github.com/bleakM/shortCut2Files.git`
2. 安装依赖（Python 3.8+）：无需额外依赖（标准库已包含）
3. 运行源码：`python main.py`

## 许可证

本项目基于 [MIT 许可证](LICENSE) 开源，欢迎自由使用和修改。

## 反馈与贡献

- 如有 Bug 或建议，欢迎提交 [Issue](https://github.com/bleakM/shortCut2Files/issues)
- 欢迎 Fork 并提交 Pull Request 改进功能


# English
 
# shortCut2Files 📂

A lightweight file shortcut manager that helps you quickly access frequently used folders. It supports alias setting, dark mode, and other features to improve file management efficiency.
With shortCut, the originally messy files on the desktop will become neat, and all important files will be within easy reach!

## Features

- 🚀 **Shortcut Management**: Add, rename, and remove shortcuts for frequently used folders for one-click access.
- 🔖 **Alias Setting**: Customize aliases for folders to hide complex paths.
- 🌙 **Dark/Light Mode**: Switch between interface styles based on usage habits.
- 📋 **Path Operations**: Quickly copy file/folder paths and open their locations.
- 📁 **File Operations**: Create, rename, and delete files/folders (moves to Recycle Bin).
- 🔄 **Auto-expand**: Set frequently used folders to expand automatically on startup, no manual clicking required.


## Installation

1. Download the latest version of `shortCut2Files.exe` (or the compressed file)
2. Create a shortcut and place it on the desktop. Double-click to run it.

> **Note**: Only supports Windows systems (tested on Windows 10/11).


## Usage Guide

### 1. Manage Shortcuts
- **Add**: Click "管理快捷方式" (Manage Shortcuts) → "添加" (Add), then select the folder to add.
- **Rename/Remove**: Right-click a shortcut and select "重命名" (Rename) or "从库中移除" (Remove from Library).
- **Auto-expand**: Right-click a shortcut and check "默认展开" (Auto-expand) to make it expand automatically on next startup.

### 2. Folder Aliases
- Right-click a folder → "设置别名" (Set Alias), then enter a custom name (e.g., set "D:/Work/Project2025" to "我的项目" (My Project)).
- The alias will be displayed in the tree view, while the original path remains unchanged.

### 3. Common Operations
- **Open Location**: Select a file/folder and click "显示选中位置" (Show Selected Location) to jump directly.
- **Copy Path**: Click "复制选中路径" (Copy Selected Path) to copy the full path to the clipboard.
- **Create New File/Folder**: Right-click a parent folder → "新建" (New) → select the type and enter a name.


## Interface Screenshots

### Light Mode
<img width="1193" height="1461" alt="image" src="https://github.com/user-attachments/assets/7bac9530-3478-4145-aba4-57f1624a492b" />

### Dark Mode

<img width="1194" height="1472" alt="image" src="https://github.com/user-attachments/assets/fc6d57d3-3182-42f5-a122-0f4738499328" />

### Shortcut Management
<img width="1124" height="792" alt="image" src="https://github.com/user-attachments/assets/72ea1265-8e5b-43a1-81c3-e7148131380f" />


## Changelog

### v1.0.0 (Initial Release)
- Support adding/deleting/renaming folder shortcuts.
- Implement folder alias functionality.
- Add dark/light mode switching.
- Basic file operations (create/delete/rename).


## Development Notes

This project is developed based on Python’s Tkinter library, with core dependencies including:
- `tkinter`: GUI framework (included in Python standard library).
- `json`: For configuration file storage.
- `ctypes`: For Windows system interactions (e.g., Recycle Bin functionality).

For secondary development:
1. Clone the repository: `git clone https://github.com/bleakM/shortCut2Files.git`
2. Install dependencies (Python 3.8+): No additional dependencies required (all use standard libraries).
3. Run the source code: `python main.py`


## License

This project is open-source under the [MIT License](LICENSE). You are free to use and modify it.


## Feedback & Contributions
- If you encounter bugs or have suggestions, feel free to submit an [Issue](https://github.com/bleakM/shortCut2Files/issues).
- Fork the repository and submit a Pull Request to contribute improvements.
