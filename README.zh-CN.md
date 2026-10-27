# Everforest · Prism

**晨光停在林间，暮色落于苔石。让每一段思绪，都寻得一抹安静的绿。**

[![发行附件下载量](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-everforest-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-everforest-prism/releases)

[English](README.md) · [下载 theme.json](https://github.com/EllisMorrow/tine-theme-everforest-prism/releases/latest/download/theme.json)

Everforest 温润的浅色与深色 medium 色板汇于一套主题，以柔和的林间底色和克制的自然点缀，铺开明暗两面。

### 深色模式

![Everforest · Prism 深色模式实拍](docs/everforest-dark.png)

### 浅色模式

![Everforest · Prism 浅色模式实拍](docs/everforest-light.png)

*用户测试后提供的 Windows 实机截图，两套配色均实际包含在同一个主题包中。*

## 安装

1. 下载 [theme.json](https://github.com/EllisMorrow/tine-theme-everforest-prism/releases/latest/download/theme.json)。
2. 在 Tine 打开 **设置 → 外观 → 主题包 → 选择 theme.json**，选择下载的文件。
3. 点击 **使用颜色**，选择 **浅色、深色或跟随系统**。

需要主题 API **0.2** 支持。原有 `logseq/custom.css` 和设备强调色可能影响效果；主题只负责 API 支持的颜色，不包含额外字体、布局或任务标记样式。

## 配色

| 角色 | 浅色 | 深色 |
| --- | --- | --- |
| 主背景 | `#FDF6E3` | `#2D353B` |
| 侧栏 | `#F4F0D9` | `#232A2E` |
| 正文 | `#5C6A72` | `#D3C6AA` |
| 标题 | `#5C6A72` | `#D3C6AA` |
| 强调色 | `#8DA101` | `#A7C080` |
| 链接 | `#286983` | `#7FBBB3` |
| 标签 | `#5D7410` | `#A7C080` |
| 高亮底色 | `#FAEDCD` | `#4D4C43` |

## 验证情况

通过官方主题格式检查；浏览器样例检查了两套完整变量、模式切换及指定颜色组合。用户提供了上方 Windows 明暗实机截图，展示公开欢迎页面上的标题、正文、层级、链接、标签、行内代码和引用区域。高亮、选中操作、设置状态和其它平台未由这些截图覆盖，不据此宣称全部路径均已验证。

## 来源与边界

基于 [Everforest Light / Dark Medium](https://github.com/sainnhe/everforest)，固定版本 `85a86eb62409e3ec88713bff3d1b9d7374e112e4`，采用 MIT 许可并保留 [原始声明](LICENSE)。两种模式均采用 Codex 可选的 Everforest Light 与 Dark 系列，并依据官方默认 medium 对比度色板映射。Tine 背景角色为独立适配；文档所列浅色文字和标签调整用于提升本包声明背景上的对比度。

独立社区适配由 EllisMorrow 完成，使用 AI 辅助开发。不分发 Codex 程序代码、标志或附带资源，不代表相关项目或 OpenAI 的官方产品，也不承诺与 Codex 像素级一致。具体映射和验证边界见 [适配说明](docs/adaptation.md)。

顶部徽标统计 GitHub Release 附件累计下载量，不代表安装人数。可在本仓库反馈问题，附版本、系统、模式及不包含私人内容的截图。

