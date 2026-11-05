# 一缕烛光 · Codex Aesthetics

面向 Codex 的视觉与交互设计 skill。它提供网页视觉和交互的默认做法、按题材选择方向的参考卡，以及使用 Codex 工具检查实际渲染的流程。

## 安装

把整个 `skills/aesthetics/` 目录放入 Codex 的用户 skill 目录。已有同名 skill 时，先移走旧目录，再放入新版。默认安装路径是 `~/.codex/skills/aesthetics/`。

```sh
cp -R skills/aesthetics "${CODEX_HOME:-$HOME/.codex}/skills/"
```

在视觉任务中可以用 `$aesthetics` 显式调用。入口是 [SKILL.md](skills/aesthetics/SKILL.md)，配套参考文件随目录一同安装。
