# 解决电脑大师 · 破甲客户端AI安装包发布库

本仓库发布「解决电脑大师」安装包（exe）。

---

## 📥 怎么下载安装包（跟着点就行）

**第 1 步**：打开本仓库主页

> https://github.com/4311272/dsh-releases

**第 2 步**：看页面**右边那一栏**，在 "About" 下面找到 **Releases** 这一块
（会显示 `Releases 1`，最新版本是 **解决电脑大师 3.3.0**，后面带绿色 `Latest` 标签）

> 找不到右侧栏也没关系，直接点这个链接进 Releases 列表：
> **https://github.com/4311272/dsh-releases/releases**

**第 3 步**：在 Releases 列表里点最新那条 **「解决电脑大师 3.3.0」**

**第 4 步**：进到版本详情页后，往下滑到底部，找到 **Assets** 这一块
（老版页面可能在页面最下方折叠着，点一下 `Assets` 展开）

**第 5 步**：点文件名 **`ASA-DSH-3.3.0-setup.exe`** 开始下载
（浏览器会跳到下载页，等几秒自动开始；文件约 267 MB）

**第 6 步**：下载完成后双击 exe 运行，按提示安装即可

### 手机上怎么下

Releases 页面在手机上会把 Assets 折起来，点 **「Assets」** 展开后再点 `ASA-DSH-3.3.0-setup.exe` 即可下载。

### 一劳永逸的直链（可复制到浏览器 / 网盘离线下载 / 下载工具）

```
https://github.com/4311272/dsh-releases/releases/download/v3.3.0/ASA-DSH-3.3.0-setup.exe
```

---

## 📦 仓库里的文件说明

| 文件 | 说明 |
| --- | --- |
| `ASA-DSH-3.3.0-setup.exe` | 安装包本体（约 267 MB），在 Releases 里 |
| `update.json` | 更新通道元数据（version / url / sha256），供客户端检查新版本用 |

### 校验下载是否完整（可选）

Windows 命令行里执行：

```
certutil -hashfile ASA-DSH-3.3.0-setup.exe SHA256
```

对比这一串，一致就是完整的、没被篡改：

```
ecd0ba702e89b228bbe2f3a40fef87d2b32a538cd2c873c92271ed8d0e02d0fb
```

---

## 💬 官方交流群

**QQ 群：702195628**

安装、授权、使用中遇到任何问题，进群问，群里有人管。

---
