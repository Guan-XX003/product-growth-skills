# 安装与迁移

将整个 `product-material-strategy` 文件夹复制到目标电脑的 Codex Skills 目录：

```text
~/.codex/skills/product-material-strategy/
```

安装后的必要结构：

```text
product-material-strategy/
├── SKILL.md
├── agents/openai.yaml
└── references/analysis-framework.md
```

重启 Codex 或重新打开任务后，可通过 `$product-material-strategy` 显式调用；符合产品分析、竞品分析、用户画像和投放素材策略的任务也允许自动调用。

## 可选飞书配置

如需把产出的飞书文档默认归档到固定文件夹，可在目标电脑配置：

```bash
export LARK_PRODUCT_ANALYSIS_FOLDER_TOKEN="目标文件夹的 folder_token"
```

未配置时，Skill 会使用目标电脑已登录的飞书账号查找名为 `产品信息分析` 的文件夹，不依赖原电脑的账号或绝对路径。
