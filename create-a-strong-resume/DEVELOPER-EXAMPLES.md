# Developer Resume Examples

Bad vs good for each section. All people, companies, and projects here are fictional.

## Contact

Bad:

```markdown
CodeNinja99
ninja.coder99@hotmail.com
```

Good:

```markdown
# Priya Raman

[priya.raman@gmail.com](mailto:priya.raman@gmail.com) · [+1 415 555 0142](tel:+14155550142) · [github.com/priyaraman](https://github.com/priyaraman) · [linkedin.com/in/priyaraman](https://linkedin.com/in/priyaraman)
```

## About

Bad (generic, hobbies, states qualities instead of showing them):

> I'm a hard-working developer with a passion for Python and clean code. I love learning new technologies and hiking on weekends. I'm looking for a great team where I can grow.

Good (story, specific tech and why, shows effort, says what's next):

> I worked the front desk at a physiotherapy clinic that booked every appointment on paper, and double-bookings were costing us a patient a day. I taught myself Python to build a booking tool on top of Google Calendar, and the clinic still runs on it two years later. That project got me hooked on backend work, especially designing data models that stop bad states from ever being saved. I'm looking for a backend Python role where correctness matters as much as speed.

## Skills

Bad (qualified, padded, untailored):

```markdown
- Python (advanced), Java (intermediate), C++ (beginner), Rust (learning)
- Communication, teamwork, problem-solving
- MS Office, Windows, VS Code
```

Good (grouped, unqualified, leads with the target job's stack):

```markdown
- Python, SQL, TypeScript
- Django, FastAPI, pytest
- PostgreSQL, Redis
- Docker, AWS, Git, GitHub Actions
```

## Experience

Bad (duties, not results):

```markdown
- Responsible for working on the backend.
- Helped with bug fixes and code reviews.
```

Good (action verb, specific, real numbers):

```markdown
**Backend Engineer** | Jan 2024 – Present · Ledgerly, Remote

- Rebuilt invoice export as a background job, cutting p95 response time from 9s to 400ms for accounts with 10k+ invoices.
- Added idempotency keys to the payments webhook, ending duplicate charges that support had been refunding by hand.
```

Non-tech job, kept short:

```markdown
**Shift Supervisor** | 2021 – 2023 · Corner Café, Austin

- Ran opening shifts and trained 6 new staff; trusted with cash reconciliation and stock ordering.
```

## Open Source

Bad (typo fix, no link, no scale):

```markdown
- Contributed to a popular open-source project.
```

Good (merged, significant, tested, linked, with scale):

```markdown
- **Tidewater** (self-hosted scheduling app, 4k GitHub stars): Added recurring-event exceptions so one occurrence can be moved without changing the series, with model and system tests ([#812](https://github.com/example/tidewater/pull/812)).
```

## Portfolio Projects

Bad (downplays, no link, no why):

```markdown
**Weather App**
Just a simple toy app I made following a tutorial. Uses an API.
```

Good (memorable name, link, stack, what, why, interesting decision):

```markdown
**[pagerbot](https://github.com/priyaraman/pagerbot)** | Python, FastAPI, PostgreSQL, Slack API

I built pagerbot after my team missed an outage because the on-call engineer's phone was on silent. It watches our uptime checks and escalates through Slack, then SMS, then a phone call until someone acknowledges. Escalation state lives in PostgreSQL with row-level locks, so two workers can never page the same person twice.
```

## Education

Bad (high school after a degree, filler coursework):

```markdown
- B.S. Computer Science, State University, 2022. Relevant coursework: Intro to Programming, Calculus I.
- Lincoln High School, 2018. Member of chess club.
```

Good:

```markdown
**B.S. in Computer Science** | 2018 – 2022 · State University
```
