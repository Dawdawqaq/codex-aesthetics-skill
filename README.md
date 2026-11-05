# 一缕烛光 · Codex Aesthetics

面向 Codex 的视觉与交互设计 skill，适用于网页、界面、海报、幻灯片等需要视觉判断的任务。

## 三层结构

| 层 | 作用 |
|---|---|
| 保底手艺 | 用[网页视觉指南](skills/aesthetics/references/floor-web-ui.md)建立排版、间距和配色。可交互页面再用[交互指南](skills/aesthetics/references/floor-interaction.md)补齐状态、反馈和动效。 |
| 方向卡 | 当题材还没有明确的视觉方向时，从[方向卡](skills/aesthetics/references/directions.md)选一个起点，再融入题材本身的具体元素。 |
| 烛光 | [SKILL.md](skills/aesthetics/SKILL.md)指导如何确定视觉焦点、取舍元素，并用 [Codex 渲染指南](skills/aesthetics/references/codex-rendering.md)检查实际效果。 |

评审或优化已有作品时，使用[审计指南](skills/aesthetics/references/audit.md)提取项目自己的设计规则，按影响分级报告问题，并在用户要求时修复。

## 安装

在仓库根目录运行以下命令。已有同名 skill 时，先移走旧目录，再安装新版。默认安装路径是 `~/.codex/skills/aesthetics/`。

```sh
skill_dir="${CODEX_HOME:-$HOME/.codex}/skills"
mkdir -p "$skill_dir" && cp -R skills/aesthetics "$skill_dir/"
```

## 调用示例

在 Codex 对话中用 `$aesthetics` 显式调用，然后描述要做的作品或要解决的问题。

```text
$aesthetics 给社区图书馆做一个活动报名页。参考老式借书卡的编号和横线，让报名按钮成为首屏焦点。完成后检查桌面和手机布局。
```

```text
$aesthetics 优化现有的搜索结果页，沿用项目的组件和配色。补齐加载、空结果和错误重试状态，再用键盘走一遍搜索流程。
```
