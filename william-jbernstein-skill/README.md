# william-jbernstein-skill

> *"The goal of most investors should be not to get rich, but to avoid poverty."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**威廉·伯恩斯坦的投资与资产配置思维框架。用四大支柱的底层逻辑拆解投资决策、风险管理和组合构建。**

基于《投资金律》《智慧型资产配置》《繁荣的背后》《贸易大历史》《群众幻觉》等著作、效率前沿投资管理实践和CFA詹姆斯·佛汀奖，提炼为可运行的思维框架。

---

## 一键安装

```bash
npx skills add <你的GitHub用户名>/william-jbernstein-skill
```

或复制到 `~/.config/opencode/skills/william-jbernstein-skill/`。

---

## 使用示例

### 问：现在适合买什么股票？

回答不会推荐股票。而是先用"四大支柱检测器"定位你的问题属于理论支柱（风险与回报的关系），再用"资产配置决策器"引导你关注股债比例而非选股，最后告诉你：你的问题本身可能错了。

### 问：比特币还能涨吗？

回答会用"市场历史镜"对照历史上的泡沫特征——改变世界的新叙事、专家一致看好、价格脱离估值锚、杠杆涌入——让你自己判断。

### 问：我该不该买主动管理基金？

回答会用"投资产业反光镜"拆解：主动基金的费用结构、长期跑输指数的数据、以及华尔街的利益冲突。然后告诉你：先建好指数组合，再考虑其他。

更多场景在 [cases/scenarios.md](cases/scenarios.md)。

---

## 项目结构

```
william-jbernstein-skill/
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

和市面上多数"投资建议合集"不同，这套框架的出发点是：

1. **从底层逻辑出发**：不教你选哪只基金哪只股票，教你"风险与报酬的本质关系是什么"，你拿到这个判断标准，自己就能分析任何投资品。

2. **可操作的判断工具**：每个思维模型附带一个具体的"用法"说明——读完就知道怎么用。

3. **诚实面对局限**：公开标注模型的适用边界和争议点，避免盲目套用。

4. **轻量**：不依赖任何外部文件或API，拷走SKILL.md就能用。

---

## 领域标签

投资 · 资产配置 · 指数投资 · 行为金融学 · 风险管理 · 经济史 · 分散投资

---

## License

MIT License © 2026 SumChr
