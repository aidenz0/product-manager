# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **Product Thinking Framework** (产品思考三步法) - a reusable AI skill designed to help product managers think through product problems systematically using three reasoning modes:

1. **Socratic Questioning** (苏格拉底式提问) - Clarify ambiguous problems
2. **First Principles Thinking** (第一性原理) - Dig into underlying logic
3. **Occam's Razor** (奥卡姆剃刀) - Determine minimum viable solutions

## Repository Structure

```
product-manager/
├── SKILL.md                    # Main skill definition
├── Workflows/                  # Core workflows
│   ├── Clarify.md             # Step 1: Identify real problem
│   ├── Deconstruct.md         # Step 2: Reduce to facts & constraints
│   ├── Simplify.md            # Step 3: Remove unnecessary complexity
│   └── Decide.md              # Step 4: Convert to actionable plan
├── references/                 # Domain knowledge references
│   ├── product-discovery.md   # User research & problem validation
│   ├── mvp.md                 # MVP definition & feature prioritization
│   ├── user-behavior.md       # User behavior & motivation
│   ├── metrics.md             # Success metrics & A/B testing
│   ├── competition.md         # Competitive analysis & differentiation
│   ├── trigger-questions.md   # Transform vague prompts
│   ├── output-patterns.md     # Structured response formats
│   ├── examples.md            # Concrete product decision examples
│   └── anti-patterns.md       # Common reasoning pitfalls
├── README.md                   # Project documentation
└── CLAUDE.md                   # This file
```

## How to Use This Skill

When invoked, this skill follows a structured approach:

1. **Clarify** - Identify the real question before solving it
2. **Deconstruct** - Break down into facts, constraints, and causal structure
3. **Simplify** - Remove false complexity while preserving adequacy
4. **Decide** - End with actionable product solution, MVP definition, or next steps

## Key Principles

- **Clarify before solving** - Don't solve the wrong problem well
- **Expose assumptions explicitly** - Surface hidden and inherited assumptions
- **Distinguish hard vs soft constraints** - Hard constraints are real; soft constraints are challengeable
- **Prefer lower assumption load** - Solutions with fewer unnecessary assumptions are usually better
- **Always end with a decision** - Provide concrete next steps, not abstract analysis

## Best Use Cases

- New product ideation and validation
- Feature prioritization decisions
- Product requirement analysis (before PRD)
- MVP scope definition
- User feedback analysis and requirement extraction
- Product roadmap planning
- Competitive analysis and positioning
- Product complexity simplification
- Growth strategy design

## Output Quality Standards

A good response should:
- Identify the real decision or problem
- Expose hidden assumptions
- Separate facts from inertia
- Reduce unnecessary complexity
- Preserve adequacy (no naive simplification)
- End with clear next steps

## Notes

- This skill is adapted from [decision-clarity-skill](https://github.com/shanezzzz/decision-clarity-skill)
- Goal: Better product decisions, not cleverer analysis
- Always ask: "Does this improve the product manager's ability to decide and act?"
