# Resume reconstruction and human voice

Use this reference to prevent an old resume from constraining the new one and to detect model-like writing patterns. Diagnose and question; do not author the user's framework or prose.

## Table of contents

- Content-source model
- Evidence atomization
- Framework independence
- User-led framework review
- Model-like writing signals
- Human-voice recovery
- Local-edit guardrails
- Final checks

## Content-source model

Treat every supplied artifact according to its authority:

| Artifact | May supply facts | May determine new structure | May supply final wording |
|---|---:|---:|---:|
| Old resume | Yes | No | Only after explicit reuse and reconfirmation |
| Raw notes or interview answers | Yes | No | No |
| Repository or documentation | Yes, when verified | No | No |
| JD | Requirements only | No | No |
| User-written new framework | N/A | Yes, after review | Headings only after approval |
| User-written new prose | Yes | Within confirmed framework | Yes, after review |
| Assistant local edit | No new facts | No | Only after user confirmation |

Do not confuse document completeness with authority. The old resume may be complete and still have the wrong narrative, grouping, or voice.

## Evidence atomization

Extract facts at the smallest useful level:

- one role and date range;
- one user or business task;
- one personal action;
- one design decision;
- one rejected option and reason;
- one measurable result with conditions;
- one artifact or external proof.

Detach each atom from its original section. Record its source location only for traceability. Do not carry over bold labels, bullet order, paragraph boundaries, or section names.

For compound legacy bullets, separate:

`product function | personal contribution | mechanism | team result | metric | unsupported language`

This lets the user decide later which atoms belong together.

## Framework independence

Diagnose common forms of legacy-frame lock-in:

- copying the same `教育—技能—项目—自评` order despite a different target or experience level;
- preserving one legacy bullet per new bullet;
- retaining project categories invented by a template;
- assigning equal space because the old document did;
- treating the global skills list as a required inventory;
- keeping weak projects merely because they already occupy a section;
- using old project titles that describe architecture rather than purpose;
- translating the old resume's order into another language without reconstruction.

Do not prescribe a universal alternative. Show what the framework must accomplish, then ask the user to propose it.

## User-led framework review

When the user proposes a new framework, review it through questions:

1. What should the reader conclude after the first third?
2. Which evidence is the strongest proof of the target role?
3. Why does each section exist?
4. Which project or phase deserves the most space, and why?
5. Which evidence is intentionally omitted?
6. Are application, infrastructure, and algorithm claims reinforcing one target?
7. Does the order reflect current relevance rather than the old resume?

Give tradeoffs, not a replacement outline. If two arrangements are plausible, explain the consequence of each and let the user choose.

## Model-like writing signals

No single signal proves AI authorship. Treat these as style problems:

### Uniform architecture

- every project has identical subheadings;
- every bullet follows the same number of clauses;
- every bullet contains a challenge, technology list, and percentage result;
- sentence lengths and punctuation patterns repeat mechanically;
- all projects receive equal space regardless of importance.

### Generic abstraction

- nouns such as `体系、能力、场景、链路、闭环、赋能` lack concrete referents;
- verbs such as `打造、构建、实现、支持、提升` repeat without distinct decisions;
- adjectives such as `高效、全面、深度、显著、灵活、稳定` replace evidence;
- claims sound like product marketing rather than an engineer recounting work.

### Keyword stitching

- framework names appear in long sequences detached from decisions;
- JD terms are mirrored even when the project evidence is weak;
- English nouns are inserted where ordinary language would be clearer;
- technologies inherit capabilities from the underlying library.

### Artificial completeness

- every project has a perfect problem-solution-result ending;
- no uncertainty, failed attempt, maintenance cost, or tradeoff appears;
- metrics are suspiciously rounded or consistently dramatic;
- all bullets sound equally important and equally polished.

### Voice replacement

- the candidate cannot explain a phrase in ordinary speech;
- wording is more senior or certain than the stated ownership;
- distinctive project incidents disappear after editing;
- the text could be pasted into another candidate's resume unchanged.

## Human-voice recovery

Do not “humanize” by adding slang, typos, filler, or random sentence variation. Recover human authorship through evidence and choice:

- ask the user how they would explain the work to a technical peer;
- ask which decision they still remember and why;
- preserve project-specific nouns, failure modes, and constraints;
- keep uneven emphasis when one part genuinely mattered more;
- allow a short factual bullet when nothing more is needed;
- retain qualified uncertainty when causality is partial;
- ask the user to replace phrases they would never say in an interview;
- prefer one distinctive detail over several generic claims.

The goal is not to evade AI detection. The goal is that the candidate recognizes, understands, and can defend every line.

## Local-edit guardrails

When reviewing new user prose:

1. Quote only the current line.
2. Name the style or evidence problem.
3. Ask what the user actually means in ordinary technical language.
4. Offer an edit direction before offering wording.
5. If wording is needed, change the smallest possible span.
6. Ask whether the revised phrase still sounds like the user.

Do not normalize all bullets into one formula. Do not add transitions merely for smoothness. Do not make every bullet the same length.

## Final checks

- Was the new framework written by the user rather than inherited or supplied?
- Can every final evidence atom be traced to a source?
- Can every final sentence be traced to new user prose or a confirmed local edit?
- Would the structure still make sense if the old resume disappeared?
- Do projects differ in rhythm because their actual work differs?
- Are concrete nouns more common than abstract praise?
- Can the user explain every phrase without reading it?
- Does the resume omit weak material intentionally rather than preserving legacy completeness?
