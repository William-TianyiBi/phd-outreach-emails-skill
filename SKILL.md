---
name: phd-outreach-emails
description: Use when researching PhD faculty targets, lab PhD students, professor/student emails, professor dossiers, PI due diligence, or drafting academic outreach emails for manipulation, UMI, embodied AI, robotics, RA, summer research, or 27fall PhD opportunities.
---

# PhD Outreach Emails

## Purpose

Prepare evidence-based PhD outreach packages for Tianyi Bi. The output is a contact table and concise email drafts. Do not send email unless Tianyi explicitly asks after reviewing the draft.

This skill also handles one-professor due diligence dossiers for PhD outreach decisions. Use dossier mode when the user asks to evaluate a professor, decide whether a professor is worth contacting, perform 导师调研, inspect funding/lab composition/student backgrounds/recruiting signals, or create a professor dossier.

## Required References

Read `references/tianyi-profile.md` before drafting emails. Use it for background, tone, and allowed claims.

Read `references/source-quality.md` before evaluating evidence, uncertainty, funding, lab membership, student background, or demographic information. If an official page is blocked, JavaScript-only, login-gated, timed out, or partially readable, read `references/blocked-page-fallbacks.md` before concluding anything is unavailable.

## Workflow

1. Clarify only if the target scope is missing. Defaults: manipulation, UMI-style data collection, tactile/force-feedback teleoperation, robot learning, dexterous manipulation; regions include Hong Kong, Singapore, United States, Saudi Arabia; opportunity is Fall 2027 PhD.
2. Research targets from primary sources first: faculty/lab pages, university profiles, lab people pages, paper pages, Google Scholar, official PDFs. Browse because people, students, and emails change.
3. For each professor, identify one relevant current PhD student or senior lab member when possible. Prefer students who work on manipulation, imitation learning, teleoperation, UMI/datasets, tactile sensing, dexterous hands, or sim-to-real.
4. Verify every email address from an official or lab-controlled page. If unverified, mark it `not found`; do not guess email formats.
5. For every target, provide at least one homepage-style evidence URL: lab website, professor's university profile, professor's personal homepage, student's university profile, or student's personal homepage. Do not rely only on search snippets, paper pages, or source names when a homepage can be found.
6. Draft mail with `To: PhD student` and `Cc: professor`. If no suitable student is found, draft `To: professor` and note why.
7. Keep each email short: 180-260 words unless the user requests otherwise. Use concrete overlap with the lab, not generic praise.
8. Include the CV/homepage attachment/link line only if the user asks, or if there is already a known CV/homepage link in context.

## Dossier Mode

When the user asks for professor due diligence rather than only a contact table:

1. Disambiguate only if needed: professor name, institution/department, and field/program context.
2. Search current web sources because funding, lab membership, papers, and recruiting status change.
3. Build an evidence table before writing conclusions. Track claim, status (`Confirmed`, `Inferred`, `Unknown`), source URL, access date, and notes.
4. Prioritize official faculty, department, lab, graduate program, publication index, funding database, lab people/alumni, public CV, ORCID/Scholar/PubMed/Semantic Scholar/DBLP, thesis, and conference-bio sources.
5. For current or recent PhD students, search public profiles before estimating admissions background: lab/team pages, alumni pages, public LinkedIn, personal sites, Google Scholar, ORCID, PubMed, thesis pages, and conference bios. Do not scrape private data or ask for login.
6. Assess research map, recent papers, funding visibility, lab composition, current/recent PhD student baseline, recruiting signals, fit for Tianyi when relevant, and outreach usefulness.
7. Recommendation must be `High`, `Medium`, `Low`, or `Do not contact yet`, with confidence `High`, `Medium`, or `Low`.
8. If an HTML dossier is requested, fill `assets/professor-dossier-template.html`; save by default to `dossiers/<Institution>_<ProfessorLastName>_dossier.html` in the current workspace unless the user provides a path.

## Dossier Output Contract

For dossier mode, include:

- Basic profile: institution, department, rank, lab, contact, and links.
- Research map: themes, methods, model systems/data, and recent direction shifts.
- Publications: Scholar/profile link if available, recent/high-signal papers, venues, collaboration pattern, and dated publication snapshot.
- Funding: active/recent grants, source, recency, role, and funding risk (`Low`, `Medium`, `High`, or `Unknown`).
- Lab composition: current members, roles, public education/professional background, and alumni outcomes where public.
- PhD student baseline: public prior institutions, degree path, pre-PhD publications where attributable, prior research roles, relevant methods/domain background, and confidence.
- Recruiting/funding signals: explicit openings, program mechanism, rotation/direct-admit clues, and recent student intake.
- Outreach recommendation and a short reasoned next step.
- Evidence log with direct source links and access date.

If the user requests Chinese output, write the final dossier and chat summary in Chinese while preserving official names, paper titles, database names, grant titles, and institution/program names in English when translation would reduce precision.

## Output Contract

Return two sections:

**Contact Table**

| Priority | Professor | Institution | Fit | PhD student To | Professor Cc | Evidence |
|---|---|---|---|---|---|---|

Fit is one sentence. Evidence must include direct homepage-style links: lab website, professor's university profile, professor's personal homepage, student's university profile, or student's personal homepage. Mark uncertain data explicitly.

**Draft Emails**

For each target:

```text
Subject: Prospective PhD applicant interested in [specific lab topic]
To: [student name/email]
Cc: Prof. [name/email]

Dear [student name],

[3-4 concise paragraphs]

Best regards,
Tianyi Bi
```

## Style Rules

- Write as Tianyi: direct, specific, technically grounded, polite.
- Prefer "I am writing to ask whether your group may have Fall 2027 PhD opportunities..." over casual phrasing.
- Mention 1-2 strongest background points only: UMI/tactile gripper, simulation data collection/environment setup, SPARK Hand/IROS 2025, ASME SMRDC champion, tactile/VTLA/manipulation.
- Make the student-email opening natural: ask whether they would be open to sharing their experience in the group and whether the work aligns with prospective PhD recruiting.
- Do not overclaim unpublished work, acceptance, authorship, or affiliation.
- Do not use flattery like "huge fan", "super excited", or "cool ideas".
- Do not mention "mass email", "template", or "agent".

## Safety And Ethics

- Do not invent students, emails, publications, positions, or funding.
- Do not recommend deceptive personalization. If evidence is thin, say so.
- Do not send or automate sending without a separate explicit user instruction for the exact approved email.
- Do not scrape private data or use non-public contact information.
