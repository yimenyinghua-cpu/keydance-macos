# 敲一敲（Keydance）

一个 macOS 本地输入活动仪表：把键盘动作、点击、光标移动和可选的 Agent 编辑事实整理成可回看的统计与热力图。

[访问官网](https://keydance.app/) · [在 Mac App Store 查看](https://apps.apple.com/cn/app/%E6%95%B2%E4%B8%80%E6%95%B2/id6797265723?mt=12) · [支持](https://keydance.app/support) · [隐私政策](https://keydance.app/privacy)

![敲一敲键盘热力图示意](keyboard-heat-real-v2-tight.webp)

## 敲一敲是什么

敲一敲（Keydance）是一款 macOS 本地输入活动仪表，常驻菜单栏，帮助你回看今天或历史日期中的键盘、点击和光标活动。

它记录的是经过聚合的活动事实，不是你输入的内容。键盘动作不等于字数、产出或效率；光标移动是基于屏幕参数的投影距离估算。

## 核心能力

- 键盘热力图：用可视化方式回看不同按键的活动分布。
- 今日节奏：按最近 24 小时的活动节奏回看高低起伏。
- 屏幕热力：区分光标停留与点击位置，观察屏幕上的活动分布。
- 今日与历史：在同一天事实的基础上查看摘要、统计和趋势。
- 可选 Agent 聚合：在你主动连接支持的 Agent 后，查看日级编辑事实；不读取或保存原始会话。

![敲一敲今日节奏示意](today-rhythm-real-v4.webp)

![敲一敲屏幕热力示意](screen-heat-real-v2-clean.webp)

## Input Monitoring 与隐私

为了观察系统范围的输入活动，Keydance 使用 macOS 的 Input Monitoring 权限和只读的 `CGEventTap`。它不会拦截或修改键盘输入，也不使用跨 App Accessibility 来读取其他应用内容。

核心记录、历史和统计默认保存在你的 Mac 上。Keydance 不保存或上传：

- 正文、剪贴板内容或截图；
- 应用、窗口、URL 或文件路径；
- raw keyCode 顺序、逐事件时间／顺序或原始坐标轨迹；
- Agent 原始会话、账号、密码或密钥。

Secure Input 出现时，键盘、点击和光标聚合会暂停。全球排行榜是独立的自愿参加功能：只有在你明确同意参加后，才上传最小的日级聚合；不参加排行榜不会影响本机核心记录。

## 适合谁

- 想把键盘与鼠标活动看得更直观的人；
- 想回看输入节奏、按键分布和历史变化的人；
- 关注本机保存和输入隐私边界的 Mac 用户；
- 使用 AI Coding 工具，并希望只查看日级编辑聚合的人。

## 获取 Keydance

- [官网](https://keydance.app/)
- [Mac App Store](https://apps.apple.com/cn/app/%E6%95%B2%E4%B8%80%E6%95%B2/id6797265723?mt=12)
- [隐私政策](https://keydance.app/privacy)
- [支持与帮助](https://keydance.app/support)
- [全球排行榜](https://keydance.app/ranking/)

## 常见问题

### Keydance 会记录我输入的文字吗？

不会。Keydance 只保留用于统计的聚合数据，不保存正文、剪贴板、截图、应用或窗口内容。

### 为什么需要 Input Monitoring？

它用于观察系统范围的键盘、点击和光标活动。Keydance 使用只读事件观察，不拦截或修改输入；你可以在 macOS 系统设置中管理权限。

### Keydance 会自动把数据上传到云端吗？

本机核心记录默认留在 Mac 上。排行榜是独立的 opt-in 功能，只有你明确参加后才会上传最小日级聚合。

### 这是开源项目吗？

不是。本仓库是 Keydance（敲一敲）的官方产品介绍与公开链接页面，不是应用源码镜像；应用源码未在此仓库发布，本仓库不授予代码的开源使用许可。

错别字、失效链接或文档反馈可以发送至 [support@keydance.app](mailto:support@keydance.app)。本仓库不接受代码贡献。

---

## English

### What is Keydance?

Keydance is a local macOS keyboard and mouse activity tracker. It turns keyboard actions, clicks, cursor movement, and optional daily Agent editing aggregates into visual statistics you can review over time.

It measures aggregated activity, not what you type. Keyboard actions are not presented as word count, productivity, or value, and cursor movement is an estimated screen-projected distance.

### Core features

- Keyboard heatmap for visual key-activity distribution.
- A recent-24-hour rhythm view for activity patterns.
- Screen heatmap separating cursor dwell from click locations.
- Today and historical views based on the same local-day facts.
- Optional daily Agent editing aggregates after you explicitly connect a supported Agent.

### Input Monitoring and privacy

Keydance uses macOS Input Monitoring and a read-only `CGEventTap` to observe system-wide input activity. It does not intercept or modify keyboard input, and it does not use cross-app Accessibility to read application content.

Core records, history, and statistics stay on your Mac by default. Keydance does not store or upload typed text, clipboard contents, screenshots, app or window details, URLs, file paths, raw key event sequences, raw cursor trails, Agent transcripts, accounts, passwords, or keys.

When Secure Input is active, keyboard, click, and cursor aggregation pauses. The global leaderboard is a separate opt-in feature and does not affect local tracking when you do not join.

### Get Keydance

- [Website](https://keydance.app/)
- [Mac App Store](https://apps.apple.com/cn/app/%E6%95%B2%E4%B8%80%E6%95%B2/id6797265723?mt=12)
- [Privacy policy](https://keydance.app/privacy)
- [Support](https://keydance.app/support)
- [Global leaderboard](https://keydance.app/ranking/)

### Is Keydance open source?

No. This is the official Keydance product-information repository, not a source-code mirror. The application source code is not published here, and this repository does not grant an open-source license for the application code.

For typo, broken-link, or documentation feedback, contact [support@keydance.app](mailto:support@keydance.app). Code contributions are not accepted here.

© 2026 董娜 · Keydance
