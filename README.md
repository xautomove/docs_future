# 快速开始

FutureDrive 是一个模块化的自动驾驶开发平台，提供实用工具、开箱即用的解决方案和高效的开发部署流程，旨在简化和加速自动驾驶相关项目的研发。

---

## 运行前置条件

- 操作系统：**Ubuntu 22.04**
- 缓存：**redis**
- 建议提前安装好 Node.js（如需源码运行）

---

## 安装方式一：直接下载 AppImage

1. 前往 [Releases 页面](https://github.com/xautomove/FutureDrive/releases) 下载最新的 `FutureDrive-x.x.x.AppImage` 文件。
2. 赋予可执行权限：
   ```bash
   chmod +x FutureDrive-x.x.x.AppImage
   ```
3. 双击运行或命令：
   ```bash
   ./FutureDrive-x.x.x.AppImage
   ```
---

## 安装方式二：源码运行（开发模式）

1. 克隆仓库：
   ```bash
   git clone https://github.com/xautomove/FutureDrive.git
   cd FutureDrive
   ```
2. 安装 yarn（如未安装）：
   ```bash
   npm install -g yarn
   ```
3. 安装依赖：
   ```bash
   yarn install
   ```
4. 安装redis
   ```bash
   sudo apt install redis-server
   ```
4. 启动开发环境：
   ```bash
   yarn dev
   ```

---

## 更多信息

- [FutureDrive 仓库](https://github.com/xautomove/FutureDrive)