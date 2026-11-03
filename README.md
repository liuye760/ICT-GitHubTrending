# ICT GitHub Trending 中文日报

每日 GitHub Trending 的中文解读与可视化看板，内容涵盖整体趋势分析、重点项目拆解与风险提示。

## 最新一期 · 2026-11-03

- 中文日报：[reports/2026-11-03-daily.md](reports/2026-11-03-daily.md)
- 可视化看板：[dashboard/index.html](dashboard/index.html)
- 当日快照：[dashboard/history/2026-11-03.html](dashboard/history/2026-11-03.html)

### 今日趋势

社区正把智能体从聊天式能力模块，推向具备执行闭环、工具调用、记忆和多阶段编排的工业化系统；与此同时，模型接入与推理基础设施继续平台化。

### 今日 Top 5

| 排名 | 项目 | Star | 今日新增 |
| --- | --- | --- | --- |
| 1 | [vercel-labs/agent-desktop](https://github.com/vercel-labs/agent-desktop) | 11,034 | +2,275 |
| 2 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 111,115 | +1,803 |
| 3 | [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 93,471 | +706 |
| 4 | [hyprwm/Hyprland](https://github.com/hyprwm/Hyprland) | 40,111 | +509 |
| 5 | [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | 33,964 | +1,379 |

## 在线访问

仓库启用 GitHub Pages 或 GitCode Pages，并将发布目录设为仓库根目录后，可通过 `/dashboard/` 访问看板；`reports/` 下为 Markdown 日报原文。

## 目录结构

```text
.
├── dashboard/
│   ├── index.html          # 最新一期看板
│   ├── styles.css          # 看板样式
│   ├── assets/             # 图标与背景图
│   └── history/            # 历史快照（按日期归档）
└── reports/
    └── 2026-11-03-daily.md # 中文日报
```

## 更新方式

在分析工程根目录执行：

```bash
node scripts/run-analysis.mjs --period daily
```

将 `reports/github-trending/2026-11-03-daily.md` 与 `reports/github-trending/dashboard/` 同步至本仓库后提交即可。