# bs-writer

`bs-writer` 是一个面向中文毕业设计、毕业论文、开题报告和答辩材料的写作 skill。它包含了一份给ai使用的写作规范，能让ai直接生成更有人味且具有专业性的论文正文。
- 部分规范借鉴了humanizer-zh这个skill
- 可以根据自己的实际需求修改`SKILL.md`中的内容
- 本skill只负责规范ai的输出内容，它可以嵌入在任意工作流中，与其他skill配合使用。
- 如果不使用codex等AI agent工具，也可以将SKILL.md中的内容作为提示词输入进对话框来规范AI的生成内容

## 安装方式

复制下面的链接，然后让 Codex 或 Claude Code 帮你安装这个 skill：

```text
https://github.com/Evan007H/bs-writer
```

示例提示词：

```text
请帮我从这个 GitHub 仓库安装 skill：https://github.com/Evan007H/bs-writer
```

## 使用方式

在需要撰写或改写中文毕业论文内容时，在提示词中显式调用 `$bs-writer`。

示例：

```text
请根据论文大纲，使用$bs-writer，在latex模板上撰写小节1.1的正文。
```

```text
请你使用$bs-writer重写下面这段文字：

[在这里粘贴需要重写的文字]
```
