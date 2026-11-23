# AI 零基础入门

一个面向 AI 初学者的中文 Codex Skill。用日常例子讲清 AI 概念，并生成一页可以离线阅读的 HTML 小课。你可以用这个仓库练习从 GitHub 下载文件、安装 Skill，再生成自己的第一节小课。

适合问「什么是 Skill、大模型和 MCP？」「什么是 Vibe Coding？」「Token 是什么？」。每节课先给出一句简明解释，再用熟悉的场景拆解概念。根据主题，可以加入对照卡片、演示或可展开的小练习。

## 1. 从 GitHub 下载

1. 在仓库首页点击绿色 **Code** 按钮，再点 **Download ZIP**。
2. 打开「下载」文件夹，解压下载好的 ZIP。双击里面的 `vibe-coding-lesson.html`，可以先看看生成的小课长什么样。
3. 在解压目录里找到名为 `ai-first-steps` 的子文件夹。打开它会看到 `SKILL.md`，以及 `assets` 和 `agents` 两个子文件夹。

## 2. 安装到 AI Agent

1. 确认你使用的 AI Agent 支持安装基于 `SKILL.md` 的 Skills。
2. 按该工具的方式导入整个 `ai-first-steps` 文件夹。如果工具通过本地目录加载 Skills，就把文件夹复制到它指定的技能目录。
3. 在工具里确认能找到「AI 零基础入门」或 `ai-first-steps`，就可以开始试用了。

## 3. 生成你的第一节小课

以 Codex 为例，选一个本地工作区，新建对话，然后输入这句话。

> 用 $ai-first-steps 讲讲什么是 Vibe Coding，生成一页 HTML 小课。用做乘法练习网页举例，并放一道可以点击「显示答案」的口算题。

生成后点击对话里的 HTML 文件链接，或在访达中找到这个文件并用浏览器打开。如果 Codex 里暂时找不到 Skill，可以重新启动 Codex 后再试。

[Codex Skills 官方说明](https://learn.chatgpt.com/docs/build-skills)

## 样例

下载 HTML 文件后，用浏览器打开即可。

- [第一次学 AI，先懂这三个词](ai-first-steps-lesson.html) 用图书馆查书的例子解释 Skill、大模型和 MCP。
- [什么是 Vibe Coding？](vibe-coding-lesson.html) 用做口算练习页的例子解释如何让 AI 边试边改，并带有可点击的演示。

讲解规则见 [SKILL.md](ai-first-steps/SKILL.md)，可复用的版式见 [HTML 模板](ai-first-steps/assets/lesson-template.html)。

## 许可证

[MIT](LICENSE)
