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

This project supports skill installation for multiple AI code assistants:

#### Method 1: Claude Code Installation (Recommended)

```bash
# Clone to local skills directory
git clone https://github.com/aidenz0/product-manager.git ~/.claude/skills/product-manager

# Or clone to any directory and configure in settings.json
git clone https://github.com/aidenz0/product-manager.git ~/product-manager
```

Add to `~/.claude/settings.json`:

```json
{
  "skills": [
    "~/product-manager/SKILL.md"
  ]
}
```

#### Method 2: OpenClaw Installation

```bash
# Clone to OpenClaw skills directory
git clone https://github.com/aidenz0/product-manager.git ~/.openclaw/skills/product-manager

# Or use OpenClaw CLI
openclaw skill install https://github.com/aidenz0/product-manager
```

Add skill reference in OpenClaw config:

```yaml
skills:
  - path: ~/.openclaw/skills/product-manager/SKILL.md
    name: product-thinking
    enabled: true
```

#### Method 3: OpenCode Installation

```bash
# Clone to OpenCode extensions directory
git clone https://github.com/aidenz0/product-manager.git ~/.opencode/extensions/product-manager

# Or use OpenCode package manager
opcode extension install product-thinking https://github.com/aidenz0/product-manager
```

Enable skill in OpenCode settings:

```json
{
  "extensions.skills": [
    {
      "name": "product-thinking",
      "path": "~/.opencode/extensions/product-manager/SKILL.md",
      "autoLoad": true
    }
  ]
}
```

#### Method 4: Manual Installation

```bash
# Clone to any directory
git clone https://github.com/aidenz0/product-manager.git
cd product-manager
```

### Usage

#### In Claude Code

After installation, when encountering product decision problems, Claude Code will automatically apply this thinking framework:

```
You: Users are requesting social sharing features. Should we build it?

Claude: [Automatically applies product-thinking skill]
Let's analyze this problem using the Product Thinking Framework...

1. Clarify: What's the real problem?
2. Deconstruct: What are the facts and constraints?
3. Simplify: What's the simplest solution?
4. Decide: What's next?
```

#### In OpenClaw

OpenClaw will automatically load the skill and trigger it in product-related conversations:

```
User: Help me think through this product requirement
OpenClaw: [Detected product-thinking skill]
Applying Product Thinking Framework to analyze...
```

#### In OpenCode

OpenCode integrates the skill into the IDE's AI assistant:

```javascript
// Trigger skill in code comments
// TODO: Use product-thinking to analyze this feature requirement
```

#### Manual Reference Usage

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
