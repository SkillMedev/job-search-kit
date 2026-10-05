# Job Search Kit

**For job seekers: tailored applications to a signed offer, plus outreach and negotiation.** — built in-house by [Skill&nbsp;Me](https://skillme.dev/?utm_source=github&utm_medium=readme&utm_campaign=pack-job-search-kit).

Reach for this when you are actively job hunting and want every stage to pull in the same direction. Land more first conversations with applications tuned to the role, cover letters that mirror the posting's top three requirements in under 300 words, and outreach that earns replies; walk into interviews with a STAR story bank mined from your own resume and a mock-interview loop; turn a thin network into warm intros; and close with the three-number negotiation system (minimum / target / anchor) and scripted counters. One kit from first application to signed offer.

## Install

- **Claude, ChatGPT, Codex, Cursor (connector):** [install the whole pack from skillme.dev](https://skillme.dev/pack/job-search-kit?utm_source=github&utm_medium=readme&utm_campaign=pack-job-search-kit) — one connection, then ask for any skill by name.
- **As files for Codex, Cursor, or Claude Code:** `npx @skillme/cli add job-application cover-letter-writer job-interview-prep salary-negotiation networking-system linkedin-post-writer cold-email-craft --target all`
- **With the skills CLI:** `npx skills add SkillMedev/job-search-kit`
- **Manually:** copy any `skills/<slug>/SKILL.md` into `.agents/skills/`, `.cursor/skills/`, or `.claude/skills/`.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Skills in this pack

- **[Job Application Writer](skills/job-application/SKILL.md)** — Tailors a resume and writes a cover letter for one specific job description - mirroring JD keywords for ATS parsing, reordering bullets by relevance, quantifying impact, and reporting which JD keywords matched and which are missing.
- **[Cover Letter Writer](skills/cover-letter-writer/SKILL.md)** — Writes a tailored cover letter from a resume and a job posting - mirrors the posting's top three requirements with resume evidence, opens with a company-specific hook, and stays under 300 words.
- **[Job Interview Prep](skills/job-interview-prep/SKILL.md)** — Prepares a candidate for a specific job interview - company research checklist, a STAR story bank mined from their resume and mapped to common competencies, a questions-to-ask bank, salary-question deflection lines, and a mock-interview loop.
- **[Salary Negotiation](skills/salary-negotiation/SKILL.md)** — Prepares and scripts salary and job-offer negotiations - market research, target/minimum/anchor numbers, BATNA strength, deflection and counter scripts, and total-compensation trades when base is capped.
- **[Networking System](skills/networking-system/SKILL.md)** — Builds a repeatable professional networking system - a tiered contact tracker, give-first outreach and reconnect scripts, a follow-up cadence by tier, and a weekly relationship-hour routine - so staying in touch stops depending on willpower.
- **[LinkedIn Post Writer](skills/linkedin-post-writer/SKILL.md)** — Write LinkedIn posts built for the feed - a hook that survives the two-line truncation, scannable one-idea-per-line structure, a comment-bait close, and first-hour engagement moves.
- **[Cold Email Craft](skills/cold-email-craft/SKILL.md)** — Write short, personalized B2B cold emails and follow-up copy - under 90 words, one ask, personalization in the first line - with good/bad contrast pairs to calibrate.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev/browse?utm_source=github&utm_medium=readme&utm_campaign=pack-job-search-kit).
