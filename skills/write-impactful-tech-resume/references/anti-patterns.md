# Resume credibility anti-patterns

This playbook distills recurring failure modes from historical technical-resume reviews. Use it to locate claims that need clarification or repair, not to declare dishonesty from style alone.

## Table of contents

- Evidence standard
- Severity model
- Timeline and chronology
- Ownership and workload
- Template and provenance
- Metrics and engineering plausibility
- Skill and technology inflation
- Production-depth theater
- Target and identity mismatch
- Formality and information quality
- Repair protocol
- Audit output template

## Evidence standard

Separate four concepts:

1. **Objective contradiction**: two sourced facts cannot both be true, or a technology is claimed before it existed.
2. **Plausibility risk**: the claim is possible but unusually broad, fast, large, or senior for the context.
3. **Evidence gap**: the claim may be true but lacks scope, method, baseline, attribution, or proof.
4. **Editorial weakness**: vague, repetitive, poorly formatted, or badly targeted writing without a truth implication.

Use multiple independent signals before escalating a plausibility concern. Repetition plus impossible workload is stronger than repetition alone. A polished style, use of AI writing tools, or absence of metrics does not prove fabrication.

Do not penalize a candidate for being credible but mismatched to one JD. Do not infer ability, integrity, salary expectations, or employability from age, gender, nationality, photo, school prestige, email provider, or unrelated protected characteristics.

## Severity model

| Level | Definition | Action |
|---|---|---|
| Blocker | Objective contradiction or impossible chronology | Stop strengthening the claim; request correction or remove it |
| High | Two or more independent plausibility signals affect a central claim | Qualify the claim and request source evidence before release |
| Medium | Important evidence gap or isolated anomaly | Mark for verification; guide a conservative local edit |
| Low | Editorial, relevance, or formatting issue | Give a local edit direction without implying dishonesty |

Treat one decisive contradiction as a blocker. Require corroboration for high-risk inferences.

## Timeline and chronology

### Technology time travel

Signal: a project claims a framework, model, protocol, or product before its public availability.

Check:

- exact project dates and whether the stack was used during the original build or a later refactor;
- preview/beta availability versus stable release;
- whether the name is an anachronistic label for an earlier internal mechanism.

Repair: ask the user to restore the original stack and, when applicable, mark a later refactor as a separately dated event. Do not draft the corrected chronology for them.

Never hard-code release dates from memory when making a consequential judgment; verify them from authoritative sources when current web access is allowed.

### Future, reversed, or overlapping dates

Signals:

- completed achievements are dated after the resume's as-of date;
- an end date precedes a start date;
- full-time employment overlaps full-time study without labeling internship, part-time, leave, or concurrent status;
- several projects overlap while each is described as full-time, independent, or led end-to-end;
- total claimed experience conflicts with age, graduation, or listed chronology.

Repair: establish an explicit as-of date, label employment type, distinguish planned work from completed work, and explain legitimate parallel projects with allocation or phase.

### Suspiciously perfect succession

Back-to-back dates are not inherently suspicious. Escalate only when combined with incompatible locations, multiple full-time roles, unexplained role changes, or physically implausible project load.

## Ownership and workload

### Identity-role mismatch

Signal: a short internship, junior role, or course project uses `主导`, `独立负责`, `总体架构`, or organization-wide impact without a bounded component or team context.

Ask:

- What component was personally owned?
- Who approved the architecture and who else implemented it?
- Was the work production, prototype, course, research, or open source?
- How much of the result belongs to the team?

Repair: replace the inflated verb with the accurate boundary, e.g. `参与平台建设，独立实现检索重排模块`.

Do not assume interns cannot do important work. Test the scope, not the title.

### Workload-volume mismatch

Signals:

- multiple complex systems allegedly built from zero within weeks;
- one person claims simultaneous ownership across unrelated domains;
- a short project contains research, data construction, training, backend, frontend, deployment, operations, and business adoption with no team attribution;
- code, PR, model, user, or project volume exceeds the stated duration without an explanation.

