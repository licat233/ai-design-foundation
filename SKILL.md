---
name: ai-design-foundation
description: Think before designing public-facing brand websites. Use when an AI agent needs to design, redesign, explore, implement, or review a brand website, corporate site, product marketing site, campaign site, ecommerce storefront, or landing page; define a visual direction; prevent generic AI/SaaS aesthetics and invented product claims; or ground layout, content, typography, color, imagery, motion, and interaction decisions in the brand, audience, evidence, and approved project knowledge.
---

# AI Design Foundation

Understand before generating. Use this skill as a compact design discipline, not a style preset or a reason to expand the user's task.

## Before you design

Never begin with:

> What should I generate?

Begin with:

> What should I understand?

Follow this sequence:

**Understand → Question → Evidence → Decision → Design → Inspect artifact → Review → Revise or deliver**

## Artifact compliance overrides prompt compliance

A compliant prompt does not prove a compliant result. Treat every generated, rendered, or implemented artifact as untrusted until you inspect the actual output.

Never claim that a design follows this skill merely because the brief, prompt, or implementation plan included the constraints. Compliance is determined only from the actual artifact.

## Read project knowledge by authority

Prefer, in order:

1. explicitly approved current briefs, foundations, and decision records;
2. verified current product, service, audience, legal, and technical facts;
3. approved assets, content, and design-system rules;
4. validated project evidence and case results;
5. drafts and active explorations;
6. historical, rejected, deprecated, or inspiration-only material.

Use explicit approval status and relevance, not file date or confident wording. Report material conflicts. Never let a draft silently replace an approved decision.

### Extract hard project constraints

Before creating, exploring, reviewing, or implementing a visual direction, extract explicit project constraints into:

- **MUST**
- **MUST NOT**
- **ALLOWED**
- **BLOCKED**
- **UNRESOLVED**

Record every project-level **MUST**, **MUST NOT**, and **BLOCKED** constraint in a ledger with a unique ID, authority source, hard-gate status, and a method for verifying it in the actual artifact.

Project-specific approved constraints override generic recommendations, examples, and valid-use exceptions in this skill.

If an approved project foundation explicitly prohibits a layout, visual pattern, color behavior, interaction, content claim, asset type, or implementation method:

- do not present it as a valid alternative;
- do not reintroduce it through common convention;
- do not use a generic exception in this skill to bypass the project decision;
- mark any output containing it as **revise** before presentation.

A project-level **MUST NOT** is a hard gate, not a preference. Read [references/execution-contract.md](references/execution-contract.md) before producing an artifact that must be generated, rendered, implemented, or verified.

If current authoritative sources conflict, record both rules. Apply an explicit project authority rule when one exists. Otherwise mark a consequential conflict **UNRESOLVED** and do not proceed past the affected irreversible decision without clarification. A reversible internal draft may continue only when the conflict is visible and cannot be mistaken for an approved result.

## Ten questions

### 1. What problem am I solving?

Identify:

- the user's requested deliverable;
- the audience's problem or task;
- the business or organizational objective;
- the constraints that affect the result.

Clarify only when a missing answer materially changes the work and cannot be handled with a reversible assumption.

### 2. What should the audience understand?

Do not begin with page sections. Define:

- what the opening must accomplish;
- what the audience should understand next;
- which uncertainty each major moment removes;
- what evidence earns trust or action.

Design audience understanding, not the company's internal org chart or a default page recipe.

### 3. What is my first answer?

Notice the first layout, palette, component, or style that comes to mind: generic Hero, dark background, three cards, product grid, gradient, dashboard, CTA, or another familiar pattern.

Do not reject it automatically. Do not accept it automatically.

### 4. Why is this my first answer?

Ask whether it follows from the audience, offering, brand world, evidence, and constraints—or merely from a frequent AI pattern.

#### Project override check

Before accepting a familiar pattern, ask:

- Has the approved project foundation explicitly rejected this pattern?
- Is it listed in a project-specific anti-pattern, **MUST NOT** rule, acceptance criterion, or review decision?
- Am I using a generic valid-use exception to reopen an already approved decision?
- Would accepting this pattern make the result structurally similar to an option the project has already rejected?

