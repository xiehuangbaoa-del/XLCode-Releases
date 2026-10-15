# XLCode · 用户版下载

> **Windows x64 测试版。下面只有一个程序 ZIP，下载它即可。**

## 下载

### [⬇ 下载 Windows x64 用户版程序（约 214 MB）](https://github.com/xiehuangbaoa-del/XLCode-Releases/releases/download/user-20261015-r1/XLCodeUser-20261015-r1-fd2dc813.zip)

文件名：`XLCodeUser-20261015-r1-fd2dc813.zip`  
版本：`20261015-r1` · Build：`fd2dc813`

- [查看本版发布说明](https://github.com/xiehuangbaoa-del/XLCode-Releases/releases/tag/user-20261015-r1)
- [用户使用说明](https://github.com/xiehuangbaoa-del/XLCode-Releases/releases/download/user-20261015-r1/README-user.md)
- [SHA-256 校验文件](https://github.com/xiehuangbaoa-del/XLCode-Releases/releases/download/user-20261015-r1/SHA256SUMS.txt)
- [验收说明](https://github.com/xiehuangbaoa-del/XLCode-Releases/releases/download/user-20261015-r1/ACCEPTANCE.md)

**不要选择 GitHub 自动生成的 “Source code” ZIP。** 这个仓库只提供发行下载与说明，不单独托管 XLCode 工程源码；自动源码归档不是程序包。

## 开始使用

1. 下载上面的程序 ZIP，并核对 SHA-256。
2. 解压整个 ZIP，进入 `XLCodeUser` 文件夹，运行 `XLCodeUser.exe`。
3. 内置 Agent 需要 Node.js **>=22.19.0**（含 npm）和受支持的 pi；缺少时按应用内提示操作。安装 Node 后请完全退出并重开应用。
4. 在本用户版“能力 → 服务商与登录”中配置你自己的模型账号或 API Key。模型服务可能收费，包内没有提供者的真实密钥或免费额度。

## 测试版说明

- **未做发行者代码签名**，Windows 可能出现 SmartScreen 提示。请确认来源，不要因此关闭安全软件。
- 用户版使用独立的应用／Bridge／pi 配置，不自动读取或迁移其他 pi 的登录与会话。
- 独立配置不是操作系统沙箱；使用命令和文件工具前，请确认项目与权限。
- 已完成本轮自动回归及包级验收；未进行线上模型调用，也不代表完整干净机器、企业网络和升级矩阵全部通过。

## 校验值

```text
b5b6701ec3d4cac1b8a04d67902e36cb1aab3c7e9dcda263caf799366f4ed443  XLCodeUser-20261015-r1-fd2dc813.zip
```

## 反馈

请到[本仓库 Issues](https://github.com/xiehuangbaoa-del/XLCode-Releases/issues)提供版本、Windows 信息、复现步骤和脱敏截图／日志。**不要提交 API Key、完整 Bridge 连接地址或项目敏感内容。**