Repair: split team output from personal output, identify reused infrastructure, show phases, and reduce claims to the defensible component.

## Template and provenance

### Project clones

Signals:

- unrelated projects repeat the same sentence structure, stack, duties, and outcome pattern;
- names change but business constraints, failure modes, and design decisions do not;
- paragraphs are duplicated verbatim across companies or projects;
- every project presents an implausibly perfect problem-solution-result loop.

Repetition alone is an editorial problem. Escalate when it combines with missing unique constraints, impossible dates, or inflated ownership.

Repair: require one project-specific constraint, decision, failure mode, and validation method for every major project. Remove duplicates rather than paraphrasing them.

### Tutorial or open-source repackaging

Signals:

- common demo combination with only generic functions;
- no unique dataset, user, constraint, modification, commit, evaluation, or failure handling;
- a public project is renamed and presented as a proprietary production system;
- the description recites framework features instead of personal changes.

Repair: label it `学习项目`, `开源二次开发`, or `基于 X 改造`; describe the actual delta, reason, test, and result. A well-executed adaptation is valid evidence when represented honestly.

### Anonymous-business theater

Using `某公司` may be necessary for confidentiality. Treat it as a gap only when every employer, user, scale, and result is anonymized so thoroughly that nothing is verifiable. Preserve confidentiality while adding non-sensitive context such as industry, team size, environment, or public artifact.

## Metrics and engineering plausibility

### Orphan metrics

Signals:

- `提升 80%` without metric definition or baseline;
- a percentage whose before/after arithmetic does not match;
- latency, throughput, accuracy, or memory without workload, hardware, dataset, sample size, or measurement window;
- team or organization outcomes attributed entirely to one person;
- research-set accuracy presented as production business impact.

Repair: add metric definition, before and after, conditions, measurement method, attribution, and a quality guardrail. Otherwise downgrade to a sourced qualitative result.

Do not use a categorically unsuitable or deliberately broken tool as a zero baseline. Treat it as failed-selection evidence and report the final result, or compare with the prior viable approach.

### Perfect or physically implausible results

Examples of signals, never automatic verdicts:

- 100% accuracy or zero errors in a non-trivial open-world task;
- end-to-end LLM work in latency that conflicts with the model, hardware, and network path;
- near-perfect retrieval metrics on noisy domain data with no evaluation design;
- massive concurrency, traffic, or cost savings with no architecture or load-test context;
- a dramatic gain reported with excessive precision but no measurement path.

Ask for the test set, denominator, baseline, hardware, concurrency, warm/cold state, repetitions, confidence interval, and whether the metric was offline or online. Preserve a surprising result only when its conditions make it credible.

### Metric laundering

Do not convert counts into impact automatically. Lines of code, PRs, documents, users, awards, and repository stars show scale or external evidence, but not necessarily quality, causality, revenue, or performance.

## Skill and technology inflation

### `精通` as an unbounded claim

`精通` is risky when applied to broad languages, frameworks, databases, cloud platforms, or entire AI domains without deep project evidence. Replace it with demonstrated use:

- weak: `精通 Java、Python、LLM、前后端与云原生`;
- defensible: `以 Java 开发交易服务 3 年；使用 Python 完成 2 个推理优化项目`.

### Orphan skills

Build a skill-to-evidence matrix. Mark each skill:

- **proven**: appears in a substantive project with a mechanism or result;
- **used**: appears in a credible task but without depth evidence;
- **claimed only**: appears only in the skills section;
- **irrelevant**: does not help the target role.

Remove or downgrade claimed-only and irrelevant items. Do not use a universal numeric cap; breadth can be legitimate for senior platform roles when the chronology and evidence support it.

### Impossible breadth

Signal: short experience claims expert depth across unrelated stacks such as kernel/C++, model research, Java enterprise systems, frontend, mobile, data engineering, cloud operations, and multiple AI frameworks.

