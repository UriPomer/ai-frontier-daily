# AI Frontier Daily

中文 AI 前沿日报，追踪论文、模型、Agent、多模态、训练与基础设施动态。

## 内容结构

- `daily/`：按 `YYYY-MM-DD.md` 保存每日简报
- `topics/`：按长期主题维护知识索引
- `index.md`：日报总索引
- `daily/TEMPLATE.md`：日报生成模板

## 内容原则

1. 优先引用论文、官方博客、代码仓库等一手来源。
2. 区分事实、作者观点与编辑判断。
3. 每条内容说明技术核心、重要性及开发者启发。
4. 使用稳定标签：`Agent`、`LLM`、`Multimodal`、`Training`、`Infra`。
5. 新日报避免重复前一日内容；同一进展有实质更新时注明变化。

## 计划中的自动化

后续通过 GitHub Actions 每日读取配置的数据源，生成 `daily/YYYY-MM-DD.md`，更新 `index.md` 与最近 7 天列表，然后提交到 `main`。

初始参考源：<https://nlp.elvissaravia.com/>。
