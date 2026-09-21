---
name: upp-submission-preparer
description: Prepare and validate a UPP seminar submission from the team workbook, including PDF export, Drive placement, and F01 field values.
---

# UPP Submission Preparer

Use for “how do I submit this seminar?”, PDF export checks, or a final pre-submission review.

## Persistent project rule

After every completed homework, create or update `Инструкции_по_сдаче/СXX_<team-code>.md` using the repository template. Include the final workbook/sheet, PDF range, artifact path, Drive folder, F01 field values, correction/version rules, deadline source, and final accessibility check.

## Prepare the artifact

1. Use the assigned team workbook, not the generic template. Confirm the team code and current seminar on `Начало`.
2. Fill only the current seminar's answer cells. Export the answer area up to the last section before `Порядок выполнения и самопроверка`; exclude the instructions and repeated source data unless the card explicitly requires them.
3. Print selected cells in landscape orientation, fit to width, and inspect every page for clipped columns, missing rows, and unreadable text.
4. Save a versioned file such as `S02_M-K11_v01.pdf`, upload it to the team's accessible Drive submission folder, and use the immutable PDF link. A local path is not a valid form answer.

## F01 checklist

- corporate `@edu.hse.ru` address;
- current seminar, team code, version, and state date;
- `PDF 1` with the accessible PDF link;
- `PDF 2` empty unless a second PDF is explicitly required;
- `POD/исходник` empty unless the current card requires a source file;
- comment optional unless explaining a correction;
- `Закрываемый предыдущий семинар`: `Нет` when no previous work is corrected.

`F01` submits the result. `F02` is for cross-review and must not be used as the result-submission form. Starting with S02, a correction of an earlier seminar uses the previous seminar selector, a link to the corrected version, and a short explanation. Use `v02` or the next version for a resubmission; never replace the earlier file.

When documenting repository artifacts, use repository-relative Markdown links. Absolute local paths such as `/Users/...` are valid only for a local desktop response, not for links that should open on GitHub.

## Safety boundary

Do not submit a Google Form, change Drive permissions, or publish personal data without an explicit user request. Report access failures and preserve the prepared PDF locally.
