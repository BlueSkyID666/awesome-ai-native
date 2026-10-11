# Contributing

Thanks for keeping this list sharp. 谢谢帮助维护本列表。中文说明在下半部分。

## The bar for an entry

1. **Primary sources only.** Link the arXiv abs page, the official repo, the official report, or a stable reference (e.g., Wikipedia for historical prior art). No aggregators, no tweets, no secondhand summaries.
2. **A stated claim.** Every entry serves at least one of the three principles in the [README](README.md#the-thesis):
   - Standardize interfaces, not behaviors
   - Reduce human relay, keep human accountability
   - Route knowledge, don't warehouse it
   (Well-argued *rejections* of a principle are also welcome — flag them clearly.)
3. **One line of evidence.** Say what the entry demonstrates — a mechanism, a number, a deployment — not marketing copy.
4. **Scope:** organizational / enterprise / workflow dimensions of agents in the loop. Pure capability research with no org angle belongs in the [related lists](README.md#related-lists) instead.

## Checklist for PRs

- [ ] Added to the right section in **both** `README.md` and `README.zh-CN.md` (keep the two in sync).
- [ ] Link resolves (no 404) — yes, please actually click it.
- [ ] Claim stated and defensible; principle alignment noted.
- [ ] One-line description, English in `README.md`, 中文在 `README.zh-CN.md`。

Keyword tuning for the [radar](scripts/radar.py) is also welcome — keep precision high, noise low.

## 贡献指南（中文）

**收录门槛：**

1. **只链一手来源**——arXiv 页面、官方仓库、官方报告或稳定参考（如历史先例用 Wikipedia）；不收聚合站、推特转述或二手总结。
2. **明确论点**——每个条目服务于 [README](README.zh-CN.md#核心论点) 三条原则中至少一条：标准化接口而非行为 / 减少人工中转、保留问责 / 路由知识而非仓储知识。（有理有据地*反对*某条原则也欢迎，但需明确标注。）
3. **一句话证据**——说明该条目展示了什么（机制、数字、部署），不要宣传腔。
4. **范围**：Agent 进入组织/企业/工作流的组织学维度。没有组织视角的纯能力研究请投[相邻列表](README.zh-CN.md#相邻列表)。

**PR 检查项：** 中英两个 README 同步更新；链接实际点开过；论点站得住、注明对齐哪条原则；一句话描述中英各一份。也欢迎调整[雷达](scripts/radar.py)的关键词——保持高精度、低噪声。
