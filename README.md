# Job Skill — Singapore / ChatGPT edition

A reusable instruction workflow for Singapore finance, fintech, risk, quantitative and data analytics internship searches. Adapted from the original Claude/India-focused job-skill.

## What changed

- Singapore employer career pages and local job boards replace India-focused sources.
- ChatGPT-compatible tool discovery replaces Claude-specific commands and scheduling APIs.
- Date compatibility is checked separately from skills: open matches, dates to confirm, watchlist, or dates that do not fit.
- Student CVs and cover letters use verified evidence; no invented ATS scores, experience or rejection diagnoses.
- Tracking records actual application outcomes; recurring searches require an explicit scheduling request.

## Use

Ask ChatGPT Work to install the skill from this repository, or use its skill-creator workflow to adapt it to your profile. Forking alone does not activate a skill. Installation and scheduling depend on the capabilities available in your ChatGPT environment.

Once enabled, select **Job Skill — Singapore** from the skill picker where supported, or ask naturally:

- "Use job-skill to find Singapore finance internships for late August 2027 to end January 2028."
- "Tailor my CV to this risk internship: [URL]."
- "Review my application tracker."
- "Set up a weekly search for matching internships."

The labels job-skill search, tailor, status, review, interview and automate are also understood as requests; they are not software commands to run in a terminal.

## Installation files

SKILL.md contains the reusable workflow. Install it in a skill directory named job-skill. Optional agents/openai.yaml metadata supplies the display name and example prompt.

Keep personal profiles, CVs, contact details, GPA, transcripts and application trackers out of this public repository. An optional private references/search-profile.md can store a user's search preferences in their own skill installation.

## Limits

This is an instruction-only skill. It does not supply job-board accounts, email access or a scheduler. It uses available connected tools and reports access limits. A search prepares a shortlist; it does not submit applications or send messages.

## License

MIT, as declared by the original repository README. Retain any upstream licence and attribution supplied with the original source.
