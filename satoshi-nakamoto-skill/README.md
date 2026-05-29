# satoshi-nakamoto-skill

> *"A purely peer-to-peer version of electronic cash would allow online payments to be sent directly from one party to another without going through a financial institution."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**中本聪的去中心化系统思维框架。用密码学证明取代第三方信任的底层逻辑拆解货币、网络和共识系统。**

基于《Bitcoin: A Peer-to-Peer Electronic Cash System》白皮书、中本聪在密码学邮件组和BitcoinTalk论坛的全部公开言论、比特币开源代码的早期实现以及密码朋克运动思想遗产，提炼为可运行的思维框架。

---

## 一键安装

```bash
npx skills add <你的GitHub用户名>/satoshi-nakamoto-skill
```

或复制到 `~/.config/opencode/skills/satoshi-nakamoto-skill/`。

---

## 使用示例

### 问：比特币价值来自哪里？

回答会用"数字稀缺性"模型拆解：比特币的价值不是来自共识，而是来自工作量证明锚定的物理成本、2100万硬顶的数学稀缺性、以及无需许可的全球流动性。然后对比法币的无上限增发和资本管制。

### 问：怎么判断一个新公链项目靠不靠谱？

回答会用"五步系统分析"工具检查它的信任假设、攻击成本、供应上限、参与门槛和激励一致性。如果团队可以冻结地址、增发代币、或者治理投票可以任意修改规则——它就不是去中心化的。

### 问：去中心化到底有什么好处？

回答会用"抗审查网络"的七层防御模型解释：去中心化的核心价值不是效率，是抗攻击韧性。集中式系统效率高但单点失败风险大，去中心化系统效率低但攻击成本指数级上升。

更多场景在 [cases/scenarios.md](cases/scenarios.md)。

---

## 项目结构

```
satoshi-nakamoto-skill/
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

和市面上多数"加密货币科普文章"不同，这套框架的出发点是：

1. **从底层逻辑出发**：不教你怎么买卖比特币，教你"为什么数学可以取代信任"，你拿到这个判断标准，自己就能分析任何去中心化系统。

2. **可操作的分析工具**：每个思维模型附带一个具体的"用法"说明——读完就知道怎么用。

3. **诚实面对局限**：公开标注模型的适用边界和争议点（能源消耗、实际中心化、量子威胁），避免盲目套用。

4. **轻量**：不依赖任何外部文件或API，拷走SKILL.md就能用。

---

## 领域标签

比特币 · 加密货币 · 去中心化 · 密码学 · 共识机制 · 数字稀缺 · 抗审查 · P2P网络 · 经济激励 · 信任最小化

---

## License

MIT License © 2026 SumChr
