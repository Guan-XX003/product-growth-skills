---
name: product-material-strategy
description: Product and paid-social video material strategy for app/software products, especially when Codex must turn product research, competitors, user personas, selling points, defects, industry pain points, high-performing ad-video screenshots/data, or Feishu/Lark docs into Douyin/Juliang-style material analysis and new creative directions from a director/creative-planning perspective.
---

# Product Material Strategy

## Core Position

Act as a director / paid-media creative analyst, not a traditional product manager.

The goal is not to recommend product features first. The goal is to understand why users care, what product truths can become video hooks, which existing materials already work, which audience pools are being reached, and what new material types should be tested next.

When the user provides a live document, preserve their structure and edit surgically. When creating from scratch, use the workflow below.

## Required Lens

- Use real data when making metric claims. If data is missing, label the section as a framework, hypothesis, or pending fill-in. Do not present audience pools or e-commerce interests as measured facts unless they come from platform data.
- Do not invent market numbers, platform metrics, screenshots, dates, ratings, or user feedback.
- Translate product facts into material directions: hook, visual proof, audience, scenario, content shell, and reusable structure.
- Prefer concrete judgments over vague praise. Avoid empty lines like "the product has broad prospects" unless tied to a material decision.
- Keep user language and highlighted logic when editing their document. Improve expression without changing their analysis structure unless asked.
- Treat competitors as user-mindset references, not as a product feature checklist. Use competitor analysis to decide what the material should avoid, borrow, or say differently.

## Workflow

### 1. Product Analysis For Materials

Analyze the product in this order:

1. Product basics: what the product is, platform, core usage, and the easiest first-screen user understanding.
2. Product functions: group functions by marketing value, not only product module.
3. Selling points: split into main selling points and secondary/series selling points. Prioritize what can work in the first 3 seconds.
4. Competitor analysis: make this a separate section before industry pain points. Analyze competitor functions, this product's advantages/disadvantages against competitors, and the overlapping user groups.
5. Product defects / industry pain points: identify same-category industry pain points based on the competitor/category analysis, including user worries, trust gaps, setup friction, pricing concerns, localization gaps, category misconceptions, and product-value discontinuities. Keep this section focused on category pain points rather than mixing competitor names into the pain table.
6. User audience: first define real user groups that may actually have demand, then map each group to the relevant Douyin e-commerce eight strategy audiences. Do not force every one of the eight audiences into the analysis.

For full section patterns, read `references/analysis-framework.md`.

### 2. Existing High-Performing Material Analysis

When the user supplies no existing hit materials or ad-performance data, proactively research public related videos instead of leaving Section 2 empty, unless the user explicitly asks for an empty framework. For overseas products, prioritize TikTok and YouTube in the target market's languages. Search this product first, then competitors and adjacent categories serving the same audience and need. Label the section "第二节：公开视频素材类型参考（初步）"; public views/likes are not proof of paid-ad performance. Follow the public-reference case format in `references/analysis-framework.md`.

For each case, use a stable structure:

1. Case metadata: material name, ID, platform, date range, screenshots/video attachments if provided.
2. Hit logic: explain the creative mechanism in director language.
3. Basic data: show metrics and explain what each metric means.
4. Playback / click curve: identify first peak, drop-off, secondary peak, and what content node caused them.
5. Reusable points: summarize what can be copied into future materials and what should not be blindly copied.

Do not over-interpret the video if the user says not to watch it. Use only screenshots/data and visible script when that is the instruction.

### 3. Strategy From Product + Case Evidence

After product and cases are analyzed, write strategy as a material system:

- Current material type judgment: explain whether existing runnable materials are concentrated in one shell, such as pain-point tutorial, itch-point display, book-list variant, native content, or IP/personified content.
- Ratio suggestion: keep proven types as the base; reserve a defined test ratio for new content shells or content-pool variants. If the user gives a ratio, preserve it.
- User demand to material direction: map self-motivation and scene demand into concrete material hooks.
- New material direction: explain why the new shell can reach people who do not actively search for the product.
- Rule/risk library: when account bans, compliance risk, exaggerated claims, free/paid ambiguity, or copyrighted content may affect delivery, call out the need for a repeatable expression rule library.
- Cross-category borrowing: borrow proven user psychology and content structures from adjacent categories, not their product details. When the product has little direct material reference, build a "same audience, same demand direction" reference map: identify mature products that serve the same user psychology even if their product form is different, then translate their offline/hardware/space expression into this product's online/app expression.
- Evaluation standards: CTR, 3-second play rate, 5-second retention, completion/hold rate if available, CVR, CPA/CPI, comment/interaction rate, and repeatability.

## Writing Rules

- Write in Chinese by default when the user is working in Chinese.
- Use section titles that sound like analysis, not marketing slogans.
- Put data support close to the claim it supports.
- If a section is only a framework for the user to fill later, say so clearly.
- When adding to an existing Feishu/Lark document, fetch outline first, then edit the smallest relevant block.
- Preserve highlighted text, images, videos, IDs, and user-added examples unless the user explicitly asks to replace them.
- For Feishu/Lark docs, never overwrite the whole document when a block-level edit can satisfy the request.
- For audience analysis, clearly distinguish "measured platform data" from "material-testing hypothesis". By default, use the table shape: real user group/age -> corresponding Douyin e-commerce eight-audience category -> real life scene/state -> core product demand -> likely content-pool videos -> likely e-commerce-pool purchase categories -> material direction.
- For Feishu/Lark docs, highlight core keywords and definitions with yellow background and red text when the user expects marked-up strategic terms.
- For Feishu/Lark docs, when the user asks for a mind map or the section title includes "思维导图", use a real document whiteboard block such as `<whiteboard type="mermaid">mindmap ...</whiteboard>`. Do not use ASCII trees (`├`, `└`, `│`) or plain paragraphs as a substitute. Keep the migration/execution table after the mind map when details need row-column comparison.

## Default Feishu Archive Location

- When creating or reorganizing Feishu documents for product analysis, product content strategy, paid-social material strategy, competitor analysis, or related product-material work, place the finished document in the user's Drive folder named `产品信息分析` by default.
- Keep account-specific identifiers out of this skill. If `LARK_PRODUCT_ANALYSIS_FOLDER_TOKEN` is configured in the target environment, use it. Otherwise, use the available authenticated Feishu/Lark integration to locate a folder named `产品信息分析`.
- If exactly one matching folder is found, use it. If none or multiple are found, ask the user to identify or create the destination instead of guessing.
- Create or edit the document with the authenticated user identity, then use the available Lark CLI, MCP, API, or browser capability to archive it in this folder and verify that the document appears in the target folder listing.
- Use another location only when the user explicitly specifies a different folder or knowledge-base destination.

Minimal Feishu mind map pattern:

```xml
<whiteboard type="mermaid">
mindmap
  root((产品素材参考中心))
    核心需求
    同人群参考品类
      参考品类 A
      参考品类 B
    迁移方向
      从线下硬件表达迁移到线上 App 演示
</whiteboard>
```

## Common Output Shape

Use this shape for a complete document unless the user gives a different structure:

1. 第一节：产品分析
2. 第二节：现有产品爆款视频素材数据分析
3. 第三节：素材类型拓展与内容策略

For a shorter answer, still follow the same logic: product truth -> user psychology -> existing material evidence -> new material tests.
