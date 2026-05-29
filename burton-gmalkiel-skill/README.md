# burton-gmalkiel-skill

> *"A blindfolded chimpanzee throwing darts at the stock pages could select a portfolio that would do as well as one selected by the experts."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**伯顿·G.马尔基尔的被动投资与有效市场思维框架。用随机漫步和有效市场假说的底层逻辑拆解投资策略、市场行为和资产配置。**

基于《漫步华尔街》（13版）、《投资要素》等著作、普林斯顿大学学术研究、Wealthfront投资实践和Vanguard董事会经验，提炼为可运行的思维框架。

---

## 一键安装

```bash
npx skills add <你的GitHub用户名>/burton-gmalkiel-skill
```

或复制到 `~/.config/opencode/skills/burton-gmalkiel-skill/`。

---

## 使用示例

### 问：茅台跌了30%，现在是加仓的好时机吗？

回答会先用"随机漫步检测器"拆解——短期价格波动是噪音，再问你的投资期限是多长。如果是5年以上，定投比抄底更符合马尔基尔的建议；如果是想博反弹，那就是投机不是投资。

### 问：银行理财经理推荐了一个年化15%的私募基金

回答会用"投资时尚过滤器"逐项检查：保证回报？不透明费用？精选历史业绩？再用SPIVA数据显示同类基金跑赢指数的概率。

### 问：30岁，有50万，怎么配置？

回答会从"生命周期资产配置"出发——股票比例≈100-30=70%，首选低成本的宽基指数基金，搭配债券ETF。再用"行为金融偏差识别"检查是否在追求热点。

更多场景在 [cases/scenarios.md](cases/scenarios.md)。

---

## 项目结构

```
burton-gmalkiel-skill/
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

和市面上多数"投资秘籍"不同，这套框架的出发点是：

1. **从学术共识出发**：不教你怎么选牛股，教你"为什么选股长期看没有用"，你掌握了这个底层逻辑，就能自动过滤90%的金融营销。

2. **可操作的判断工具**：每个思维模型附带一个具体的"用法"说明——读完就知道怎么用。

3. **诚实面对局限**：公开标注有效市场假说的边界和指数投资的潜在问题，避免盲目崇拜。

4. **轻量**：不依赖任何外部文件或API，拷走SKILL.md就能用。

---

## 领域标签

投资 · 被动投资 · 有效市场 · 资产配置 · 行为金融 · 指数基金 · 长期主义

---

## License

MIT License © 2026 SumChr
