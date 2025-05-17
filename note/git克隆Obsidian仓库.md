来自ai.
# 完整的 Git 克隆 Obsidian 仓库教程

## 步骤 1: 安装 Git

1. **Windows**: 访问 [Git官网](https://git-scm.com/download/win)，下载并安装最新版本。
2. **macOS**: 打开终端并运行以下命令，如果没有安装，终端会提示你安装 Git：
```bash
   git --version
```

  3.**Linux**: 使用包管理器安装 Git。例如，在 Ubuntu 上使用：
```bash
sudo apt update
sudo apt install git
```
## 步骤 2: 克隆 Obsidian 仓库
### 1.**创建一个文件夹**：打开终端/命令行窗口，创建一个文件夹用来存放你要克隆的仓库：
```bash
mkdir obsidian-repo
cd obsidian-repo
```
我自己在F盘放了一个文件夹用于克隆仓库
### 3.**克隆仓库**：你可以通过以下命令来克隆 Obsidian 的 Git 仓库。假设你要克隆官方的 Obsidian 仓库，使用以下命令：
```bash
git clone https://github.com/obsidianmd/obsidian-releases.git
```
