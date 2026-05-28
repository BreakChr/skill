# adam-smith-skill

> *"It is not from the benevolence of the butcher, the brewer, or the baker that we expect our dinner, but from their regard to their own interest."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**亚当·斯密的经济学与道德哲学思维框架。用看不见的手、劳动分工、自利与社会利益的底层逻辑拆解市场机制、商业模式和政策设计。**

基于《国富论》《道德情操论》两部经典，结合250年来的阐释与发展，提炼为可运行的思维框架。

---

## 一键安装

```bash
npx skills add <你的GitHub用户名>/adam-smith-skill
```

或复制到 `~/.config/opencode/skills/adam-smith-skill/`。

---

## 使用示例

### 问：为什么外卖平台的配送费忽高忽低？

回答会用**自然价格与市场价格**模型拆解：配送费是市场出清信号，高峰时需求 > 供给 → 价格上涨 → 吸引更多骑手上线 → 供给增加 → 配送费回落。这是价格机制在实时配置资源。

### 问：我在做AI产品，团队人少应该怎么提高效率？

回答会用**劳动分工与市场规模**模型分析：先判断你的市场规模是否够大。如果市场够大，就要细分专业角色（建模、数据、部署、产品）而不是全员全能。如果市场还在验证阶段，则适合通才团队快速迭代——分工深度要和市场规模匹配。

### 问：公司该不该把客服外包？

回答会用**绝对优势**框架拆解：算一下你的团队在客服上的相对效率，与核心产品开发的效率差。如果你在客服上1小时产生100元价值，在产品上1小时产生1000元价值——应该外包客服，专注于你的优势领域。

更多场景在 [cases/scenarios.md](cases/scenarios.md)。

---

## 项目结构

```
adam-smith-skill/
├── SKILL.md                 # 核心思维框架定义
├── README.md
├── LICENSE
├── playbook/                # 深度原理与操作手册
│   ├── principles.md        # 核心原理详解
│   ├── patterns.md          # 决策模式与行为分析
│   └── origins.md           # 思想源流与表达风格
├── cases/                   # 实战场景案例
│   └── scenarios.md         # 场景对话演示
└── assets/
```

---

## 设计思路

和市面上多数「经济学入门建议」不同，这套框架的出发点是：

1. **从底层逻辑出发**：不教你怎么炒股买房，教你「价格信号如何配置资源」「分工如何产生效率」——你拿到这些判断工具，自己就能分析任何市场和行业。

2. **可操作的判断工具**：每个思维模型附带一个具体的「用法」说明——读完就知道怎么用。

3. **诚实面对局限**：公开标注模型的适用边界和争议点，避免盲目套用。

4. **轻量**：不依赖任何外部文件或API，拷走SKILL.md就能用。

---

## 领域标签

经济学 · 商业 · 市场 · 制度分析 · 效率 · 分工 · 自发秩序 · 公共政策

---

## License

MIT License © 2026 SumChr
