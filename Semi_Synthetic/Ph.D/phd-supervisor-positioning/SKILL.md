---
name: phd-supervisor-positioning
description: Build and tailor an evidence-grounded academic research profile for a PhD student seeking a prospective supervisor or supervision transfer. Use when the user wants to synthesize CVs, proposals, publications, public academic profiles, research projects, teaching, and technical skills into a 2–4 page research dossier, 1-page profile, target-professor alignment matrix, or first-contact email. Also use to compare prospective supervisors, update the academic evidence bank, or adapt the profile to a professor, lab, or research group. Prioritize supplied files and authoritative public sources; never invent achievements, expertise, authorship roles, or reasons for a supervision change.
---

# PhD Supervisor Positioning

## Core goal

Position the user as a developing researcher whose trajectory, evidence, and future agenda can be understood quickly by a prospective PhD supervisor. Produce research-facing materials, not a generic CV rewrite.

Treat the task as evidence synthesis plus target-specific positioning.

## Workflow

1. **Identify the requested mode.**
   - Baseline profile update: build or refresh the user's academic evidence bank.
   - Targeted positioning: analyze one professor/lab and tailor the user's profile.
   - Comparison: compare multiple prospective supervisors.
   - Deliverable-only: generate one or more approved outputs from an existing evidence bank.

2. **Collect evidence before drafting.**
   Prefer, in order:
   - user-supplied CV/proposal/publications/files;
   - the bundled baseline in `references/baseline-profile.md`;
   - official university/lab pages and publication records for target professors;
   - user-provided LinkedIn, ORCID, Google Scholar, GitHub, or similar public profiles;
   - connected Google Drive files only when the user explicitly asks to use Drive or provides a Drive source.

   When source material is incomplete or inaccessible, say so. Do not silently replace missing evidence with general knowledge.

3. **Build an evidence bank.**
   Use the schema and confidence rules in `references/evidence-schema.md`.
   Separate:
   - documented facts;
   - public-profile confirmations;
   - evidence-based synthesis;
   - claims requiring user confirmation.

4. **Construct the research narrative.**
   Organize the user's trajectory around research evolution rather than chronology alone. For the current bundled profile, a useful default synthesis is:
   `digital forensics/applied AI -> data and annotation leadership -> Arabic NLP/LLM work -> methodological research on Arabic LLM benchmarking and evaluation reliability`.
   Treat this as synthesis, not as a quoted self-description.

5. **Analyze the target professor when provided.**
   Use official and recent sources where possible. Extract:
   - current research themes;
   - methods, datasets, languages, modalities, and evaluation interests;
   - recent papers/projects most relevant to the user;
   - overlap with the user's demonstrated work;
   - complementary expertise the user could bring;
   - plausible joint directions;
   - fit caveats or missing evidence.

   Do not use generic praise. Support alignment claims with specific evidence from both sides.

6. **Generate the requested outputs.**
   Follow `references/output-templates.md` for:
   - 2–4 page Academic Research Profile / Prospective Supervision Dossier;
   - 1-page concise research profile;
   - professor alignment matrix;
   - first-contact email.

7. **Run the quality gate before finalizing.**
   Apply `references/quality-gates.md`.

## Positioning rules

- Lead with research identity, current agenda, and evidence; do not lead with the need to leave a supervisor.
- Prefer the framing: **what the researcher knows, has done, is building, and can contribute**.
- Mention a supervision transfer only when context requires it or the user requests it.
- Never speculate about conflict with a current or former supervisor.
- Do not disparage any supervisor, institution, lab, or collaborator.
- Omit date of birth, marital status, full home address, and personal phone numbers from research dossiers and professor-contact emails unless the user explicitly requests them.
- Preserve publication metadata and authorship order exactly as supported by the source. Never infer first-author, corresponding-author, lead-author, acceptance status, or contribution role.
- Distinguish peer-reviewed publications, conference papers, presentations, theses, preprints, repositories, and works in progress.
- Distinguish **completed work** from **proposed/future work**. In particular, do not present planned proposal components as implemented results.
- Avoid inflated labels such as "expert", "leading researcher", or "state-of-the-art specialist" unless directly supported and appropriate.
- Translate skill-list wording into standard academic language only when meaning is preserved. If a source phrase is unusual, prefer a neutral description rather than embellishment.

## Target-professor alignment

When evaluating fit, use a multidimensional matrix rather than a single flattering score. Recommended dimensions:

- Research-topic overlap
- Methodological overlap
- Language/data overlap
- Benchmark/evaluation overlap
- Complementary technical strengths
- Evidence of contribution readiness
- Feasibility of a joint doctoral direction

Rate each dimension as `Strong`, `Moderate`, `Limited`, or `Unknown`, and give a short evidence-based rationale. Clearly label speculative future collaboration ideas as proposals, not facts.

For multiple professors, compare on the same dimensions and include trade-offs. Do not rank solely by prestige.

## Source handling

When the user supplies files, ground claims in those files and cite them using the platform's file-citation syntax when available. When web research is used, cite the supporting pages. For inaccessible sources such as blocked LinkedIn or Google Scholar pages, state the limitation and use another authoritative source only if it supports the same fact.

Do not copy temporary runtime citation tokens into reusable skill references or templates.

## Deliverable defaults

Unless the user specifies otherwise:

- Use polished academic English.
- Keep the 2–4 page dossier evidence-dense, readable, and professor-facing.
- Keep the 1-page version highly selective.
- Keep the first-contact email around 180–250 words.
- Make the email personalized to the professor using 1–2 specific overlap points.
- Include links to ORCID, Google Scholar, GitHub, or a research profile only when available and useful.
- Do not attach or reproduce sensitive personal contact details unless explicitly requested.

## References

- Read `references/baseline-profile.md` when working on Ruwa AbuHweidi's profile or when no newer profile source supersedes it.
- Read `references/evidence-schema.md` when ingesting or reconciling evidence.
- Read `references/output-templates.md` before generating any final dossier, one-page profile, alignment matrix, or contact email.
- Read `references/quality-gates.md` before finalizing a professor-facing output.
