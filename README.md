# lovstudio-visual-clone

![Version](https://img.shields.io/badge/version-1.0.1-CC785C) ![Pro](https://img.shields.io/badge/Pro-blueviolet)

从参考图中提取设计要素，生成可复刻同款风格的指令。

Part of [lovstudio/skills](https://github.com/lovstudio/skills) — by [lovstudio.ai](https://lovstudio.ai)

## What you get

看到一张喜欢的海报、Banner、UI 截图，想要"做一个一样风格的"，但说不清到底好在哪？

把图丢进来，得到两份可直接使用的产物：

- **设计 DNA 报告** — 拆解出色彩、字体、版式、纹理、节奏、情绪等 8 个维度的可量化描述
- **复刻指令** — 一段可粘贴到任何下游工具（AI 出图、设计师 brief、品牌手册）里的自包含指令，让别人或别的工具能直接复刻这个风格

## Install

```bash
npx skills add lovstudio/skills --skill lovstudio-visual-clone -g -y
```

或通过 Claude Code 原生市场：

```
/plugin marketplace add lovstudio/skills
/plugin install visual-clone@lovstudio
```

首次使用需激活 license：

```bash
uvx lovstudio-skill-helper activate <your-license-key>
```

还没有 key？前往 [lovstudio.ai](https://lovstudio.ai) 购买。

## Usage

把参考图发给 Claude Code，并说出意图：

- "复刻这个风格"
- "提取设计要素"
- "analyze this design"
- `/lovstudio-visual-clone`

Skill 会问清楚你想把这个风格用在什么场景（海报？落地页？PPT？），然后输出设计 DNA 和复刻指令。

## License

Commercial — All rights reserved.
