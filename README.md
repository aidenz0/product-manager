# 🎯 产品思考三步法（Product Thinking Framework）

<div align="center">

一个可重用的AI思维框架，帮助产品经理通过系统化思考将模糊的产品问题转化为清晰可行的产品方案。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/your-username/product-manager?style=social)](https://github.com/your-username/product-manager/stargazers)

[English](README_EN.md) | 简体中文

</div>

---

## ✨ 特性

### 🧠 三步思考法

- **苏格拉底式提问** - 拆解模糊问题，明确真实需求
- **第一性原理** - 挖掘底层逻辑，回归事实本质
- **奥卡姆剃刀** - 确定最小可行方案，去除冗余���杂度

### 🔄 四步工作流

```
遇到产品问题
    ↓
【澄清】什么是真实问题？（vs 表面问题）
    ↓
【拆解】这由什么组成？（事实、约束、因果）
    ↓
【简化】最简方案是什么？（移除不必要复杂度）
    ↓
【决策】下一步做什么？（可执行方案）
```

### 📚 九大领域知识库

- 📊 **产品发现** - 用户研究、问题验证、需求分析
- 🎯 **MVP定义** - 功能优先级、范围界定
- 👥 **用户行为** - 行为分析、激励机制
- 📈 **指标体系** - 成功指标、A/B测试
- 🏆 **竞争分析** - 竞品分析、差异化定位
- ❓ **触发问题** - 模糊提示→清晰分析
- 📝 **输出模式** - 结构化响应格式
- 💡 **实战示例** - 真实产品决策案例
- ⚠️ **反模式** - 推理陷阱和失败模式

## 🎯 适用场景

| 场景 | 说明 |
|------|------|
| 🔍 **新产品开发** | 创意验证、市场机会评估、MVP范围界定、产品定位 |
| ⚙️ **功能设计** | 需求分析、功能优先级、方案选择、复杂度简化 |
| 📊 **产品优化** | 用户反馈分析、数据指标诊断、产品迭代方向 |
| 🎯 **战略决策** | 竞争策略、增长策略、资源分配、风险评估 |

## 🚀 快速开始

### 安装

```bash
# 克隆项目
git clone https://github.com/your-username/product-manager.git
cd product-manager
```

### 使用方式

#### 方式1：作为Claude Code Skill（推荐）

1. 将此项目放置在本地目录
2. 在Claude Code中引用skill路径
3. 遇到产品决策问题时，AI会自动应用此思维框架

#### 方式2：手动参考

1. 遇到产品问题时，参考 `SKILL.md`
2. 按照 `Workflows/` 中的四步流程思考
3. 查阅 `references/` 获取领域知识
4. 使用 `references/output-patterns.md` 规范输出

### 快速示例

**问题：** "用户要求添加社交分享功能，我们应该做吗？"

**使用产品思考三步法：**

#### 1. 澄清
- **表面问题**：是否添加社交分享？
- **真实问题**：用户想分享内容，但需要理解为什么、分享什么、与谁分享
- **隐藏假设**：用户要求的功能=他们需要的；竞品有=我们要有

#### 2. 拆解
- **事实**：15个用户/3个月提到分享；流失率60%
- **硬约束**：开发团队满负荷2个月
- **因果**：高流失 → 用户找不到价值 → 可能缺乏分享机制

#### 3. 简化
- **完整系统**：高假设负担（假设用户会分享、假设带来增长）
- **最简方案**：添加"复制链接"按钮，测试用户是否真的想分享

#### 4. 决策
- **建议**：不立即构建完整系统
- **实验**：本周添加复制链接，2周后评估数据
- **成功指标**：10%点击率，分享用户留存+20%

更多示例请查看 [USAGE_EXAMPLES.md](USAGE_EXAMPLES.md)

## 📁 项目结构

```
product-manager/
├── SKILL.md                    # 主skill定义
├── Workflows/                  # 四个核心工作流
│   ├── Clarify.md             # 澄清：识别真实问题
│   ├── Deconstruct.md         # 拆解：还原为事实和约束
│   ├── Simplify.md            # 简化：移除不必要复杂度
│   └── Decide.md              # 决策：转化为可执行方案
├── references/                 # 九大领域知识库
│   ├── product-discovery.md   # 产品发现
│   ├── mvp.md                 # MVP定义
│   ├── user-behavior.md       # 用户行为
│   ├── metrics.md             # 指标体系
│   ├── competition.md         # 竞争分析
│   ├── trigger-questions.md   # 触发问题
│   ├── output-patterns.md     # 输出模式
│   ├── examples.md            # 实战示例
│   └── anti-patterns.md       # 反模式避坑
├── QUICKSTART.md              # 5分钟快速入门
├── USAGE_EXAMPLES.md          # 使用示例
└── README.md                  # 项目说明
```

## 💡 核心原则

| 原则 | 说明 |
|------|------|
| 🔎 **澄清再解决** | 不要很好地解决错误的问题 |
| 💭 **显式暴露假设** | 将未声明的假设带到表面 |
| 🚧 **区分约束** | 硬约束真实，软约束可挑战 |
| ✂️ **偏好简单** | 更少假设的方案通常更好 |
| 🎯 **以行动结束** | 始终提供具体下一步或验证计划 |

## 📖 文档

- [📚 快速入门指南](QUICKSTART.md) - 5分钟上手产品思考三步法
- [💡 使用示例](USAGE_EXAMPLES.md) - 3个完整产品决策示例
- [📋 项目总结](PROJECT_SUMMARY.md) - 项目详细说明
- [🎯 SKILL定义](SKILL.md) - 核心skill定义

## 🌟 质量标准

使用此skill产生的优秀回答应该：

- ✅ 识别真实的决策或问题
- ✅ 暴露隐藏假设
- ✅ 将事实与惯性分开
- ✅ 减少不必要的复杂性
- ✅ 保持充分性（不天真简化）
- ✅ 留给产品经理更清晰的下一步

> **记住：目标是更好的产品决策，而不是更聪明的分析。**

## 🤝 贡献

欢迎贡献！请随时提交 Issue 或 Pull Request。

## 📄 License

本项目基于 [MIT License](LICENSE) 开源。

## 🙏 致谢

本项目基于 [decision-clarity-skill](https://github.com/shanezzzz/decision-clarity-skill) 改编，专门针对产品经理的工作场景进行优化和本地化。

---

<div align="center">

## ⭐ Star History

如果这个项目对你有帮助，请给个 Star ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=your-username/product-manager&type=Date)](https://star-history.com/#your-username/product-manager&Date)

**[⬆ 回到顶部](#-产品思考三步法product-thinking-framework)**

Made with ❤️ by Product Managers, for Product Managers

</div>
