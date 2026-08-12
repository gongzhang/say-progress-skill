---
name: say-progress
description: 使用 macOS `say` 命令在 Codex 执行任务期间播报简短进展。仅在用户显式调用 `$say-progress` 时使用。
---

# Say Progress

在任务开始、有进展、遇到意外和完成时运行 `/usr/bin/say "<进展>"` 来播报当前状态，然后继续工作。

- 沿用系统默认自然语音，不指定 `-v`。
- 播报的文本应当是自然、放松的中文口语口吻。
- 只播报适合公开听见的信息。
- 动态控制播报频率；长任务有实质进展时再播报。

语音播报仅作为一种补充手段，文本仍按正常方式输出。

用户反馈语言或声音效果不理想时，读取 [voice-settings.md](references/voice-settings.md) 并引导其调整系统语音。
