# Continuation and full-grading workflow

Use this workflow only after the user explicitly approves the pilot and asks to continue.

## Resume exact result files

Within each fixed section folder, find exactly one file with the corresponding pilot name:

- `UNIV1110_Section6_Grading_Pilot`
- `UNIV1110_Section8_Grading_Pilot`

Confirm that each file belongs to the correct section and contains the three pilot rows. If a file is missing or more than one matching file exists, stop and ask the user. Do not create a replacement or choose arbitrarily.

## Determine remaining students

1. Read the source response sheet in row order.
2. Consider every row with a non-empty PDF link.
3. Match previously graded students using both the original row number and university number.
4. Preserve the pilot rows without regrading them unless the user explicitly requests a correction.
5. Begin with the first qualifying source row not already present in the result file.
6. Grade every remaining qualifying row; an inaccessible non-empty link still counts and receives the technical status.

## Apply the same rubric

Use the rubric, statuses, readability values, output columns, and feedback rules in [pilot-grading.md](pilot-grading.md). Inspect every page, use visual reading or OCR when needed, and never guess unreadable content.

## Save progress safely

- Append results only to the existing result sheet for the correct section.
- Never modify either source response spreadsheet.
- Work in manageable batches and read back each batch after writing.
- Verify original row number, university number, student name, PDF filename, component marks, final total, and section.
- Prevent duplicate students and preserve all previously verified rows.
- If interrupted, leave a clear checkpoint identifying the last verified source row in each section.

## Completion checks

Before declaring completion, compare each result file with its source sheet and verify:

- every source row with a non-empty PDF link appears exactly once;
- no extra or duplicated student appears;
- Section 6 contains no Section 8 rows and vice versa;
- totals equal the sum of the three rubric components whenever all components are numeric;
- technical and manual-review cases contain explanatory notes;
- both files remain in their designated folders.

## Rename the same files

After all checks succeed, rename the existing files without replacing them:

- `UNIV1110_Section6_Grading_Pilot` → `UNIV1110_Section6_Grading_Final`
- `UNIV1110_Section8_Grading_Pilot` → `UNIV1110_Section8_Grading_Final`

Verify the new names, preserved contents, and correct folder locations.

## Final report

Provide the two verified final-file links, counts by section and overall, manual-review and failed-open counts, identity or section conflicts, and confirmation that all qualifying rows were covered exactly once.

Do not regrade pilot students or modify source response sheets unless the user explicitly authorizes that separate action.
