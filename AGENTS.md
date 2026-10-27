# AGENTS.md · STUIDNULL 团队规则

负责人：王嘉诚（组长）。AI 每次对话都要遵守下面的规则。

- 基准文档是 `docs/PRD.md`。不清楚就提问，不要编造。
- 只用 HTML · CSS · JS。禁止构建工具和框架。
- 每个人只在 `characters/[我的id]/` 里工作，文件夹之外只能读取。
- 共同区域（`index.html`、`css/`、`js/`、`data/`、`characters/_template/`）只有负责人可以修改。
- 颜色只用 `css/common.css` 的令牌；文案一律写成 `{"zh": "…", "ko": "…"}`。
- 图片放在各自的 `assets/`，用相对路径 `./assets/`，文件名全部小写英文加连字符。
- 手机优先；动画只用 transform / opacity，支持 prefers-reduced-motion。
- 动手前先给计划；做完列出改动的文件和行数，文件行数突然减少要先停下。
- 一次只做一件事，做好就提交：`[w周次-id-标签] 说明`，例如 `[w1-naitu-about] 添加介绍标签页`。
- 用到的提示词记到 `docs/prompt-log/[我的id].md`。
