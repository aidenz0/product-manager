# 🎯 Product Thinking Framework

<div align="center">

A reusable AI thinking framework that helps product managers transform vague product problems into clear, actionable solutions through systematic reasoning.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/your-username/product-manager?style=social)](https://github.com/your-username/product-manager/stargazers)

English | [简体中文](README.md)

</div>

---

## ✨ Features

### 🧠 Three-Step Thinking Method

- **Socratic Questioning** - Clarify ambiguous problems and identify real requirements
- **First Principles Thinking** - Dig into underlying logic and return to facts
- **Occam's Razor** - Determine minimum viable solutions and remove unnecessary complexity

### 🔄 Four-Step Workflow

```
Product Problem Arises
    ↓
【Clarify】What's the real problem? (vs. surface problem)
    ↓
【Deconstruct】What is it made of? (facts, constraints, causality)
    ↓
【Simplify】What's the simplest solution? (remove unnecessary complexity)
    ↓
【Decide】What's next? (actionable plan)
```

### 📚 Nine Domain Knowledge Bases

- 📊 **Product Discovery** - User research, problem validation, requirement analysis
- 🎯 **MVP Definition** - Feature prioritization, scope definition
- 👥 **User Behavior** - Behavior analysis, incentive mechanisms
- 📈 **Metrics** - Success metrics, A/B testing
- 🏆 **Competition** - Competitive analysis, differentiation positioning
- ❓ **Trigger Questions** - Transform vague prompts into clear analysis
- 📝 **Output Patterns** - Structured response formats
- 💡 **Examples** - Real product decision cases
- ⚠️ **Anti-Patterns** - Reasoning pitfalls and failure modes

## 🎯 Use Cases

| Scenario | Description |
|----------|-------------|
| 🔍 **New Product Development** | Idea validation, market opportunity assessment, MVP scoping, product positioning |
| ⚙️ **Feature Design** | Requirement analysis, feature prioritization, solution selection, complexity simplification |
| 📊 **Product Optimization** | User feedback analysis, metrics diagnosis, iteration direction |
| 🎯 **Strategic Decisions** | Competitive strategy, growth strategy, resource allocation, risk assessment |

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/product-manager.git
cd product-manager
```

### Usage

#### Method 1: As a Claude Code Skill (Recommended)

1. Place this project in a local directory
2. Reference the skill path in Claude Code
3. AI will automatically apply this thinking framework when encountering product decision problems

#### Method 2: Manual Reference

1. When facing a product problem, refer to `SKILL.md`
2. Think through the four-step workflow in `Workflows/`
3. Consult relevant `references/` for domain knowledge
4. Use `references/output-patterns.md` to structure your response

### Quick Example

**Problem:** "Users are requesting social sharing features. Should we build it?"

**Using Product Thinking Framework:**

#### 1. Clarify
- **Surface problem:** Should we add social sharing?
- **Real problem:** Users want to share content, but we need to understand why, what, and with whom
- **Hidden assumptions:** User requests = what they need; competitors have it = we need it

#### 2. Deconstruct
- **Facts:** 15 users mentioned sharing in 3 months; 60% churn rate
- **Hard constraints:** Dev team fully booked for 2 months
- **Causality:** High churn → Users don't find value → May lack sharing mechanisms

#### 3. Simplify
- **Full system:** High assumption load (assume users will share, assume it drives growth)
- **Simplest solution:** Add "copy link" button, test if users really want to share

#### 4. Decide
- **Recommendation:** Don't build full system immediately
- **Experiment:** Add copy link button this week, evaluate data in 2 weeks
- **Success metrics:** 10% click rate, +20% retention for sharing users

For more examples, see [USAGE_EXAMPLES.md](USAGE_EXAMPLES.md)

## 📁 Project Structure

```
product-manager/
├── SKILL.md                    # Main skill definition
├── Workflows/                  # Four core workflows
│   ├── Clarify.md             # Clarify: Identify real problem
│   ├── Deconstruct.md         # Deconstruct: Reduce to facts & constraints
│   ├── Simplify.md            # Simplify: Remove unnecessary complexity
│   └── Decide.md              # Decide: Convert to actionable plan
├── references/                 # Nine domain knowledge bases
│   ├── product-discovery.md   # Product discovery
│   ├── mvp.md                 # MVP definition
│   ├── user-behavior.md       # User behavior
│   ├── metrics.md             # Metrics system
│   ├── competition.md         # Competitive analysis
│   ├── trigger-questions.md   # Trigger questions
│   ├── output-patterns.md     # Output patterns
│   ├── examples.md            # Practical examples
│   └── anti-patterns.md       # Anti-patterns to avoid
├── QUICKSTART.md              # 5-minute quick start guide
├── USAGE_EXAMPLES.md          # Usage examples
└── README.md                  # Project documentation
```

## 💡 Core Principles

| Principle | Description |
|-----------|-------------|
| 🔎 **Clarify before solving** | Don't solve the wrong problem well |
| 💭 **Expose assumptions explicitly** | Surface hidden and inherited assumptions |
| 🚧 **Distinguish constraints** | Hard constraints are real; soft constraints are challengeable |
| ✂️ **Prefer simplicity** | Solutions with fewer assumptions are usually better |
| 🎯 **End with action** | Always provide concrete next steps or validation plans |

## 📖 Documentation

- [📚 Quick Start Guide](QUICKSTART.md) - Get started with Product Thinking Framework in 5 minutes
- [💡 Usage Examples](USAGE_EXAMPLES.md) - 3 complete product decision examples
- [📋 Project Summary](PROJECT_SUMMARY.md) - Detailed project documentation
- [🎯 SKILL Definition](SKILL.md) - Core skill definition

## 🌟 Quality Standards

Good product thinking output should:

- ✅ Identify the real decision or problem
- ✅ Expose hidden assumptions
- ✅ Separate facts from inertia
- ✅ Reduce unnecessary complexity
- ✅ Preserve adequacy (no naive simplification)
- ✅ End with clear next steps

> **Remember: The goal is better product decisions, not cleverer analysis.**

## 🤝 Contributing

Contributions are welcome! Please feel free to submit Issues or Pull Requests.

## 📄 License

This project is open source under [MIT License](LICENSE).

## 🙏 Acknowledgments

This project is adapted from [decision-clarity-skill](https://github.com/shanezzzz/decision-clarity-skill), optimized and localized for product manager scenarios.

---

<div align="center">

## ⭐ Star History

If this project helps you, please give it a Star ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=your-username/product-manager&type=Date)](https://star-history.com/#your-username/product-manager&Date)

**[⬆ Back to Top](#-product-thinking-framework)**

Made with ❤️ by Product Managers, for Product Managers

</div>
