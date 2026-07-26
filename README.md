<p align="center"><img src="assets/brand/velaryn-og.png" alt="Velaryn" width="760"></p>

<h1 align="center">Velaryn</h1>
<p align="center"><strong>Knowledge, in motion.</strong></p>
<p align="center">面向 Android 平板的本地优先 AI 知识库与智能体工作台。</p>

<p align="center">
  <a href="https://velaryn.cn/">官方网站</a> ·
  <a href="https://velaryn.cn/download/">下载 Beta</a> ·
  <a href="https://velaryn.cn/docs/">使用文档</a> ·
  <a href="https://velaryn.cn/roadmap/">路线图</a> ·
  <a href="https://github.com/Nobel-BY/velaryn/issues">反馈问题</a>
</p>

> 当前版本：**v0.9.0 Beta** · Android 12+ · ARM64 · 横屏平板优先。Beta 阶段请为重要资料保留独立备份。

## Velaryn 是什么

Velaryn 不把资料当成聊天附件。它把文档阅读、知识组织、混合检索、可核查引用、关系图谱和智能体任务连接成一条可沉淀的工作流：

```text
导入资料 → 原版/结构化阅读 → 本地检索 → 核查来源
         → 智能体研究 → 带引用结果 → 确认后写回知识库
```

- **本地优先知识库**：原文件、索引、笔记和关系默认保留在 Android 设备。
- **PDF / DOCX 阅读**：原版分页与结构化文本并存，兼顾阅读、查找和引用。
- **混合检索**：关键词与语义召回协同；本地嵌入不可用时透明降级。
- **可核查引用**：关键结论可返回原始文档、页码或段落。
- **Markdown 知识网络**：双链、反链、未链接提及与知识图谱健康审计。
- **知识协同智能体**：多轮检索、冲突检查、任务进度与来源可见。
- **受控知识写入**：创建笔记、标签或关系前默认预览确认。
- **MCP 知识桥**：经过授权的外部 AI 客户端可检索平板知识库并创建笔记。

## 产品截图

| 原版文档阅读 | 混合检索与原文 |
| --- | --- |
| ![Velaryn DOCX 原版阅读](assets/screens/docx-reader.jpg) | ![Velaryn 混合检索](assets/screens/hybrid-search.jpg) |

![Velaryn 知识图谱](assets/screens/knowledge-graph.jpg)

## 快速开始

1. 从 [velaryn.cn/download](https://velaryn.cn/download/) 下载官方 APK。
2. 安装前核对官网提供的 SHA-256。
3. 创建知识库，先导入 5–20 份 PDF、DOCX、Markdown 或 TXT。
4. 在设置中配置你自己的模型 API。
5. 从精确搜索、引用跳转和选定资料研究开始试用。

更完整步骤见 [GETTING_STARTED.md](docs/GETTING_STARTED.md)。

## 数据边界

- 知识库检索在平板本地完成。
- 调用云端模型 API 时，只发送当前任务需要的上下文片段。
- 智能体写入默认需要确认；自动写入必须由用户主动开启。
- 密钥、安全令牌和私人资料不应出现在公开 Issue 中。

详见 [隐私与安全说明](docs/PRIVACY_AND_SECURITY.md) 与官网 [安全页](https://velaryn.cn/security/)。

## 仓库范围

这是 Velaryn 的**公开产品仓库**，用于：

- 产品介绍与公开文档；
- Beta 版本进展和已知边界；
- 缺陷报告与功能建议；
- 官方网站和下载入口的可信关联。

本仓库不等同于应用完整源代码仓库，也不表示仓库内所有内容均以开源许可证发布。参见 [REPOSITORY_SCOPE.md](REPOSITORY_SCOPE.md)。

## 来源与致谢

Velaryn 基于 [Mintplex-Labs/anythingllm-mobile](https://github.com/Mintplex-Labs/anythingllm-mobile)（MIT License）进行深度定制。原始版权和 MIT 许可文本见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。AnythingLLM 与 Mintplex Labs 不对 Velaryn 的定制版本提供背书或支持。

## 参与反馈

- 遇到缺陷：使用 [Bug report](https://github.com/Nobel-BY/velaryn/issues/new?template=bug_report.yml)
- 提交建议：使用 [Feature request](https://github.com/Nobel-BY/velaryn/issues/new?template=feature_request.yml)
- 安全问题：请先阅读 [SECURITY.md](SECURITY.md)，不要公开漏洞利用细节。

---

<p align="center">© 2026 Velaryn · Public Beta</p>
