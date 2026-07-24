# Hong Kong Batch Outreach Rule

Use this reference when Tianyi asks to organize Hong Kong faculty outreach, Hong Kong/GBA professor pools, or a 4-5 day Hong Kong batch schedule.

## Default Scope

Default target schools:

- HKUST
- HKUST(GZ)
- CUHK
- CUHK(SZ)
- HKU

If Tianyi explicitly includes PolyU, PolyU Dongguan, CityUHK, or other Hong Kong/GBA schools, include them as an expanded batch rather than silently replacing the five-school default.

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

Goal: finish the reachable Hong Kong batch in 4-5 days.

Default cadence:

- 4-day plan when there are 16 or fewer ready/sendable targets.
- 5-day plan when there are 17-25 ready/sendable targets.
- Put lower-confidence or form-only targets into `hold_or_form_only.md`, not into daily send files.
- Avoid repeating the same school on the same day when possible.
- Avoid repeating the same department on the same day when possible.
- If school diversity and department diversity conflict, prioritize department diversity inside each day.
- Keep daily volume balanced; do not overfill one day while later days are sparse.

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

Each draft should ask about both:

- Fall 2027 PhD opportunities.
- Fall 2026 RA opportunity, research assistantship, visiting research, or pre-PhD research opportunity when appropriate.

Default wording:

```text
I am writing to ask whether your group may have Fall 2027 PhD opportunities, or whether there may be a Fall 2026 RA / visiting research opportunity through which I could contribute to the group before applying.
```

Use `Fall 2026 RA / visiting research` only when the lab has a plausible current project, visible student activity, or recruiting signal. If RA looks unlikely, keep the PhD question primary and mention RA as a secondary possibility.

## Route Rule

Default to student-first only when a current PhD student or senior lab member has a verified public email and strong topic overlap.

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
- One sentence asking about Fall 2027 PhD and possible Fall 2026 RA / visiting research.
- One paragraph with 1-2 strongest background points.
- One paragraph with concrete lab overlap.
- One closing sentence asking whether the route is worth discussing.

Do not overuse broad phrases like `embodied AI` unless the lab actually uses the concept or has robot learning/VLA/VTLA/manipulation overlap.

## Twelve Clarification Questions For Tianyi

Ask these when building or revising a Hong Kong batch if the answers are not already known:

1. 这次“五个学校”是否固定为 HKUST、HKUST(GZ)、CUHK、CUHK(SZ)、HKU，还是要把 PolyU 也纳入主批次？
2. HKUST(GZ) 和 CUHK(SZ) 是否按独立学校处理，还是分别归入 HKUST / CUHK 做同校去重？
3. 每天你希望最多发几封？如果 4-5 天发完，默认每天 4-6 封是否可以接受？
4. 是否允许同一天发同一学校但不同系的老师，还是同一天必须完全避免同校？
5. “系不重复”的优先级是否高于“学校不重复”？例如同一天可以 HKUST ECE + HKUST CSE 吗？
6. 你更想优先套机械/电子/机器人系的老师，还是 CS/AI 方向的 embodied AI/VLA 老师也同等优先？
7. 26 Fall RA 是远程 RA、线下 visiting research、gap-year RA，还是暑研/短期 research internship 都可以？
8. 如果老师明确只收 PhD、不提 RA，邮件里还要不要提 26 Fall RA？
9. 这批邮件是否优先发给教授本人，还是仍然优先找实验室博士生并 Cc 教授？
10. 是否优先找有中国大陆教育/工作背景或中文页面的老师，还是只要在香港学校、方向合适就可以？
11. 邮件是否需要加入 CV/homepage/Google Scholar/GitHub 链接或附件提醒？
12. 如果 4-5 天排不完所有合适老师，剩余人选应该进入 overflow，还是降低 fit 阈值一次性排完？
