<!-- markdownlint-disable MD033 MD041 -->

<div align="center">

中文 | [English](./CONTRIBUTING-en.md)

</div>

# 为 Project Hazelita 做贡献

感谢你愿意花时间参与 Project Hazelita。

贡献并不一定从一个 Pull Request 开始。一个有用的 bug 报告、一个经过思考的问题、一处文档改进、一份翻译、一个设计建议、一次代码审查，甚至一个在恰当时候提出的小想法，都可能让 Project Hazelita 变得更好。

如果你刚刚来到这里，也完全可以从很小的事情开始。

## 在开始之前

本文描述的是 Project Hazelita 各项目默认共用的贡献方式。Project Hazelita 下的不同项目可能使用不同的编程语言、工具、开发流程和发布方式。如果你正在参与的仓库中存在自己的 `CONTRIBUTING.md`、开发文档或其他项目专属说明，请优先遵循该项目自己的规则。

参与 Project Hazelita 项目时，也请遵守我们的[《行为准则》](./CODE_OF_CONDUCT.md)与[《Project Hazelita 社群公约》](https://github.com/ProjectHazelita/community-guidelines)。

## Issue

在创建新的 Issue 之前，建议先搜索已有 Issue，确认相同的问题或话题是否已经被报告或讨论。

### 报告 bug

如果你发现了一个 bug，请尽可能提供足够的信息，让其他人能够理解并复现问题。

有帮助的信息通常包括：

- 实际发生了什么；
- 你原本期望发生什么；
- 可以复现问题的步骤；
- 受影响的版本或 commit；
- 使用的操作系统、运行环境或相关依赖版本；
- 有助于定位问题的日志、截图或错误信息。

在公开日志、截图或配置内容之前，请记得移除密码、token、私人信息以及其他敏感数据。如果问题可能涉及安全漏洞，请不要创建公开 Issue，而应按照项目的 `SECURITY.md` 或 Project Hazelita 的默认[《安全政策》](https://github.com/ProjectHazelita/.github/blob/main/SECURITY.md)进行私下报告。

### 功能建议

我们欢迎功能建议。一个有帮助的功能建议通常应该先说明「你正在尝试解决什么问题」，而不仅仅是「你希望我们采用哪一种实现方式」。

请尽量描述具体的使用场景、现有功能或替代方案的不足，以及你期望达到的效果。如果有相关示例、截图或参考资料，也可以一并提供。你不需要先拿出完整的设计或实现方案；对于范围较大、可能影响架构或现有行为的建议，先讨论需求与取舍，再开始实现，通常更有帮助。

## Pull Request

Pull Request 应尽可能围绕一个明确的目的展开。在提交 Pull Request 之前，请根据项目实际情况尽量确认：

- 项目能够在你的环境中正常构建或运行；
- 已运行项目提供的相关测试、linter 和 formatter；
- 如果行为发生变化，对应文档也已经更新；
- 没有混入与本次修改无关的大规模格式化或重构；
- Pull Request 中说明了修改了什么，以及为什么需要这项修改。

通常来说，小而聚焦的 Pull Request 会比包含大量无关变化的提交更容易理解、审查和维护。

## Commit

Project Hazelita 通常采用 [约定式提交](https://www.conventionalcommits.org/zh-hans/v1.0.0/)，并在 commit message 的 type 后追加一个 [gitmoji](https://gitmoji.dev/) 以描述改动内容。我们遵照这样的 commit message 模板：

```text
<type>[optional scope]: <gitmoji> <description>

[optional body]

[optional footer(s)]
```

其中 `scope`、`body` 和 `footer(s)` 都是可选的。例如，这是一个符合我们要求的 commit message，它包含 `scope` 而不含 `body` 和 `footer(s)`：

```text
fix(docker): :bug: build memory images via buildx bake to grant host networking
```

不同项目可能采用不同的 commit 规范。如果 repo 没有规定特定格式，请遵循上文所述的规范，尽量让 commit message 简洁地说明这次修改的目的。

清晰的 Git 历史当然很好，但我们并不要求贡献者为了提交 Pull Request，在本地花费不合理的时间反复整理 commit。

根据项目的合并策略，维护者可能会在合并时进行 Squash、Rebase 或其他形式的 commit 整理。

## 代码审查

代码审查讨论的是贡献本身，而不是对贡献者的评价。

在审查其他人的工作时，请尽量：

- 说明为什么需要某项修改；
- 区分「必须修改的问题」与「建议、偏好或可选优化」；
- 对不熟悉项目或相关技术的贡献者保持耐心；
- 在合理范围内以善意理解他人的表达；
- 将批评集中在代码、设计、文档和具体行为上，而不是贡献者本人。

收到 review 意见时，可以提出问题或表达不同意见。如果不明白为什么需要修改某处，也可以直接询问 reviewer。

## AI 辅助贡献

Project Hazelita 欢迎负责任地使用 AI 辅助开发工具。我们接受使用 AI 工具编程、调试、编写文档、翻译、整理资料、研究或探索可能的实现方式；但提交贡献的人，仍然需要对自己的贡献负责。

在提交 AI 辅助生成或修改的内容之前，请尽合理努力确认：

- 你理解自己提交的代码或文字在做什么；
- 它确实解决了预期的问题；
- 在适当情况下已经进行了测试；
- 不包含明显错误、虚构内容或未经验证的假设；
- 没有意外包含密码、token、私人信息或其他秘密；
- 没有引入你无权使用或许可证不兼容的第三方代码、文字、图片或其他材料；
- 在 review 中，你能够解释、讨论并根据反馈修改这项贡献。

请不要直接提交大量未经检查的生成内容，并期待维护者替你完成全部验证工作。如果 AI 辅助在某项贡献中占据了较大比重，并且说明这一点有助于维护者理解内容的产生或验证过程，我们欢迎你在 Pull Request 中提供相关背景。

## 安全问题

请 **不要通过公开 Issue、Discussion 或 Pull Request 报告安全漏洞**。

如果你发现可能影响项目安全的问题，请查看对应仓库中的 `SECURITY.md`；如果项目没有提供自己的安全政策，则按照 Project Hazelita 的默认[《安全政策》](https://github.com/ProjectHazelita/.github/blob/main/SECURITY.md)进行报告。如果无法确定一个问题是否具有安全影响，优先采用私下报告通常更加稳妥。

## 许可证与第三方内容

向 Project Hazelita 的仓库贡献内容，即表示你同意你的贡献可以按照该仓库所采用的许可证进行分发，除非该项目另有明确说明。

请只提交你有权贡献的内容。如果贡献中包含来自第三方的代码、资源、文字或其他材料，请确认其许可证、署名要求及其他使用条件与目标项目兼容。不同的 Project Hazelita 项目可能采用不同的许可证，因此请以具体仓库中的许可证文件为准。

## 不知道从哪里开始？

没关系。你可以：

- 浏览现有 Issue；
- 寻找不够清晰或可以完善的文档；
- 提出或参与已有讨论；
- 帮忙测试项目；
- 分享一个尚未完全成形的想法；
- 或者加入 Project Hazelita 社群，在社群里交流。

---

<div align="center">

感谢你以一个 Issue、一份 patch、一个想法、一次 review 或一场讨论的方式，\
让 Project Hazelita 一点一点继续生长。🌱

</div>
