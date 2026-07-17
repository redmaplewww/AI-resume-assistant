# Project narrative and role positioning

Use this guide when the reconstructed resume describes Agent, RAG, platform, framework, or other architecture-heavy work. Extract project facts from the old resume without preserving its project title, bullet order, or categories. Use examples only to diagnose and formulate questions. Never copy them into candidate prose; require the user to write the new project framing and first version.

## Table of contents

- The first-pass test
- Choose a role lane
- Build the project opening
- Connect demand to design
- Show iteration and judgment
- Use metrics with honest baselines
- Place technology keywords
- Allocate space by importance
- Before-and-after pattern
- Final checklist

## The first-pass test

After reading only the project title and opening sentence, ask:

1. Who uses this?
2. What concrete task or decision does it support?
3. What was inadequate about the previous workflow or tools?
4. Which constraint makes the problem technically non-trivial?

If the answer is only “a Multi-Agent platform with RAG, memory, search, and tools,” fail the project. That describes components, not purpose. Without an expected outcome, architecture choices cannot be evaluated.

Guide the user from an architecture-only title toward this empty title scaffold:

`[domain task] + [critical constraint when distinctive] + [solution category]`

The resulting title still needs an opening sentence that identifies the real user, task, source, and constraint.

## Choose a role lane

### Application or product Agent engineering

Lead with user workflow, task completion, reliable retrieval and tool use, routing failures, evaluation, fallback, safety, latency, and delivery. Infrastructure is supporting evidence when it helps complete the application task.

### Agent infrastructure or platform engineering

Lead with a concrete runtime or platform bottleneck; state, scheduling, DAG, checkpoint, permission, tool, or deployment boundaries; consistency and recovery tradeoffs; and downstream adoption.

Do not present a private framework as valuable merely because it resembles a known coding-agent architecture. Treat infra as a specialized lane unless the supplied JD set shows otherwise; target it explicitly or connect the platform to a real application and adoption.

### Algorithm or research

Lead with method contribution, failure of existing methods, dataset and evaluation design, credible baselines, ablations, model behavior, and reproducibility. Agent orchestration and application architecture do not by themselves establish algorithm depth.

### Portfolio rule

Choose one dominant lane. Make the first project the strongest proof for that lane. Keep a secondary project only when it reinforces the same hiring thesis. Compress, connect, or remove a technically interesting but off-axis project.

## Build the project opening

Guide the user to write the opening as one natural paragraph, not a detached “核心需求” section. Offer only this rough scaffold:

`[product] 面向 [user] 的 [task], 需要 [source/data] 满足 [authority/freshness/language/scale constraint]; 因 [existing approach failure], 构建 [solution category] 支撑 [decision/outcome].`

Do not claim “刚需”, “核心痛点”, or “行业领先” as labels. Let the described task and constraint establish importance.

## Connect demand to design

Use the reasoning chain:

`specific need → observed failure → decision or iteration → mechanism → validation`

Examples:

- Cross-language policy recall → sparse lexical retrieval misses semantically equivalent terms → introduce multilingual dense retrieval and fuse independent results → report retrieval evaluation.
- Exact, time-sensitive exchange-rate query → generic web search summarizes inconsistently → route to a dedicated tool with authoritative-source fallbacks → report final query success and freshness behavior.
- User background text causes routing bias → planning agent is triggered incorrectly → archive bad cases, simplify prompts, and evaluate on a fixed intent set → report accuracy and token cost.
- Local-file dependency updates are slow and complex DAGs are weak → redesign distribution and task state → explain the transactional mechanism, recovery model, and scheduling behavior.

Avoid “technology → capability” bullets that never return to the need. Chunking, embedding, BM25, reranking, memory, and tools are not achievements by themselves.

## Show iteration and judgment

A failed option can demonstrate engineering judgment when it was plausible and the reason for rejection is concrete.

Use:

`为解决 [need] 试用 [option], 在 [conditions] 下发现 [measured/observed failure]; 因 [tradeoff], 改用 [final approach], 获得 [result].`

This reasoning is stronger than listing both the rejected and selected technologies without context. Keep the rejected path concise; it supports the decision rather than becoming the project story.

Do not invent alternatives to create a tradeoff narrative. Sometimes a strong result plus a clear requirement is sufficient.

## Use metrics with honest baselines

Use three metric forms:

1. **Comparable improvement**: old and new approaches were both viable and measured under the same conditions.
2. **Final attainment**: report the achieved value and test definition when the prior tool was categorically unsuitable.
3. **Failure-rate repair**: report the affected scenario, sample count, and final success or error rate.

Do not use `0% → result` when zero came from a tool that could not perform the task. This looks engineered by selecting a broken baseline. Guide the user to report `final attainment + test definition + conditions`, or compare against the previous usable solution.

Do not force comparisons for framework selection, architecture, or qualitative tradeoffs when measurement would be misleading. Explain selection through workload, consistency, recovery, deployment, and maintenance constraints.

## Place technology keywords

Serve two readers:

- Recruiters need recognizable role keywords for basic matching.
- Hiring managers need the problem, decision, mechanism, and outcome.

Prefer this order:

1. Put important technologies in the bullets that explain their use.
2. Add one compact project-level stack line when scanning or ATS coverage still benefits.
3. Keep a concise global skills section as an index of evidence already present.

Do not let keyword coverage dominate the narrative. A long framework list cannot rescue an unclear project and makes AI-generated resumes look interchangeable.

## Allocate space by importance

Write a complete project, then weight the hard and differentiating parts more heavily. Do not give every component equal space.

- Give the opening 1–2 lines.
- Use 2–4 strong bullets for the core project.
- Give more space to constraints, decisions, failures, and validated results.
- Compress standard setup, CRUD, generic memory, basic deployment, and framework-provided capabilities.
- Promote a tiny detail only when it proves a target competency such as search reliability, data validation, consistency, or recovery.

Avoid rigid blocks named “需求”, “难点”, “方案”, and “结果”. Integrate each constraint into the technical bullet it justifies so the section reads as one project rather than disconnected answers.

## Diagnostic contrast

Architecture-first text usually follows:

`framework + component inventory + generic capabilities`

It fails when the user, task, constraint, and expected outcome remain unknown.

Guide the user toward this reasoning structure without filling it:

`user/task + unmet need + critical constraint → selected mechanisms → validation`

Then ask the user to write the first version and revise it locally. Do not reconstruct the prose for them.

## Final checklist

- Can a technical reviewer explain the product after the first two lines?
- Is the dominant role lane unmistakable?
- Does every major technical choice answer a stated constraint?
- Are failed alternatives real, concise, and informative?
- Are metrics measured against a fair baseline or reported as final attainment?
- Is the project coherent rather than split into artificial template sections?
- Do important bullets receive more space than generic implementation?
- Are technology keywords present without becoming the content?
- Would removing a framework name still leave a distinctive project story?
