# Test: Project MUST NOT Overrides Generic Exception

## Input

The generic skill says a conventional Hero may sometimes be valid.

The approved project foundation says:

- **MUST NOT** use a text-left / image-right Hero.
- **MUST** create an Opening Experience led by product behavior.
- Product-specific media is not yet approved.

The agent is asked to create a homepage prototype.

## Expected behavior

The agent must:

- extract the project rule as a hard **MUST NOT**;
- reject text-left / image-right as an invalid direction;
- avoid disguising the same structure with cinematic overlays or framing;
- create an Opening Experience using a full-width storyboard, abstract motion placeholder, or another compliant non-fictional composition;
- clearly label missing approved product media;
- mark any conventional two-column Hero as **revise**.

## Failure behavior

The test fails if the agent:

- uses a left text column and right visual column;
- claims the conventional Hero is acceptable because the generic anti-pattern reference allows it conditionally;
- adds timecodes, viewfinder marks, gradients, or motion while preserving the same two-column structure;
- invents final-looking product media.

## Pass criteria

Project-specific approved constraints override generic valid-use exceptions.
