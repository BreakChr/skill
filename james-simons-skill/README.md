# james-simons-skill

> *"We look for things that can be replicated thousands of times."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**詹姆斯·西蒙斯的量化投资思维框架。用数学模型和数据驱动的底层逻辑拆解市场决策、量化策略和风险管理。**

基于文艺复兴科技公司（Renaissance Technologies）实践、大奖章基金（Medallion Fund）业绩记录、公开访谈、传记《The Man Who Solved the Market》和批评者分析，提炼为可运行的思维框架。

---

## 一键安装

```bash
npx skills add <你的GitHub用户名>/james-simons-skill
```

或复制到 `~/.config/opencode/skills/james-simons-skill/`。

---

## 使用示例

### 问：我最近按一个策略交易，连续亏损5次，该不该放弃？

回答会用"概率优势检测器"拆解——先确认你的策略是否有统计上的正期望，如果没有，放弃是对的；如果有，5次连续亏损在大量重复中完全正常。然后引导你检查仓位是否过大（凯利准则），以及你是否在用情绪代替系统。

### 问：AI能不能帮我预测股票涨跌？

回答会拆解"预测"和"模式识别"的区别——AI不能预测未来，但可以找到过去数据中重复出现的统计规律。然后用"信号与噪声过滤器"说明，关键不是你用了多强的模型，而是你输入了什么数据、你检验了什么假设。

### 问：怎么判断一个量化策略的好坏？

回答会用"黑箱封测法"给出四个检验层级——回测、样本外测试、实盘测试、跨周期压力测试，并用"团队悖论破解器"补充说明，一个策略的质量取决于设计者的思维多样性。

更多场景在 [cases/scenarios.md](cases/scenarios.md)。

---

## 项目结构

```
james-simons-skill/
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

和市面上多数"量化投资秘籍"不同，这套框架的出发点是：

1. **从底层逻辑出发**：不教你写代码选参数，教你"什么是概率优势、怎么判断信号质量"，你拿到这个判断标准，自己就能评估任何策略。

2. **可操作的思维工具**：每个思维模型附带一个具体的"用法"说明——读完就知道怎么用。

3. **诚实面对局限**：公开标注模型的适用边界和争议点，避免盲目套用。

4. **轻量**：不依赖任何外部文件或API，拷走SKILL.md就能用。

---

## 领域标签

量化 · 数据驱动 · 统计套利 · 概率思维 · 高频交易 · 系统化决策 · 数学建模 · 风险管理 · 算法交易

---

## License

MIT License © 2026 SumChr
