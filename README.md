# Internship Scout skill

This is a reusable skill for an AI assistant that finds internships and undergraduate research openings and alerts a student when new matches appear.

It walks the student through a short setup conversation (study and skills, season and locations, role types, eligibility, search languages, and check times, plus an optional weekly email digest). After that, it searches official program and employer pages, reports verified openings, keeps a ledger so the same listing is not announced twice, stays quiet when a check finds nothing new, and can send one weekly status email if the student asked for it.

The skill does not apply to jobs, contact employers, or send messages on the student's behalf, and it does not invent listings.

## How to use it

- **As a skill folder:** copy the `internship-scout` folder into your AI assistant's skills directory, then ask the assistant to find internships or undergraduate research openings.
- **As a single file:** paste the contents of `internship-scout/SKILL.md` into a bot or assistant that accepts custom instructions or skills.

After you add the skill, start a chat and tell the assistant you want help searching. It should ask the setup questions first, then begin the search with your answers.