If yes, reject the pattern and explore a direction that complies with the approved project constraints.

Do not repeatedly reopen confirmed design decisions during execution.

Read [references/anti-patterns.md](references/anti-patterns.md) when the result feels generic, over-styled, interchangeable, or suspiciously familiar.

Use familiar components when justified. The failure is unjustified default use, not familiarity itself.

### 5. What evidence supports the decision?

Trace important choices to:

- user instructions;
- approved project knowledge;
- verified product, service, or organizational facts;
- real assets, content, cases, data, and behavior;
- validated design principles;
- an explicit provisional hypothesis.

Never invent features, behavior, dimensions, metrics, prices, customers, testimonials, awards, certifications, research, compatibility, case results, or legal claims.

When evidence is missing, omit it, state a reversible assumption, use an explicit placeholder such as `[NEEDED: verified metric]`, or mark a blocker. Never hide missing truth inside finished-looking work.

Keep placeholders visibly provisional near the affected visual. Do not make them look product-specific or production-ready, claim they demonstrate real behavior, or rely on a page-level disclaimer instead of local labeling. State what evidence will replace them.

### 6. What am I assuming?

Expose assumptions about:

- audience priorities;
- brand personality;
- product appearance and behavior;
- content and asset quality;
- technical relationships;
- legal, accessibility, or platform constraints.

For each consequential assumption, state its risk and validation. Representative content must be labeled representative.

### 7. Can the offering demonstrate this instead?

Let the product, service, organization, or mission carry the story. Design reveals value; it does not manufacture unsupported value.

Demonstrate when demonstration makes the value clearer. Explain when text is required for accessibility, search, legal review, technical evaluation, comparison, or complete understanding.

Show first and explain second when that order serves the audience. Do not turn this into a ban on copy.

### 8. Am I designing understanding or arranging content?

#### Hierarchy before layout

Before choosing a layout, determine whether the content items have equal communication priority.

Do not default to equal columns because the number of items happens to match a common grid. If the items are equally important, an equal-column layout may be appropriate. If they are not equally important, make the visual hierarchy reflect the communication hierarchy.

Let layout express meaning, not symmetry.

Use these principles:

- establish hierarchy before decoration;
- let attention precede information overload;
- introduce specifications when they help the audience evaluate;
- derive visual behavior from the brand's real environments, materials, people, culture, mechanics, and evidence;
- use motion to reveal change, sequence, function, relationship, or feedback—not merely to decorate;
- vary density and emphasis according to meaning;
- preserve approved intent across breakpoints and implementation details;
- remember that premium does not imply dark, technology does not imply blue, and physical products do not imply SaaS presentation.

Read [references/brand-foundation.md](references/brand-foundation.md) when the brand lacks an actionable foundation or abstract adjectives need translation into design behavior.

### 9. Am I solving the request or expanding it?

Choose one path:

- **Execute** when direction and facts are sufficient;
- **Explore** when a consequential direction remains unresolved;
- **Block** only when missing truth, authority, safety, legal approval, or an irreversible decision prevents responsible work.

When exploring, compare two or three strategically different answers—not cosmetic variations. Stop when one direction has enough evidence for the next reversible step. Read [references/exploration-and-decisions.md](references/exploration-and-decisions.md) only when exploration or a decision record is needed.

Complete the requested website, design, review, or implementation before proposing a larger framework. Do not substitute planning, research, naming, documentation, or theory for the requested artifact.

Keep one version focused on one goal. Finish the current version before optimizing a future version. Improve through **complete → review → revise**, without redesigning unrelated parts each round.

#### Choose the medium by verification needs

Use image generation for visual direction, mood, composition studies, imagery concepts, and early internal references.

When the task requires exact copy, deterministic typography, precise dimensions, responsive behavior, accessibility verification, interactive states, or production-ready layout, use a deterministic medium such as HTML/CSS, a coded prototype, or an editable design tool. Treat image-generated text and UI details as provisional.

