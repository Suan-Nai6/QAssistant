<div align="center">
    <h1> QAssistant </h1>

[![GitHub release](https://img.shields.io/github/release/Suan-Nai6/QAssistant.svg)](https://github.com/Suan-Nai6/QAssistant/releases/latest)
[![main](https://github.com/Suan-Nai6/QAssistant/actions/workflows/push_ci.yml/badge.svg)](https://github.com/Suan-Nai6/QAssistant/actions/workflows/push_ci.yml)
[![QQ](https://img.shields.io/static/v1?label=QQ群&logo=tencentqq&message=Channel&color=0088cc)](https://t.me/QAuxiliary)
[![issues](https://img.shields.io/github/issues/Suan-Nai6/QAssistant?logo=github)](https://github.com/Suan-Nai6/QAssistant/issues)

</div>

---

QAssistant 是一个基于 QAuxiliary 的开源 Xposed 模块

## 使用方法

激活本模块后，在 QQ 或者 TIM 自带设置中点击 **QAssistant** 即可进入设置页面

- Android >= 7.0
- QQ >= 8.2.0, TIM >= 2.2.0, QQLite >= 4.0, QQ HD >= 5.9.3

## 一切开发旨在学习，请勿用于非法用途

- 本项目保证永久开源，欢迎提交 PR，但是请不要提交用于非法用途的功能。
- 如果某功能被大量运用于非法用途或严重侵害插件使用者权益，那么该功能将会被移除。
- 本模块完全免费开源，没有任何收费，请勿二次贩卖。
- 鉴于项目的特殊性，开发团队可能在任何时间**停止更新**或**删除项目**

### 许可证

- [EULA](https://github.com/qwq233/License/blob/master/v2/LICENSE.md)

```
版权所有©2022 gao_cai_sheng <qwq233@qwq2333.top, qwq2333.top>

允许在遵守 CC BY-NC-SA 4.0 协议的同时，复制和分发此协议文档的逐字记录副本，
且允许对其进行更改，但必须保留其版权信息与原作者。如果您提出申请特殊权限，协议
作者可在其口头或书面授予任何人任何但不包括以盈利为目的的使用本协议的权利。

请务必仔细阅读和理解通用许可协议书中规定的所有权利和限制。在使用前，您需要仔细
阅读并决定接受或不接受本协议的条款。除非或直至您接受本协议的条款，否则本作品及
其相关副本、相关程序代码或相关资源不得在您的任何终端上下载、安装或使用。

您一旦下载、使用本作品及其相关副本、相关程序代码或相关资源，即表示您同意接受本
协议各项条款的约束。如您不同意本协议中的条款，您则应当立即删除本作品、附属资源
及其相关源代码。

本作品权利只许可使用，而不出售。
```

## 不会支持的功能

- 抢红包及其他金钱相关功能
- 群发消息

## 编译

1. 安装 git, ccache(可选), cmake, SDK 和 NDK, 版本参考 [Version.kt](build-logic/convention/src/main/kotlin/Version.kt);
2. 将本仓库 clone 至本地，本仓库含有 git submodule 所以请使用 git clone 而不是下载源代码压缩包；
3. 拉取 MMKV, DexKit 等子模块, `git submodule init && git submodule update --recursive`;
4. 使用 Gradle 编译安装包。

---

## 赞助

- 由于项目的特殊性，我们不接受任何形式的捐赠，但是我们希望有更多的人能够参与本项目的开发

## [通用许可协议](https://github.com/qwq233/License/blob/master/v2/LICENSE.md)

![备选案文]（https://repobeats.axiom.co/api/embed/d049a8a977ea00c45646218fdc903d0e8e2ab958.svg“Repobeats 分析图像”）
![star] (https://star-history.com/#Suan-Nai6/QAssistant&Date)
