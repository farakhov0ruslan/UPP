---
name: upp-course-navigator
description: Navigate this UPP/UniFlow course repository and explain the current seminar, source materials, workbook sheet, deliverable, and submission route.
---

# UPP Course Navigator

Use for questions such as “what is the current homework?”, “where is the answer sheet?”, “which materials matter?”, or “where do we submit?”.

## Workflow

1. Read `CLAUDE.md` and `AGENTS.md` before using the repository map.
2. Inventory the current files; treat the map in `AGENTS.md` as potentially stale when new lectures, seminars, or workbooks were added.
3. Identify the active lecture/seminar from the newest materials and from the `Начало` sheet of the team workbook. Never infer the team code from a filename alone.
4. Prove that the matching lecture and seminar/card files exist. Report their exact paths; if either is missing, ask the user for it before solving.
5. Read the active seminar card/slides, the matching lecture, prior seminar sheets, `Кейс`, `00_Старт_студента_Москва_8.1.pdf`, and the assessment rules.
6. Separate official course instructions from a newer deadline or clarification supplied by the user. State conflicts explicitly.
7. Report exact locations: workbook, sheet, answer blocks/ranges, export format, folder, form, and optional fields.

## Repository anchors

- The case is fictional UniFlow; the task is management analysis, not application development.
- The team workbook is the authoritative working surface. Use its `Начало` sheet for the team code, current version, form links, and team Drive links.
- `Кейс` contains the facts and decision catalogue. Codes such as `U/E/M/P` must not be invented or silently reinterpreted.
- Treat facts, hypotheses, unknowns, and conditional exercises as different things. A missing value is not automatically zero.
- Preserve traceability: connect current requirements to prior sheets, carried assumptions, and later consequences; flag contradictions instead of silently replacing earlier answers.
- `F01` is result submission; `F02` is cross-review. Do not conflate them.

## Output

Give a short “do this next” sequence, then a source map and a final submission checklist. Do not edit the workbook or send an external form unless the user explicitly asks.
