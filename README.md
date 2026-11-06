# Lindy & Lin — Tavo Plugin Suite

A collection of plugins for [Tavo](https://www.tavoai.dev/), an AI role-play front-end, developed by **Lin**. These plugins extend Tavo with beautification regex management, AI-assisted character-card generation, mask management, and chronicle-based long-term memory for role-play agents.

> 配套 @Lin 发布的主题（状态栏 / 数值条 / 折叠栏）使用效果更佳。

## Plugins

| File | Plugin | Version | What it does |
|---|---|---|---|
| `Lindy V1.1.6-gre.tpg` | **Lindy** | 1.1.6 | Regex manager for status panels, value bars, and collapsible sections. Saves tokens vs. raw CSS output. |
| `linmask-v0.2.8.tpg` | **LinMask** | 0.2.8 | Mask manager: sorting, notes, Tavo import/export. |
| `LinChar-0.1.9.tpg` | **LinChar** | 0.1.9 | API-connected AI card writer: turns rough settings into structured character cards and world books via built-in templates. |
| `Lin世界档案 V1.2.0.tpg` | **Lin World Archive** | 1.2.0 | Auto-captures new side characters and concepts into the world book — an active memory & cognition-update mechanism. |
| `Lin记忆管家 V1.5.0.tpg` | **Lin Memory Manager** | 1.5.0 | Chronicle-based long-term memory: day-level keyword entries, consolidated into resident entries every ten days. |

## Install

1. Download the `.tpg` file you need.
2. In Tavo, import the plugin file (插件管理 → 导入).
3. Pair with a Lin theme for the full beautification pipeline.

## Notes

- Companion desktop/mobile editors: see the [lindy-suite](https://github.com/sssylttt07/lindy-suite) repository.

## Credits & Attribution

- **Preset collapsible sections** — 本套件（Lindy、Lindy Pro、Lindy Air、LinWork Pro）中的四个预设折叠栏，取自 Rubii 社区常见的大众折叠栏，由本作者进行整合与修改；骰子世界观系列折叠栏为本项目原创设计。
- **Memory design** — 记忆插件与记忆折叠栏的设计灵感来源于 Rubii 社区常见的多个记忆整理指令，在此基础上做了归纳整理、大幅规则修改与编年史化调整。
- **Character card templates** — LinWork Pro 与 LinChar 中的角色卡模板，基于 Tavo 社区分享的通用模板，本作者加工了九型人格的性格设计部分，并对条目做了拆分（如外貌等）。
- 以上内容如有原创作者，欢迎联系本作者进行致谢与署名。

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for what changed between builds.

## License

Released under the MIT License.