### 10. Should I stop thinking?

Stop when:

- the requested artifact exists;
- the relevant review passes;
- unsupported facts are absent;
- remaining uncertainty is non-blocking or explicitly handed back;
- no new evidence, constraint, or request requires another decision.

Do not reopen approved decisions or continue abstracting without new evidence. Summarize, record, deliver, and wait.

After a meaningful failure, add at most one reusable discipline that is directly supported by the failure. Do not turn one mistake into an unsupported theory or a larger architecture.

Before delivery, check:

- Does the requested artifact exist?
- Did I stay inside the requested scope?
- Did new reasoning introduce evidence, or only more ideas?
- Am I improving a version that does not yet exist?
- Does the result satisfy the user's stated success criteria without violating truth, access, or approved constraints?

## Review before delivery

### Mandatory postflight

After generating, rendering, or implementing a design:

1. open or capture the actual artifact;
2. inspect the complete artifact, not only a thumbnail or prompt;
3. test every hard-gate constraint against the artifact;
4. inspect the underlying composition without relying on color, imagery, branding, motion, labels, or decorative effects;
5. mark every constraint **PASS**, **FAIL**, or **NOT VERIFIABLE**;
6. never treat **NOT VERIFIABLE** as **PASS**.

If a **MUST NOT**, **BLOCKED**, or hard **MUST** fails, mark the artifact **REVISE**. Do not call it compliant, approved, finished, or ready. Identify the smallest underlying cause, revise or regenerate the affected part, then inspect the new artifact again. Continue until it passes or reaches a genuine blocker.

Do not let the user discover an obvious hard-gate violation that you could have detected by opening the artifact.

Evaluate in this order:

1. objective and audience task;
2. brand specificity;
3. offering and evidence integrity;
4. experience and content sequence;
5. visual language and rhythm;
6. usability and accessibility;
7. responsive and implementation quality.

Read [references/review-checklist.md](references/review-checklist.md) for a full review. Mark findings as **pass**, **needs evidence**, or **revise**. Tie every requested change to an objective, observation, or principle—not personal taste.

Apply these hard checks:

- Does the result violate any explicit project-level **MUST NOT** or **BLOCKED** constraint?
- Does the underlying composition comply, or have forbidden patterns merely been disguised with decorative styling?
- Has a previously rejected structure been reintroduced with different colors, effects, framing, or terminology?

Mark any violation as **revise**, not **pass**.

Use status language precisely:

- **PROCESS USED** — the reasoning process was followed; this says nothing about artifact compliance;
- **DIRECTIONAL DRAFT** — useful for discussion but not yet passed;
- **COMPLIANT** — every hard gate passed against the actual artifact;
- **NEEDS EVIDENCE** — compliance cannot be verified from the available artifact;
- **REVISE** — one or more hard gates failed;
- **BLOCKED** — required evidence, authority, assets, or approval is unavailable.

A desktop-only artifact cannot prove responsiveness. A static artifact cannot prove accessibility, interaction, or implemented motion. Mark unsupported claims **NOT VERIFIABLE** or **NEEDS EVIDENCE**.

Before delivery, report the artifact inspected, hard-gate result, failed or unverifiable constraints, artifact status, evidence dependencies, and the next revision when status is **REVISE**. Read [references/execution-contract.md](references/execution-contract.md) for the full inspection, revision, evidence, and delivery contract.

For regression or forward-testing of this skill, read [references/evaluation-cases.md](references/evaluation-cases.md). Do not load evaluation cases during ordinary design work.

## Keep output proportional

Match the output to the requested artifact. For a direction decision, default to a one-page brief containing only:

- consequential assumptions;
- one objective;
- relevant principles;
- short alternatives when exploration was necessary;
- the selected direction and evidence;
- main risks or validation steps.

Do not add page-by-page specifications, production copy, full visual rules, or implementation details until the direction is selected or the user requests them.

## Final reminder

Pass every important decision through:

**First Answer → Challenge → Evidence → Decision → Design**

Never design from habit. Design from reasoning. Deliver the requested work, then stop.
