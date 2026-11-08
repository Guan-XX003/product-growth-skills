# Product Growth Skills · 产品分析与素材内容策略

从产品事实、目标用户和素材证据出发，帮助策划人员回答：这个产品该对谁说、先说哪个卖点、用什么视频形式表达，以及下一轮测试什么素材。

当前提供一个 Skill：[`product-material-strategy`](skills/product-material-strategy/SKILL.md)。它用于 Codex 的产品研究和内容策划，适合 App、软件、订阅与工具类产品。

## 适合哪些任务

| 任务 | 产出 |
|---|---|
| 新产品分析 | 功能与卖点、竞品、行业痛点和目标用户 |
| 已有素材复盘 | Hook、视觉证明、留存节点、点击与转化表现 |
| 缺少投放数据时找参考 | 公开相关视频、来源链接和可借鉴的表达 |
| 下一轮内容测试 | 人群—场景—需求—素材形式—评估指标 |
| 整理飞书策略文档 | 保留原结构的局部补充、表格和思维导图 |

公开视频的播放量、点赞量只作为内容参考；有真实广告数据时才分析投放效果。数据不足的结论会标为假设或待验证。

## 安装

需要支持 Skills 的 Codex；基础分析可以使用你提供的资料。联网研究和飞书文档操作分别依赖当前环境中的搜索、浏览器或飞书集成。

```bash
git clone https://github.com/Guan-XX003/product-growth-skills.git
mkdir -p "$HOME/.codex/skills"
cp -R product-growth-skills/skills/product-material-strategy "$HOME/.codex/skills/"
```

如已安装同名 Skill，先备份再更新。重新打开 Codex 任务即可发现；其他助手可将完整 Skill 目录放进其支持的 Skills 目录。

## 第一次使用

```text
$product-material-strategy
分析【产品名称、官网或商店链接】，目标市场是【地区与语言】。
请按“产品分析 → 素材参考分析 → 内容策略”输出。
目前没有真实投放数据，请查找公开参考，并把假设与实测结论分开。
每个素材方向写清楚人群、场景、开头 Hook、功能演示和验证指标。
```

复盘已有广告时，再附上素材或截图、投放时间、消耗、展示、点击、转化与播放指标。只提供你有权使用的数据。

## 输入与输出示例

输入：“一款桌面组件 App，希望面向刚开始美化手机桌面的用户。”

输出方向示例：用户嫌设置复杂 → 用“设置前后对比 + 一次实际操作”解释价值 → 测试不同开头的点击、留存与转化。这只是示意，不代表该方向已被验证有效。

完整文档通常有三部分：

1. **产品分析**：功能、主次卖点、竞品、行业痛点与用户。
2. **素材分析**：现有广告证据；无广告数据时改为公开参考。
3. **内容策略**：可复用表达、素材类型扩展、下一轮测试与评估标准。

详细表格和案例格式见 [分析框架](skills/product-material-strategy/references/analysis-framework.md)。

## 可选：接入飞书

需要你自己的、已授权的飞书集成。Skill 不附带飞书账号、凭据或已建文档。

默认查找名为“产品信息分析”的文件夹；若目标环境提供 `LARK_PRODUCT_ANALYSIS_FOLDER_TOKEN`，则使用该配置。未找到或存在多个同名文件夹时，需要你明确目的地。

```bash
export LARK_PRODUCT_ANALYSIS_FOLDER_TOKEN="你的目标文件夹 token"
```

是否需要在桌面应用环境中额外配置变量，取决于所用飞书集成。详见 [安装与迁移](skills/product-material-strategy/INSTALL.md)。

## 目录与使用边界

```text
skills/product-material-strategy/
  SKILL.md                       工作流与写作规则
  INSTALL.md                     安装和飞书配置
  agents/openai.yaml             助手发现信息
  references/analysis-framework.md 详细分析框架
```

本项目提供分析方法和 Skill，不内置广告投放连接、自动采集服务或投放执行功能；不能凭空得到你的后台数据，也不保证某个素材方案必然起量。

[反馈问题](https://github.com/Guan-XX003/product-growth-skills/issues)时请附上脱敏输入、缺失的分析环节和期望输出。

[维护说明](MANAGEMENT.md)
