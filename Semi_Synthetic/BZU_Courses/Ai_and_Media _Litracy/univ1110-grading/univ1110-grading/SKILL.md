---
name: univ1110-grading
description: Grade and audit Birzeit University UNIV1110 AI and Media Literacy PDF submissions for Sections 6 and 8 using Google Sheets and Drive. Use for the six-student pilot, continuation or full grading, resuming saved progress, checking mismatches, or producing the two section-specific grading sheets for this Summer 2026 workflow. Do not use for other courses or assessments.
---

# UNIV1110 Grading

## Fixed resources

Treat both response spreadsheets as read-only:

- Section 6: `https://docs.google.com/spreadsheets/d/1BgHC3fX3gJV4GMCkcAQOLGHYPBGuLP3yRU4UZ2PgAt8/edit?usp=drivesdk`
- Section 8: `https://docs.google.com/spreadsheets/d/10c9_UvNVqqRmgFeKmrQu24G2EvFiLNjQjIKoV_QHDwA/edit?usp=drivesdk`

Store Section 6 results only in:
`https://drive.google.com/drive/folders/1UeNVJmA8q8UX9-2nj7BgZ81BX-2u6E1_?usp=drive_link`

Store Section 8 results only in:
`https://drive.google.com/drive/folders/1dyTwHuFua7RT9i7DYl2joijIIu2HAXObbO79-yLjJP6MvDNAnjAQFaTSmnKdmW56e_Ahyuvk?usp=drive_link`

## Select the workflow

- For a trial, sample, pilot, or first six students, read and follow [pilot-grading.md](references/pilot-grading.md).
- For approval of the pilot, continuation, remaining students, or full grading, read and follow [continuation-grading.md](references/continuation-grading.md).
- For an audit or correction, use the relevant workflow and change only the exact rows the user identifies.

## Invariants

1. Use Google Drive and Google Sheets connectors for live data and writes. Use PDF visual inspection or OCR when text extraction is insufficient.
2. Link every grade to the student name, university number, and original Google Sheets row from the same source row.
3. Open the linked PDF and inspect every page. If visible, compare the name and university number inside the PDF with the sheet row.
4. Never infer hidden or illegible content. Use `غير قابل للتقييم` for affected grade cells and explain why.
5. Use `تعذر فتح الملف` for missing access or an unavailable link. Use `يحتاج مراجعة يدوية` when the file opens but cannot be evaluated reliably.
6. Accept typed, scanned, photographed, or handwritten work. Ignore spelling, language, and formatting issues when meaning is understandable.
7. Apply generous grading consistently: understanding, relevant effort, and sound reasoning matter more than polish.
8. Never edit the two source response spreadsheets.
9. Keep the two sections separate and store each result file only in its assigned folder.
10. After every write batch, read back the written rows and verify student identity, source row, totals, and section.

## Shared rubric

Total: 10 points.

- Document completion: 1 point.
- First reflection about AI: 5 points.
- Prompt-engineering task: 4 points.

Use the detailed rubric and required output columns in the selected workflow reference. Do not award points for content that was not verified.

## Safety and stopping rules

- Stop and ask the user if a required source spreadsheet cannot be accessed.
- Stop continuation if the exact pilot result file is missing or duplicated in its assigned folder; do not silently create a replacement.
- Record identity conflicts rather than guessing which identity is correct.
- Do not process more students than the selected workflow authorizes.
- Report what was opened, how it was read, technical failures, manual-review cases, identity conflicts, and links to verified result files.
