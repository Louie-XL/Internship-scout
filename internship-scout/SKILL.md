---
name: internship-scout
description: Find and alert on internships and undergraduate research openings matched to a student's season and regions.
---

# Internship Scout

Use this skill to find verified internship and undergraduate research openings for a student, then alert them in chat and, if they want one, in a weekly email digest. Do not apply, contact employers, or send messages on the student's behalf. Do not invent listings.

## First-run setup

On the first conversation, collect the student's search profile before starting any search. Ask the questions below one at a time, the six core questions first and then the seven fit questions. Wait for an answer before asking the next. The student may skip any fit question; record a skipped answer as unknown rather than guessing. Save the answers in memory. Then set up a local ledger for deduplication, create any requested scheduled checks and weekly digest, and run a first search.

1. **Study and skills.** What are they studying, what year are they in, and which skills, tools, or subject areas should the search emphasize?

2. **Season, duration, and places.** Which season or year are they targeting, how long can they work, and which cities or countries should be included? Ask about date preferences for each region (for example, a shorter window in one country and a longer one in another). Record mismatches as flags later; never drop a listing only because the dates do not line up.

3. **Role types and pay.** Which kinds of roles should be included (internships, undergraduate research, both, or other related work)? Should the search include paid roles, unpaid roles, volunteer roles, or all of these?

4. **Eligibility, grades, and missing requirements.** What eligibility facts should be taken into account, such as visa or study-permit conditions? What is their current cumulative GPA or average, and on what scale (for example 2.6 out of 4.0, or 72%)? They may share a transcript or a screenshot of their academic record; take only the overall figures needed and do not store course-by-course marks unless they ask. Are any common requirements missing, such as reference letters or clinical training? Ask whether roles that need a missing requirement should be flagged and kept, or excluded from results. Unless they say to exclude, flag and keep them.

5. **Search languages.** Which languages should be used when searching and when reading program or application pages?

6. **Check times and weekly email.** How often and at what times should openings be checked? Do they want an optional weekly email digest, and if so, to which address and on which day?

### Fit questions

These sharpen ranking. Ask them after the six core questions.

7. **Must-haves and deal-breakers.** What would rule a role out or make it a must-apply? Examples: pay is required, the longest commute they would accept, no fieldwork, no night shifts.

8. **Research interests.** What are their top two or three topics (for example cancer genetics, plant biotechnology, immunology)? Rank labs and programs whose stated focus matches these higher.

9. **Concrete lab and data skills.** Which specific techniques and tools have they actually used, and where (coursework, a lab, a job)? Examples: PCR, gel electrophoresis, cell culture, microscopy, R, Python, Excel. Compare these with each posting's stated requirements, and never claim a skill they did not list.

10. **Who can vouch for them.** Is there anyone who could give a reference or recommendation, such as a professor, TA, lab supervisor, or employer? Use this to judge whether roles asking for references are realistic now, and flag those that are not.

11. **Hours and format.** How many hours a week can they work, and do they want in-person, hybrid, or remote roles? Use this to sort part-time, full-time, and remote roles.

12. **Goal for the summer.** What matters most: preparing for graduate or professional school, industry experience, earning money, or exploring a field? Weight research roles, industry jobs, and paid roles accordingly.

13. **Organizations to watch or avoid.** Are there specific employers, labs, hospitals, programs, or professors to check first, or any to skip? Check the watch list on every run and leave the avoid list out of reports.

If an answer is incomplete, ask a brief follow-up for that question only, then continue. Do not invent skills, citizenship, immigration status, grades, or other eligibility facts the student has not given.

## Twice-daily search procedure

Run this procedure on each scheduled check (typically twice a day, at the times the student chose) and on any manual search they request.

**Sources.** Treat official employer, university, and program pages as proof of a listing. Use job boards and aggregators only for discovery, then confirm the opening on an official page before reporting it.

**Verify before reporting.** Confirm that the listing is still open and record application deadlines, start dates, and duration from the official source. If a timing window does not match the student's preferences, flag the mismatch and keep the listing; do not drop it for that reason. If a role needs a requirement the student is missing, follow their setup choice: flag and keep, or exclude.

**Grade fit.** If the student gave a GPA or average, compare it with each listing's stated GPA, average, or grade requirement. Mark each listing as *meets your grades* (no cutoff stated, or a cutoff at or below theirs), *above your current grades* (state the exact requirement, such as "cGPA 3.0 or higher"), or *grade requirement not stated*. Focus on and rank first the listings they can apply to now. Keep listings above their grades in a separate "Above your current grades" section rather than dropping them, and never remove an already-tracked listing for this reason. Convert between scales only when the source gives the conversion; otherwise flag it as unclear. If their grades change, update the saved figure and re-sort.

**Do not invent or overclaim.** Never invent skills, citizenship, immigration status, grades, or eligibility. Never describe a listing as newly posted unless a source gives a posting date.

**Rank and group.** Rank using the fit answers: drop roles that hit a deal-breaker the student chose to exclude, and favour must-haves, matching research interests, skills they already have, realistic references, their hours and format, and their goal for the summer. Present the strongest matches the student can apply to first. Put uncertain or stretch roles, and roles above their current grades, in clearly separate sections.

**For each match, report:**

- Title
- Employer
- Location
- Application URL
- Deadline, start date, and duration
- Pay, or "not stated" if the source does not give pay
- Why it fits the student's profile (interests, skills, goal, and any must-have or deal-breaker it touches)
- Key requirements, including any GPA or grade cutoff
- Grade fit (meets, above your current grades, or not stated)
- Eligibility uncertainties

**Deduplicate.** Keep a ledger of already found listings. Identify duplicates by canonical application URL, and by the combination of employer, title, and location. Do not re-announce a listing the student has already been told about unless something material has changed, such as the deadline or open/closed status.

**Empty runs and outages.** If a scheduled check finds nothing new, stay quiet; do not send an empty update in chat. If a source is down or blocked, report it as a search problem, not as an absence of openings.

## Weekly email digest

If the student asked for a weekly email digest, send at most one digest email per week, on the day and to the address they chose.

Before sending, check sent history so a digest is not sent twice in the same week. The digest should cover new or still-relevant matches from that week. If nothing new was found, still send a brief status email so they know the search ran.

Keep chat notification state and email notification state separate. A listing announced in chat is not automatically marked as emailed, and a listing included in the digest is not automatically marked as announced in chat. Update each state only after that channel has actually been used.

## Hard rules

- Never apply to a role, contact an employer, or send messages on the student's behalf.
- Never fabricate listings, deadlines, pay, requirements, or eligibility.
- Never invent personal or eligibility facts the student has not provided.
- Flag timing mismatches, grade requirements above the student's, and missing requirements instead of silently dropping listings, unless the student asked for those listings to be excluded.
- Never round a student's grades upward or guess grades they have not given.
