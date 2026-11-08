---
name: product-growth-skills-setup
description: "Guide first-time installation and initial configuration of the product-material-strategy Skill in this repository. Use when installing it, checking research capability, configuring optional Feishu output, or starting the first analysis."
---

# 产品策略 Skill 配置引导

Guide first-time installation and initial configuration of the product-material-strategy Skill in this repository. Use when installing it, checking research capability, configuring optional Feishu output, or starting the first analysis.

## Locate the project

Read installed `references/installation.json` when present, and verify its `repository_path` contains `onboarding.json` and `skills/product-material-strategy/SKILL.md`. If moved, use the user's clone location. Read that Skill's `INSTALL.md` and `references/analysis-framework.md` for the chosen output.

## Choose the smallest usable path

1. Check discovery of the functional `product-material-strategy` Skill. If missing, run the clone's `python3 scripts/install_skills.py` and reopen the task. No model package, paid API or ad-account connection is required for analysis of supplied materials.
2. Determine whether the user wants analysis in this chat/local files or a Feishu document. Local output does not require Feishu setup. Reuse any known product URL, market, language and available material/performance evidence; ask only for missing inputs that affect the analysis.
3. Inspect actual search/browser capability. When unavailable, use supplied official materials and label missing research; never fill missing ad metrics with invented data. Public likes and views are reference evidence, not paid-delivery proof.
4. Only for requested Feishu output, inspect the available authenticated integration. Use that integration's documented authorization flow if needed; never ask for copied cookies, app secrets or full config dumps. Resolve `LARK_PRODUCT_ANALYSIS_FOLDER_TOKEN` locally or locate a folder named “产品信息分析”. If none or multiple match, obtain the destination rather than guessing. Existing documents should be edited by block, preserving user content.
5. Run a small first analysis following product truth → material evidence → test strategy. Mark what is measured, publicly observed, hypothesized or missing. Writing to Feishu is appropriate only when the user requested that output; do not create test documents as part of local setup.

Report the installed Skill, available evidence tools, chosen output location and any unresolved authorization. Ready for supplied-material analysis can be true even if Feishu or live ad-data access is absent.
