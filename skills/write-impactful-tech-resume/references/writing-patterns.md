# Coaching prompts for technical resume writing

Use this reference to diagnose and locally revise text the user has already written. Never turn these patterns into a first draft or fill them from raw facts.

## Table of contents

- Local-edit protocol
- Project-positioning prompts
- Achievement prompts
- Metric prompts
- Depth prompts
- Translation and style

## Local-edit protocol

Work on one user-written line at a time:

1. Identify the line's current claim.
2. Identify one missing link: task, need, ownership, mechanism, scope, or result.
3. Ask for that fact if it is not already confirmed.
4. Make the smallest revision that incorporates confirmed evidence.
5. Explain the change and request confirmation.

Do not replace the user's voice with a standard formula. Do not add a second achievement merely because the line looks short.

## Project-positioning prompts

Ask:

- Who uses the project?
- What concrete task or decision does it support?
- What was inadequate before?
- What source, workflow, or constraint makes it non-trivial?
- Why is this an application, infrastructure, or algorithm project?

Offer only this empty scaffold when needed:

`[user/task] + [unmet need] + [key constraint] + [solution category]`

Fail the opening if it only names `Multi-Agent`, `RAG`, `platform`, or `framework`. Read [project-narrative.md](project-narrative.md) for architecture-heavy work.

## Achievement prompts

### Application or Agent work

Ask which user failure or workflow problem led to the routing, retrieval, tool, fallback, memory, or evaluation decision. Ask how task completion was validated.

Use only this schematic:

`need/observed failure → personal decision → mechanism → validation`

### Architecture or platform work

Ask what runtime, state, scheduling, consistency, recovery, deployment, or adoption bottleneck existed. Ask what alternative was considered and why the final boundary fit.

Use only this schematic:

`platform bottleneck → ownership boundary → tradeoff → mechanism → operating result`

### Performance work

Ask for workload, hardware/model, bottleneck evidence, intervention, before/after conditions, and quality guardrail.

Use only this schematic:

`conditions + bottleneck → intervention → comparable measurement + guardrail`

### Reliability and operations

Ask for the concrete failure mode, detection method, recovery or prevention mechanism, affected scope, and resulting incident or recovery metric.

### Developer productivity

Ask which repeated manual steps or integration delays existed, what was standardized or automated, who adopted it, and how lead time changed.

### Open-source or cross-team influence

Ask which contribution was personal, what was accepted or adopted, and which public artifact supports it. Keep code volume, PR count, rankings, awards, and stars as scope evidence rather than automatic impact.

## Metric prompts

For every user-provided number, ask:

1. What exactly was measured?
2. What was the usable baseline?
3. Were before and after measured under comparable conditions?
4. What hardware, traffic, model, dataset, sample, or window applied?
5. Was it an individual, team, or organization result?
6. What quality or correctness guardrail was preserved?

When no defensible number exists, help the user identify rollout scope, eliminated failure mode, adoption, release, or validated behavior. Do not invent a placeholder value.

## Depth prompts

Across a major project, seek several of these layers without forcing all into one bullet:

- user or business task;
- problem constraint;
- component personally owned;
- design choice and rejected alternative;
- implementation mechanism;
- scale or operating condition;
- validation method;
- result and guardrail.

If the user's text only lists technologies, ask which actual decision or failure each important technology addressed.

## Translation and style

- Translate only user-written and approved text.
- Preserve ownership qualifiers, metric conditions, and uncertainty.
- Use past tense for completed work and present tense for ongoing work.
- Prefer precise verbs over inflated labels.
- Keep conventional technology names unchanged.
- Do not expand terse source text into achievements the user did not write and confirm.
