---
name: create-a-strong-resume
description: Build, tailor, or review a software developer resume or CV so every line is signal a hiring manager can act on. Interviews the candidate for specifics, orders sections for their situation, writes Contact, About, Skills, Experience, Open Source, Education and Projects to developer-hiring rules, and fact-checks every claim. Use when user asks to write, edit, review, tailor, or format a resume or CV, or any single section of one.
---

# Create a Strong Resume

Resume has one job: get the interview. Hiring managers scan for reasons to hire and reasons not to. Every line must be **signal** (proof you can do this job) and never **noise** (anything the employer does not care about, or anything that could describe anyone).

Test for every line: *could this sentence appear on someone else's resume unchanged?* If yes, make it specific or cut it.

## Workflow

1. **Parse input**: PDF/DOCX → extract text to markdown first.
2. **Target**: find target role, stack, seniority. Different job types get different resume versions.
3. **Interview**: relentlessly, 1 focused question at a time. Pull out specifics: numbers, scale, users, stars, PR links, what broke and how it got fixed, why a project exists, how the candidate got into programming.
4. **Structure**: pick section order from [Structure](#structure).
5. **Write**: each section per [Section Rules](#section-rules). Voice per [Voice](#voice).
6. **Verify**: every number, incident, and tool traces to a source (work log, repo code, merged PR, user answer). Unsourced claim → ask, or cut. Never invent a metric or a story.
7. **Review**: run [Checklist](#checklist).

## Structure

**Has had a tech job:**

1. Name + contact
2. About
3. Skills
4. Experience
5. Open source (optional, sits next to Experience)
6. Education
7. Portfolio projects

**Looking for first tech job:** projects are the most important section, so they move up: Name + contact, About, Skills, Portfolio projects, Experience, Education.

Extras (certifications, awards) go last, and only if they add signal. An award needs who gave it and why.

## Section Rules

### Contact

Comes first.

- Full name, prominent (the top heading).
- Email next. Professional address (name-based), never a handle.
- Phone number. Include it: spam can be blocked, a recruiter who can't reach you is gone.
- Clickable GitHub link. Clickable LinkedIn link. Portfolio site optional.
- Every item clickable (`mailto:`, `tel:`, URLs).

### About

Optional. Worth it only if done well; a weak one wastes the most valuable space on the page.

- 3–5 sentences. Sell the story and the work it took to get here.
- Tell a story, don't list facts. First person is fine here.
- Be specific: which tech, and *why*, and *which parts* of it.
- Show smart, capable, hard-working through what happened. Never state it.
- End with what the candidate wants next (role, stack).
- No hobbies, "passion for coding", "love to learn", "great company to work for".

### Skills

Short. Hiring managers skim it; recruiters and ATS keyword screens use it.

- Bullets of logically grouped technologies, no labels needed:
  - languages
  - frameworks
  - data stores
  - infrastructure, tools, CI (Git, GitHub, GitHub Actions count: ATS looks for them)
- Never qualify: no "advanced", "intermediate", "4/5".
- List only what the candidate is comfortable being interviewed on. Prefer tools that a bullet or project backs up.
- Tailor per version: lead with the target job's stack, drop unrelated tools. A short believable list beats a long one.
- Techniques and outcomes ("schema-validated LLM output") belong in bullets, not here.

### Experience

- Any job counts, even outside tech. Non-tech roles get a line or two showing responsibility and reliability.
- Unpaid real work counts: a site, script, or automation a non-profit or small business actually uses is experience.
- Reverse chronological. Header: `**Title** | Mon YYYY – Mon YYYY · Company, City`.
- Bullets start with an action verb ([ACTION-WORDS.md](ACTION-WORDS.md)), no pronouns, past tense for past roles.
- Quantify only with real numbers: *Accomplished X, measured by Y, by doing Z*.
- One role spanning several products/clients → group bullets by product, name the product in its first bullet.
- Keep the strongest. A dozen-plus bullets on one role means cut.

### Open Source

Merged PRs in a real, used project can be as strong as paid work.

- Only significant work: features, or bug fixes with tests. No typo or docs-only PRs.
- Link each PR. Add the project's real-world scale from its README (orgs, users, stars).
- Open or unmerged PRs stay off until merged.

### Portfolio Projects

- 1–2 projects. 3 is the absolute max.
- Each entry:
  - Unique, memorable name
  - Clickable GitHub link (plus live demo if deployed)
  - Tech stack, checked against the code (Gemfile, package.json), not memory
  - A paragraph or two: what it does, why it exists, the interesting technical decision
- First person is fine ("I built X to…").
- Never "just", "toy", "simple", "followed a tutorial". If the project is weak, improve the project, then describe it without apology.

### Education

Degree, school, dates. Drop high school once there is a degree. Put Education above Experience only for students with no tech job.

## Voice

- **Bullets** (Experience, Open Source): no pronouns, action verb first, phrases not stories.
- **Paragraphs** (About, Projects): first-person narrative allowed and encouraged.
- Specific over general, active over passive, plain over flowery.
- One format everywhere: same date style, same separators, serial comma or none, consistently.

## Checklist

- [ ] Every line passes the "could be anyone's" test.
- [ ] Every number and incident has a source.
- [ ] Contact: name, email, phone, GitHub, LinkedIn, all clickable.
- [ ] About tells a story and names what the candidate wants next.
- [ ] Skills grouped, unqualified, tailored, backed by the rest of the resume.
- [ ] 1–3 projects, each with link, stack, and why.
- [ ] No "just", "toy", or "tutorial".
- [ ] Open source: merged, significant, linked.
- [ ] No hobbies, photo, age, gender, or references.
- [ ] No typos, no passive voice, formatting survives PDF export.
- [ ] Tailored to the target job.

---

- [DEVELOPER-EXAMPLES.md](DEVELOPER-EXAMPLES.md): bad vs good for each section.
- [ACTION-WORDS.md](ACTION-WORDS.md): action verbs by category.
- [REFERENCE.md](REFERENCE.md): general student resume samples and layout templates. Where they conflict with this file (skill levels, interests, narrative), this file wins.
- [CREDITS.md](CREDITS.md): sources.