Repair: select the target-role core, demote adjacent skills to `了解/使用过` only if truthful, and connect every retained skill to evidence.

## Production-depth theater

### Architecture without a job to do

Signal: the project title and opening enumerate Multi-Agent, RAG, memory, search, planning, or tools, but a reader cannot identify the user, task, unmet need, or expected outcome.

This is a positioning and depth failure even when every component is real. Without demand, the reader cannot judge whether the architecture is necessary, overbuilt, or copied from a framework.

Repair: rename the project around its domain task; identify the real user and constraints in the opening; connect each major mechanism to an observed failure or decision. Read [project-narrative.md](project-narrative.md).

### API or low-code work presented as model engineering

Distinguish:

- calling a hosted model API;
- configuring an orchestration/low-code product;
- building RAG or agent application logic;
- training or fine-tuning a model;
- serving and optimizing inference;
- operating a production system.

Each is legitimate but different. Use the accurate layer and do not inherit capabilities from the underlying platform.

### Demo presented as enterprise production

Signals:

- only feature implementation is described;
- no testing, deployment, monitoring, failure handling, security, data governance, cost, load, rollout, or user feedback appears;
- `enterprise-grade`, `high concurrency`, or `production-ready` is asserted without operating evidence.

Do not require every production keyword. Look for at least two project-relevant lifecycle signals and one concrete operating constraint before using enterprise-grade language.

### Fashionable but shallow

Signal: many current terms—RAG, Agent, MCP, tool calling, reranking, multimodal, fine-tuning—appear without parameters, selection rationale, evaluation, failures, tradeoffs, or deployed behavior.

Repair: keep fewer terms and attach each to a real constraint and decision. Do not add fake parameters merely to appear deep.

## Target and identity mismatch

### Wrong resume for the JD

Signals:

- stated target title differs from the application;
- evidence is concentrated in another function, such as frontend, testing, data analysis, or research;
- availability, internship/full-time intent, location, or seniority conflicts with the role.

Classify as **mismatch**, not dishonesty. Preserve the authentic background and either target a better-fitting role or show a truthful transition narrative. Do not rename non-AI work as AI work.

### Experience inflation during transition

Separate total career experience, relevant technical experience, and experience in the target specialty. Example: `7 年软件开发，其中 1 年大模型应用经验` is clearer than `7 年 AI 经验`.

## Formality and information quality

Low-severity but consequential patterns:

- generic self-evaluation and mottos consume space without evidence;
- long course lists crowd out results for experienced candidates;
- typos, broken numbering, inconsistent dates,乱码, or unreadable scanned text undermine care and ATS parsing;
- missing role, dates, employment type, location/availability, portfolio links, or contact channel blocks evaluation;
- internal jargon, boastful labels, or casual phrases weaken professional tone;
- a long document repeats functions while hiding the strongest evidence.

Repair directly. Do not equate email domain, photo style, or template choice with technical ability.

## Repair protocol

For each issue:

1. Quote or precisely locate the claim without reproducing personal identifiers.
2. Classify it as contradiction, plausibility risk, evidence gap, mismatch, or editorial issue.
3. Explain the reasoning chain and confidence level.
4. Ask one concrete verification question.
5. Choose one action: substantiate, narrow, reattribute, redate, relabel, locally revise, or remove.
6. Revise only text the user supplied. Ensure the edited statement is weaker than or equal to the available evidence, never stronger.

## Audit output template

| Priority | Type | Resume evidence | Why it matters | Verification question | Repair direction |
|---|---|---|---|---|---|
| Blocker/High/Medium/Low | Contradiction/risk/gap/mismatch/editorial | Sanitized claim | Short reasoning | One answerable question | Specific action or local edit direction |

End with:

- **Release blockers**: claims that must be resolved before sending;
- **Interview probes**: questions for unusual but potentially strong claims;
- **Safe edits**: improvements that do not depend on new facts;
- **Evidence requests**: only artifacts or details that materially improve credibility.
