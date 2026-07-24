# Hong Kong Batch Outreach Rule

Use this reference when Tianyi asks to organize Hong Kong faculty outreach, Hong Kong/GBA professor pools, or a compact Hong Kong batch schedule.

## Default Scope

Default target schools, treated as independent schools/campuses:

- HKUST
- CUHK
- HKU
- PolyU
- PolyU Dongguan / PolyU Greater Bay Area related platforms
- CityUHK
- CityUHK Dongguan / CityU Dongguan
- CUHK(SZ)

Treat all campuses above independently for scheduling and grouping. Do not include `CUHKGZ`; Tianyi has marked it as unclear/out of scope. Include `HKUST(GZ)` only if Tianyi explicitly names `HKUST(GZ)` in a later request.

## Candidate Pool Rule

Create one folder for the batch, normally:

```text
hong_kong_outreach_batch_<YYYY-MM-DD>/
```

The folder should contain:

- `README.md`: batch rule, send cadence, unresolved assumptions, and daily index.
- `faculty_pool.md`: all current-field Hong Kong/GBA faculty found for the selected schools.
- `day_01_email_drafts.md`, `day_02_email_drafts.md`, etc.: daily send batches.
- Optional `hold_or_form_only.md`: targets blocked by form-only policy, stale affiliation, no verified email, weak fit, or unclear PhD advising.

For `faculty_pool.md`, use this schema:

```text
Professor:
School:
Department / Lab:
Email:
Website:
Send / Hold:
Fit:
Lab anchor:
Funding / recruiting signal:
Student-first route:
Why me:
Draft status:
Evidence:
```

## Scheduling Rule

Goal: collect and draft all reachable Hong Kong/GBA targets in one complete batch, even if the final count exceeds 30.

Default cadence:

- Do not hard-limit daily volume while building the faculty pool.
- If daily sending files are requested, split the final ready pool into a compact multi-day schedule after the pool is complete.
- Put lower-confidence or form-only targets into `hold_or_form_only.md`, not into daily send files.
- Same-school repetition on the same day is allowed.
- Department repetition is not important for this batch.
- If volume and `roughly 30 emails` conflict, lower the fit threshold and finish the whole selected pool rather than stopping at 30.

Default daily structure:

```text
# Hong Kong Outreach - Day N

Send window:
Daily rule:

## Contact Table

| Priority | Professor | School | Department / Lab | To | Cc | Route | Fit | Status |
|---|---|---|---|---|---|---|---|---|

## Draft Emails
```

## Email Intent

Each draft should ask only about:

- Fall 2027 PhD opportunities.

Default wording:

```text
I am writing to ask whether your group may have Fall 2027 PhD opportunities related to [specific lab topic].
```

Do not mention Fall 2026 RA, visiting research, research assistantship, internship, or pre-PhD research unless Tianyi explicitly reopens that scope in a later request.

## Route Rule

Default to student-first with professor Cc when a current PhD student or senior lab member has a verified public email and strong topic overlap.

Use professor-direct when:

- No suitable current student email is verified.
- The lab page asks applicants to contact the PI directly.
- The best available student route is stale, alumni-only, or weakly related.

Use Hold/Form-only when:

- The page says not to email and provides a form.
- Current PhD advising is unclear.
- The professor has stale/non-current affiliation for the selected school.
- Email is not verified from official, lab-controlled, or personal pages.
- Fit is too indirect for this batch.

## Hong Kong Tone Rule

Write in polished English by default.

Make the email practical and opportunity-oriented:

- One sentence identity and timeline.
- One sentence asking about Fall 2027 PhD.
- One paragraph with 1-2 strongest background points.
- One paragraph with concrete lab overlap.
- Do not include Tianyi's sparse GitHub homepage link in the email body by default.
- Assume Tianyi will paste or attach his CV manually unless he explicitly asks for a CV attachment line.
- One closing sentence asking whether the route is worth discussing.

Do not overuse broad phrases like `embodied AI` unless the lab actually uses the concept or has robot learning/VLA/VTLA/manipulation overlap.

## Fit Rule

No priority order among mechanical engineering, ECE/EE, robotics, CS, AI, VLA, VLM, or manipulation if the lab clearly works on at least one of:

- VLA / vision-language-action models
- VLMs with robot/embodied deployment relevance
- robot manipulation
- robot learning
- embodied AI with physical robot tasks
- tactile/visuo-tactile/multimodal manipulation policy learning

For low-threshold expansion, include a target only when the email can still name one concrete technical bridge to Tianyi's background, such as manipulation data collection, tactile/force feedback, teleoperation, robot policy learning, simulation setup, dexterous hands, VLA/VLM-for-robotics, or embodied deployment. If the only overlap is broad AI/ML/CV/NLP with no robotics or embodied/manipulation bridge, put the target in `hold_or_form_only.md` or skip it.

Do not prioritize China-background search for this batch. Most target schools are in Hong Kong/GBA; use research fit and contactability instead.

## Resolved Preferences

- CityUHK Hong Kong main campus and CityUHK Dongguan should be researched together but treated as independent school/campus labels.
- PolyU Hong Kong main campus and PolyU Dongguan / Greater Bay Area related platforms should be researched together but treated as independent school/campus labels.
- Student-first routing is limited to current PhD students. Do not use postdocs, research assistants, lab managers, alumni, master's students, or visiting students as the primary `To` contact unless Tianyi explicitly allows it later.
- If no suitable current PhD student email is verified, draft professor-direct.
- Do not add Tianyi's GitHub homepage link to the email body by default; Tianyi will paste or attach his CV manually.

## Remaining Clarification Questions For Tianyi

No clarification questions are required by default for this batch. Continue with the resolved preferences above unless Tianyi changes the scope.
