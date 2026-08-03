# HTML Editor Mode

[![English](https://img.shields.io/badge/Language-English-1f6feb?style=flat-square)](README.en.md)

为现有 HTML 页面加入轻量、优雅的可视化编辑模式，同时保留原有设计、响应式布局、动画与交互逻辑。

## 功能

- 直接编辑标题、正文、标签与卡片文字
- 调整所选文字的字号和颜色
- 替换图片 URL、修改全局颜色变量
- 拖动独立文本块或组件微调位置
- 导出包含当前修改内容的 HTML 文件
- 使用低调的图标式编辑菜单，避免遮挡页面内容

## 使用方式

将 `html-editor-mode` 文件夹复制到你的 AI 编程 Agent 所使用的 skills / instructions 目录中。

支持 `SKILL.md` 约定的 Agent 可直接读取其中的工作流；具体安装位置请遵循所用 Agent 平台的文档。以 Codex 为例：

```text
~/.codex/skills/html-editor-mode/
```

然后在任务中说明：

```text
Use $html-editor-mode to add a lightweight editing mode to this HTML page.
```

## 项目结构

```text
html-editor-mode/
├── SKILL.md
└── agents/openai.yaml
```

`SKILL.md` 是核心工作流文件。`agents/openai.yaml` 是可选的 OpenAI / Codex 界面元数据；不支持该文件的 Agent 可以安全忽略它。
