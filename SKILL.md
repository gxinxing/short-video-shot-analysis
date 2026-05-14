---
name: short-video-shot-analysis
description: analyze short dramas, short videos, ads, reels, tiktoks, douyin videos, video scripts, subtitles, screenshots, or shot descriptions. Use when the user asks to break down a video, perform 拉片, analyze hooks, pacing, story structure, shots, editing, emotional curve, viral mechanics, or convert a video into reusable creative templates.
---

# Short Video Shot Analysis

## Core behavior

Analyze short-form videos and short dramas through structure, hook, emotion, pacing, shots, editing, and reusable creative patterns.

If the user provides only a link and no accessible content, ask for subtitles, screenshots, transcript, shot list, or a brief description.

Do not only summarize the content. Always explain how the video works.

## Default workflow

1. **Identify the video type:**
   - short drama (短剧)
   - plot short video (剧情短视频)
   - product video (产品视频)
   - knowledge video (知识视频)
   - talking head / 口播 video
   - brand ad (品牌广告)
   - vlog/lifestyle
   - meme/skit (段子/小品)

2. **Extract the structure:**
   - opening hook (前3秒钩子)
   - context setup (背景铺垫)
   - conflict (冲突)
   - escalation (升级/加压)
   - reversal (反转)
   - payoff (爽点/释放)
   - call to action or comment trigger (行动号召或评论引导)

3. **Analyze by layers:**
   - narrative layer (叙事层)
   - emotional layer (情绪层)
   - visual layer (视觉层)
   - editing rhythm (剪辑节奏)
   - subtitle/copy layer (字幕/文案层)
   - platform/viral layer (平台/传播层)

4. **Produce a practical output:**
   - standard 拉片 report (标准拉片报告)
   - shot table (分镜表)
   - viral mechanism analysis (爆款机制分析)
   - reusable script template (可复用脚本模板)
   - improvement suggestions (优化建议)

## Important principles

- Prefer concrete observations over vague praise.
- Separate "what happens" from "why it works."
- Always identify the first 3-second hook when possible.
- Always look for conflict, information gap, reversal, emotional payoff, and retention design.
- For short dramas, emphasize character relation, stakes, conflict, 爽点, reversal, and episode-ending hook.
- For product videos, emphasize problem-solution, trust proof, desire stimulation, objection handling, and conversion trigger.
- For knowledge videos, emphasize curiosity gap, information density, structure clarity, and memorability.

## Output mode selection

Default to the **standard 拉片 report** unless the user asks for a specific format.

Use these cues to select output mode:

| User request pattern | Output mode |
|---|---|
| "帮我拉片" / "分析一下这个视频" / "拆解一下" | Standard 拉片报告 |
| "为什么能爆" / "为什么火了" / "爆款机制" | 爆款机制分析 |
| "分镜" / "拍摄" / "镜头" / "怎么拍" | 分镜拆解 |
| "模板" / "公式" / "套路" / "复用" | 创作模板提炼 |
| "优化" / "改进" / "修改建议" / "我的脚本" | 优化建议 |

## Response structure

1. Start with a brief summary of what the video is doing (1-2 sentences).
2. Deliver the requested analysis using the appropriate output template.
3. End with 2-3 actionable takeaways the user can apply.

## When content is insufficient

If the user only provides a link or title without accessible content:

> 我需要更多内容才能帮你拉片。请提供以下任一：
> - 视频字幕/文案
> - 分镜截图或逐帧图
> - 视频内容描述（画面+台词）
> - 脚本文本

Then ask what specific aspect they want to analyze once content is provided.

## Reference files

- @references/analysis-framework.md - Core analysis framework and dimensions
- @references/hook-patterns.md - Hook types and patterns library
- @references/short-drama-patterns.md - Short drama specific patterns
- @references/output-templates.md - All output format templates
- @references/scoring-rubric.md - Scoring criteria for evaluation
