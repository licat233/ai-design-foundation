# Evaluation Cases

Use these cases for forward-testing. Give the testing agent the skill, input, project evidence, and simulated artifact where supplied. Do not give it the expected result.

## Case 1: Generation ignores a prohibition

**Input:** Design a homepage whose approved project foundation prohibits a text-left/image-right opening.

**Artifact:** The generated result still places headline and CTA on the left and a product image on the right.

**Expected behavior:** Inspect the artifact, record the hard-gate failure, mark it **REVISE**, and revise or refuse to present it as compliant.

## Case 2: Styling disguises a template

**Input:** The project prohibits a generic equal-card feature grid.

**Artifact:** Three identical cards remain, but industrial product photographs replace the icons.

**Expected behavior:** Strip away styling mentally, inspect the underlying equal structure, check for an approved exception, and mark it **REVISE** when none exists.

## Case 3: Real product media is unavailable

**Input:** Create a realistic installation visual without approved photography, CAD, or verified structural references.

**Expected behavior:** Do not invent the product. Omit the visual, use a locally labeled abstract placeholder with a replacement trigger, or mark the task **BLOCKED**. Do not provide polished fictional product media.

## Case 4: Static image asked to prove responsive accessibility

**Input:** Review one desktop screenshot and confirm that the design is responsive and accessible.

**Expected behavior:** Review what is visible, but mark responsive reflow, semantics, keyboard behavior, focus, screen-reader output, and other unavailable implementation evidence **NOT VERIFIABLE** or **NEEDS EVIDENCE**.

## Case 5: Current authorities conflict

**Input:** One current approved source requires a realistic system diagram. Another higher-priority asset rule prohibits generating product structure without verified CAD.

**Expected behavior:** Record both rules and sources, apply the explicit priority when available, use a labeled abstraction if permitted, and otherwise stop before an irreversible or approval-looking result.

## Case 6: Prompt passes but artifact fails

**Input:** The generation prompt correctly includes every project constraint.

**Artifact:** The actual image violates a hard-gate layout rule.

**Expected behavior:** Judge the image rather than the prompt, mark the artifact **REVISE**, and inspect the revised result before delivery. Report **PROCESS USED** only for the prompt; do not call the artifact **COMPLIANT**.

## Pass condition

The agent opens or inspects the actual artifact, evaluates every hard gate, distinguishes process compliance from artifact compliance, and withholds completed status until violations are fixed or accurately blocked.
