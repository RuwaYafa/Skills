# Pilot grading workflow

## Scope

Grade exactly the first three rows with a non-empty PDF link in Section 6 and exactly the first three such rows in Section 8, following source-sheet row order.

If a non-empty link cannot be opened or access is denied, keep that student in the sample. Do not replace the student with a later row. Record `تعذر فتح الملف`.

Do not grade more than three students per section and do not edit either source spreadsheet.

## Rubric

### Document completion — 1 point

- `1/1`: The required document or answers are present in a clear form, whether on the original template or in a separate typed or handwritten file.
- `0.5/1`: Work exists, but essential data or sections are missing.
- `0/1`: No answers are available for evaluation.

### First reflection about AI — 5 points

1. AI definition — 1 point: accept any understandable student-written definition showing a basic grasp of AI, even if technically imprecise.
2. Two human tasks — 2 points: award 1 point for each logical task, such as emotion, empathy, ethical judgment, human creativity, responsibility, or complex physical skills. Accept other examples with understandable reasoning.
3. Benefits to the student's discipline — 2 points:
   - `2/2`: a clear benefit connected to the student's discipline or career.
   - `1/2`: a correct but general benefit.
   - `0/2`: no relevant response.

### Prompt engineering — 4 points

- 1 point for the first prompt.
- 1 point for a second prompt that adds details or constraints.
- 1 point for a clearer or more specific third prompt.
- 1 point for an overall logical progression among the three.

Award `4/4` for three versions of the same topic progressing from general or simple to more detailed and clear. Do not enforce technical labels rigidly. If three versions exist but progression is weak, award no less than `3/4` when a clear attempt exists.

## Status and readability values

Document status must be one of:

- `مكتملة`
- `مكتملة جزئيًا`
- `غير مكتملة`
- `يحتاج مراجعة يدوية`
- `تعذر فتح الملف`

Readability must be one of:

- `قراءة نصية`
- `قراءة بصرية أو OCR`
- `قراءة جزئية`
- `غير قابل للقراءة`
- `تعذر فتح الملف`

Do not label a technical or legibility failure as `غير مكتملة`.

## Output columns

Create separate Section 6 and Section 8 tables using exactly these columns:

1. رقم الصف في Google Sheets
2. الرقم الجامعي
3. اسم الطالب
4. اسم ملف PDF
5. إمكانية القراءة
6. حالة الوثيقة
7. اكتمال الوثيقة /1
8. التأمل الأول /5
9. هندسة الأوامر /4
10. الدرجة النهائية /10
11. تغذية راجعة قصيرة
12. ملاحظات المصحح

Feedback must be one or two supportive sentences, start with a specific positive observation, and include at most one improvement grounded in the submission.

## Save and verify

Create these two independent Google Sheets:

- `UNIV1110_Section6_Grading_Pilot` in the fixed Section 6 folder.
- `UNIV1110_Section8_Grading_Pilot` in the fixed Section 8 folder.

Each file must contain only its section's three sampled students. Read back both files, verify their folder locations and contents, then provide both links.

## Pilot summary and stop

Report PDF links processed, successful opens, text reads, visual/OCR reads, manual reviews, failed opens, identity or section mismatches, rubric ambiguity, and both verified result-file links.

Then stop and wait for explicit approval. Do not continue grading automatically.

