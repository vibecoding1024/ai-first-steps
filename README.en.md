# AI First Steps · Chinese-Language Agent Skill

[简体中文](README.md)

AI First Steps explains AI concepts such as large language models, MCP, and vibe coding through everyday examples. It turns answers into self-contained HTML lessons you can read offline. The lessons are written in Simplified Chinese by default.

## Sample lessons

Download the HTML files and open them in a browser.

- [What are Skills, large models, and MCP?](ai-first-steps-lesson.html) See how each one helps an AI assistant find a book in a library.
- [What is vibe coding?](vibe-coding-lesson.html) See how you can ask AI to build a multiplication practice page and refine it after trying it out.

## 1. Download from GitHub

1. On the repository homepage, click **Code**, then **Download ZIP**.
2. Unzip the download. Open `vibe-coding-lesson.html` in a browser to see a sample lesson.
3. Inside the extracted directory, find the `ai-first-steps` folder. It contains `SKILL.md` and the `assets` and `agents` subfolders.

## 2. Install in an AI agent

1. Check that your AI agent supports skills defined by a `SKILL.md` file.
2. Import the entire `ai-first-steps` folder using your agent's installation method. If it loads skills from a local directory, copy the folder to the location specified by your agent.
3. Look for `ai-first-steps` or `AI 零基础入门` in the agent's available skills.

## 3. Generate your first lesson

In Codex, open a local workspace, start a new chat, and try this prompt.

> Use $ai-first-steps to explain vibe coding in an HTML lesson. Use a multiplication practice page as the example and include one question with a button that reveals the answer.

Open the generated HTML file from the chat or your workspace. If the skill doesn't appear after installation, restart Codex and try again.

You can also ask “What is a token?” or “How does MCP help an AI assistant look up information?”

See [SKILL.md](ai-first-steps/SKILL.md) for the lesson-writing instructions and the [HTML template](ai-first-steps/assets/lesson-template.html) for the layout.

## License

[MIT](LICENSE)
