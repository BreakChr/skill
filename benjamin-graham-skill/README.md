# benjamin-graham-skill

> *"The intelligent investor is a realist who sells to optimists and buys from pessimists."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**本杰明·格雷厄姆的价值投资分析框架。用安全边际和内在价值的底层逻辑拆解投资决策和公司分析。**

基于《证券分析》(1934)、《聪明的投资者》(1949)、格雷厄姆-纽曼公司投资实践和28年哥伦比亚商学院教学，提炼为可运行的价值投资思维框架。

---

## 一键安装

```bash
npx skills add <你的GitHub用户名>/benjamin-graham-skill
```

或复制到 `~/.config/opencode/skills/benjamin-graham-skill/`。

---

## 使用示例

### 问：某科技股跌了30%，现在是买点吗？

回答会先帮你区分这是投资还是投机，然后用"市场先生情绪表"定位当前的市场情绪状态，再用"内在价值锚"判断这只股票的价格和内在价值之间的关系，最后给出是否符合安全边际的判断。

### 问：我该做主动投资还是买指数基金？

回答会用"投资者类型识别器"帮你判断你是防御型还是进取型，然后给出相对应的策略建议——如果你没有时间做深度研究，防御型投资者的所有筛选条件会帮你排除90%以上的错误。

### 问：这个公司PE只有8倍，是不是被低估了？

回答会用"七道防御筛选"逐条检验，然后从格雷厄姆的十条进取标准出发，分析低PE是否因为盈利不可持续、负债过高或者其他隐藏风险——低估值可能是价值陷阱。

更多场景在 [cases/scenarios.md](cases/scenarios.md)。

---

## 项目结构

```
benjamin-graham-skill/
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

1. **从底层逻辑出发**：不教你怎么选具体股票，教你"安全边际和内在价值的本质是什么"，你拿到这个判断标准，自己就能分析任何投资标的。

2. **可操作的判断工具**：每个思维模型附带一个具体的"用法"说明——读完就知道怎么用。

3. **诚实面对局限**：公开标注模型的适用边界和争议点，避免盲目套用。

4. **轻量**：不依赖任何外部文件或API，拷走SKILL.md就能用。

---

## 领域标签

价值投资 · 安全边际 · 内在价值 · 市场先生 · 基本面分析 · 防御型投资 · 进取型投资 · 证券分析 · 格雷厄姆价值投资法 · 理性决策

---

## License

MIT License © 2026 SumChr
