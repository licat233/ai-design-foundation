# Artifact Execution Contract

Use this contract whenever a design is generated, rendered, implemented, or presented as more than an unverified concept.

## Constraint ledger

Before creating the artifact, record every consequential project constraint:

| ID | Rule | Class | Source | Hard gate | Artifact verification |
|---|---|---|---|---|---|
| H-01 | Do not use a split text-left/image-right opening | MUST NOT | Approved project anti-pattern library | Yes | Inspect the rendered first viewport |

Give every project-level **MUST**, **MUST NOT**, and **BLOCKED** rule a unique ID. Add **ALLOWED** and **UNRESOLVED** rules when they affect a decision. Do not rely on memory when a rule can determine delivery status.

## Artifact trust model

Treat output from image generators, code generators, renderers, design tools, and implementation agents as an untrusted draft until inspected.

A correct brief, prompt, plan, or tool call proves only **PROCESS USED**. It does not prove that the artifact is **COMPLIANT**.

## Choose the medium by verification needs

Use image generation for:

- visual direction exploration;
- mood and composition studies;
- imagery concepts;
- early internal references.

Do not treat an image-generated interface as final or verified when the task requires:

- exact approved copy;
- deterministic typography;
- precise component dimensions;
- responsive behavior;
- accessibility verification;
- interactive states;
- production-ready layout.

Use a deterministic medium such as HTML/CSS, a coded prototype, or an editable design tool for those requirements. Treat image-generated text and UI details as provisional.

## Mandatory postflight

After generating, rendering, or implementing:

1. Open or capture the actual artifact.
2. Inspect the complete artifact at a useful scale, not only a thumbnail.
3. Test each hard-gate ledger item against what is visible or operable.
4. Mark each item **PASS**, **FAIL**, or **NOT VERIFIABLE**.
5. Record the observation supporting the status.
6. Never infer **PASS** from prompt compliance.
7. Never convert **NOT VERIFIABLE** into **PASS**.

## Test the structural silhouette

Mentally remove:

- color;
- imagery;
- texture;
- branding;
- motion;
- decorative lines;
- effects and labels.

Inspect the remaining hierarchy and spatial silhouette. If it still matches a project-prohibited pattern, the artifact fails even when its styling looks brand-specific.

Examples:

- A split opening remains split when its right-side image becomes a product shelf.
- An equal feature grid remains equal when icons become product close-ups.
- A SaaS composition remains SaaS-like when blue becomes the brand color.

## Failed output handling

When an artifact violates a **MUST NOT**, **BLOCKED**, or hard **MUST**:

1. mark it **REVISE**;
2. do not call it compliant, approved, finished, or ready;
3. identify the smallest underlying cause;
4. revise or regenerate the affected part;
5. inspect the replacement artifact again;
6. repeat until all hard gates pass or a genuine blocker is reached.

Do not hide a forbidden structure with different colors, imagery, effects, labels, framing, or terminology.

## Resolve authority conflicts explicitly

When current authoritative sources conflict:

1. record both rules and sources;
2. determine whether the conflict changes the artifact;
3. apply an explicit project authority rule when one exists;
4. otherwise mark a consequential conflict **UNRESOLVED**;
5. do not silently choose a preferred rule;
6. do not proceed past the affected irreversible decision without clarification.

A reversible internal draft may continue only when the conflict is visibly documented and cannot be mistaken for an approved result.

## Placeholder integrity

When evidence or approved assets are missing:

- prefer omission or clearly labeled abstraction;
- label placeholder status next to the affected visual;
- do not make a placeholder product-specific or production-ready;
- do not let a page-level disclaimer replace local labeling;
- do not claim placeholder imagery demonstrates real behavior;
- state the replacement trigger and required evidence.

## Evidence limits

A static image cannot prove:

- semantic structure or reading order;
- keyboard operation or focus visibility;
- implemented target sizes;
- responsive reflow or zoom behavior;
- reduced-motion behavior;
- screen-reader output;
- loading performance;
- interaction timing.

A desktop-only artifact cannot be marked responsive. A static artifact cannot be marked accessible. A motion description cannot prove implemented motion is purposeful. Mark these **NOT VERIFIABLE** or **NEEDS EVIDENCE** until the required implementation or viewport exists.

## Design status language

- **PROCESS USED** — the skill's reasoning process was followed.
- **DIRECTIONAL DRAFT** — the artifact supports discussion but has not passed.
- **COMPLIANT** — every hard gate passed against the actual artifact.
- **NEEDS EVIDENCE** — compliance cannot be verified from available evidence.
- **REVISE** — one or more hard gates failed.
- **BLOCKED** — required evidence, authority, assets, or approval is unavailable.

Never use “compliant,” “approved,” “finished,” or “ready” for a directional draft.

## Delivery gate

Before presenting a design as the answer, report only the relevant items:

1. artifact inspected;
2. hard-gate result;
3. failed or unverifiable constraints;
4. artifact status;
5. evidence or asset dependencies;
6. next revision when status is **REVISE**.

Deliver according to status:

- **COMPLIANT**: deliver as compliant.
- **NEEDS EVIDENCE**: deliver with explicit limits.
- **REVISE**: revise before delivery, or show only as a clearly rejected/internal draft.
- **BLOCKED**: do not provide a misleading finished-looking substitute.

Do not let the user discover an obvious hard-gate violation that could have been detected by opening the artifact.
