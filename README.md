# AI Design Foundation

A brand-agnostic design-thinking and working-discipline skill for AI agents.

AI Design Foundation helps an agent understand before generating, challenge familiar design defaults, ground important decisions in evidence, protect product truth, review against principles, and deliver the requested work without uncontrolled scope expansion.

It is designed for public-facing brand websites, including corporate sites, product marketing sites, campaign sites, ecommerce storefronts, and landing pages.

## Why this exists

AI agents can produce polished interfaces quickly, but polished output can still be:

- generic or interchangeable;
- shaped by familiar Hero, card, SaaS, gradient, or dark-tech patterns;
- disconnected from the brand's real context;
- based on invented product facts or hidden assumptions;
- over-planned while the requested artifact remains unfinished.

This skill introduces a compact working loop:

```text
Understand
    ↓
Question
    ↓
Evidence
    ↓
Decision
    ↓
Design
    ↓
Review
    ↓
Deliver
```

Every important decision passes through:

```text
First Answer → Challenge → Evidence → Decision → Design
```

## What it changes

When asked to “design a homepage,” an agent should not immediately default to:

```text
Hero → Three Cards → Features → CTA → Footer
```

It should first determine:

- What is the requested deliverable?
- Who is the audience, and what are they trying to understand or do?
- What business or organizational objective matters?
- Which project sources are approved and authoritative?
- What real product, service, brand, and content evidence exists?
- What assumptions or blockers remain?
- Is direct execution appropriate, or is limited exploration required?
- Is the first visual answer justified, or merely familiar?

## Core principles

- Understand before generating.
- Design audience understanding, not default page structure.
- Let the product, service, organization, or mission carry the story.
- Prefer evidence over unsupported claims.
- Demonstrate when demonstration clarifies; explain when complete understanding requires it.
- Use motion to reveal function, sequence, relationship, change, or feedback—not merely to decorate.
- Treat familiar components as tools, not forbidden patterns or automatic answers.
- Never invent product facts, metrics, customers, certifications, cases, or technical behavior.
- Explore consequential decisions, not cosmetic variations.
- Review through objectives and principles, not personal preference.
- Complete the requested work before expanding its scope.
- Stop abstracting when the evidence and request have ended.

## Install in Codex

Codex supports the open Agent Skills format and discovers skills from user and repository locations.

### User-wide installation

```bash
git clone https://github.com/licat233/ai-design-foundation.git \
  "$HOME/.agents/skills/ai-design-foundation"
```

### Repository-scoped installation

From the repository root:

```bash
git submodule add https://github.com/licat233/ai-design-foundation.git \
  .agents/skills/ai-design-foundation
```

Codex normally detects new and updated skills automatically. Restart Codex if the skill does not appear.

Invoke it explicitly with:

```text
$ai-design-foundation
```

Codex may also activate it implicitly when a task matches the scope in the `description` field.

See the official [Codex skill documentation](https://learn.chatgpt.com/docs/build-skills.md) for current discovery locations and behavior.

## Use with other AI agents

The core workflow is instruction-only Markdown and does not depend on Codex-specific tools.

If an agent supports the [Agent Skills standard](https://agentskills.io), install this repository as a skill directory using that agent's documented discovery location.

If an agent does not support Agent Skills directly, load [`SKILL.md`](SKILL.md) as project or agent instructions and make the `references/` files available for selective reading. Do not assume that Claude Code, Cursor, Gemini, or another agent uses the same installation path as Codex; follow that product's current documentation.

## Example prompts

```text
Use $ai-design-foundation to define a homepage direction for this brand before creating mockups.
```

```text
Use $ai-design-foundation to review this website for generic AI patterns, unsupported claims, and weak brand specificity.
```

```text
Use $ai-design-foundation to implement the approved direction without inventing missing product facts.
```

```text
Use $ai-design-foundation to decide whether this task needs creative exploration or can proceed directly to execution.
```

## Recommended composition

AI Design Foundation is the stable, brand-independent layer. Project-specific brand knowledge should remain separate.

```text
AI Design Foundation
        +
Brand foundation or Brand Skill
        +
Approved project brief and decisions
        +
Verified content and assets
        ↓
Design execution
```

For example, an ARMOR project may load AI Design Foundation together with an ARMOR-specific brand layer. The core skill itself contains no ARMOR rules and does not default to an industrial, retail, architectural, dark, light, premium, or SaaS visual style.

## Repository structure

```text
ai-design-foundation/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── anti-patterns.md
    ├── brand-foundation.md
    ├── exploration-and-decisions.md
    └── review-checklist.md
```

- [`SKILL.md`](SKILL.md) contains the mandatory compact workflow.
- [`references/brand-foundation.md`](references/brand-foundation.md) translates brand evidence and abstract adjectives into design behavior.
- [`references/anti-patterns.md`](references/anti-patterns.md) checks conditional failure patterns without banning familiar components.
- [`references/exploration-and-decisions.md`](references/exploration-and-decisions.md) governs limited exploration and decision records.
- [`references/review-checklist.md`](references/review-checklist.md) provides the full review gate.
- [`agents/openai.yaml`](agents/openai.yaml) provides optional Codex/ChatGPT UI metadata.

The references use progressive disclosure: agents should load only the file needed for the current decision.

## Scope

This skill does not:

- provide a universal visual style;
- replace a brand's approved identity or design system;
- make missing product knowledge safe to invent;
- guarantee that a design is effective without real users, content, implementation, and validation;
- require every website to avoid dark themes, Heroes, cards, gradients, or familiar components.

Its job is narrower and more practical:

> Prevent an AI agent from producing a finished-looking design before it has enough understanding, evidence, and direction to do so responsibly.

## Contributing

Issues and pull requests are welcome when they are supported by observed design failures, real project evidence, or repeatable evaluation—not theory expansion alone.

Keep proposed changes focused. One failure should normally produce one testable improvement, not a larger framework.
