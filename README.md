# bs-writer

`bs-writer` 是一个面向中文毕业设计、毕业论文、开题报告和答辩材料的写作 skill。它强调基于真实项目信息写作，避免编造数据、文献和实验结果，并尽量减少套话、宣传腔和明显的 AI 写作痕迹。

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
请根据上一步生成的“论证逻辑链条”，使用`$bs-writer`这个skill，在latex模板上撰写小节2.5的正文。
```

```text
请根据论文大纲，使用`$bs-writer`这个skill，在latex模板上撰写小节2.5的正文。
```

```text
请你使用`$bs-writer`这个skill重写下面这段文字：

[在这里粘贴需要重写的文字]
```
