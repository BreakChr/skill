# robert-james-shiller-skill

> *"The stock market has not been efficient. There are patterns in the data that question the Efficient Market Hypothesis."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**罗伯特·席勒的行为金融学与叙事经济学思维框架。用非理性繁荣、资产泡沫和叙事传播的底层逻辑拆解市场行为、投资决策和经济政策。**

基于《非理性繁荣》《叙事经济学》《新金融秩序》《金融与好的社会》等著作、Case-Shiller房价指数、CAPE比率研究和2013年诺贝尔奖贡献，提炼为可运行的思维框架。

---

## 一键安装

```bash
npx skills add <你的GitHub用户名>/robert-james-shiller-skill
```

或复制到 `~/.config/opencode/skills/robert-james-shiller-skill/`。

---

## 使用示例

### 问：A股最近涨得太猛了，是泡沫吗？

回答会先用CAPE和历史数据定位当前估值水平，然后用非理性繁荣检测器分析催化因素和心理因素，最后给出"高估值不意味着马上跌，但长期回报预期会降低"的判断。

### 问：比特币还能买吗？

回答会从"基本面现金流"和"病毒式叙事"两个维度拆解，区分投资与投机——没有基本面支撑的价格依赖下一个买家的出价，这是典型的投机性资产特征。

### 问：AI会导致大面积失业吗？

回答会用技术恐慌叙事的历史模式来分析，将当前AI叙事与历史上机器替代、计算机替代做对比，用动物精神框架理解社会的不安全感，而非直接下结论。

更多场景在 [cases/scenarios.md](cases/scenarios.md)。

---

## 项目结构

```
robert-james-shiller-skill/
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

1. **从底层逻辑出发**：不教你怎么选股，教你"市场为什么会有泡沫"和"如何用历史数据定位估值"。
2. **可操作的判断工具**：每个思维模型附带具体的"用法"说明。
3. **诚实面对局限**：公开标注模型的适用边界和争议点。
4. **轻量**：不依赖任何外部文件或API，拷走SKILL.md就能用。

---

## 领域标签

行为金融 · 叙事经济学 · CAPE估值 · 资产泡沫 · 市场波动 · 金融创新 · 动物精神

---

## License

MIT License © 2026 SumChr
