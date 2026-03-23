# CLAUDE.md

## Project
Build and maintain the public website for **Evolving Orgs**.

## Brand
**Evolving Orgs**

## Tagline
**How organizations evolve in the age of AI**

## Core positioning
Evolving Orgs is a thought leadership and advisory platform focused on how AI is changing organizations, management systems, decision-making, team design, and leadership.

The site should feel:
- clear
- modern
- credible
- lightweight
- thoughtful
- not corporate and not overly “startup hype”

Avoid vague consulting fluff.

## Primary audience
- executives
- heads of product
- transformation leaders
- innovation leaders
- founders
- management teams trying to figure out AI beyond tools

## Primary goal of the site
1. Establish authority
2. Publish original thinking
3. Capture email subscribers
4. Generate advisory, workshop, and speaking inquiries

## Secondary goal
Create a platform that can later support:
- reports
- frameworks
- diagnostic tools
- webinars
- research products

---

## Tech stack
Use:
- GitHub as the source repository
- Cloudflare Pages as the host
- simple static site architecture
- minimal dependencies
- easy-to-edit content structure

Preferred stack order:
1. plain HTML/CSS/JS if enough
2. Astro if needed for maintainability
3. Next.js only if there is a strong reason

Default to the simplest option that keeps the site fast and easy to maintain.

## Hosting and deployment
- Repo lives on GitHub
- Cloudflare Pages is connected directly to the GitHub repo
- Deploy automatically on push to `main`
- Use preview deployments for pull requests if available
- Keep deployment simple and low-maintenance

## Domain
Primary domain:
**evolvingorgs.com**

Use the root domain as primary.
Redirect `www.evolvingorgs.com` to `evolvingorgs.com`.

---

## Information architecture

### Pages to create first
1. Home
2. Thinking
3. About
4. Work With Me
5. Contact

### Pages to add later
6. Research
7. Frameworks
8. Speaking
9. Newsletter archive

---

## Homepage requirements

### Hero
Display:
- Brand: Evolving Orgs
- Tagline: How organizations evolve in the age of AI
- Primary CTA: Read the Thinking
- Secondary CTA: Join the Email List

### Problem section
Explain:
AI is not just another tool. It changes how organizations decide, coordinate, learn, and operate.

### Insight section
Explain:
Most organizations are trying to use AI inside outdated management systems.

### Promise section
Explain:
Evolving Orgs explores how leaders can redesign organizations for the AI era.

### Content section
Highlight:
- essays
- research
- frameworks
- case breakdowns

### Services section
Highlight:
- executive briefings
- advisory
- workshops
- speaking

### Email signup section
Include a simple embedded Kit form with minimal friction.

---

## Writing style
Write in a tone that is:
- direct
- intelligent
- concise
- grounded
- not buzzword-heavy
- not inflated
- not “future of work” fluff

Avoid:
- “revolutionary”
- “cutting-edge”
- “synergy”
- “leverage AI to unlock transformation”
- generic agency language

Prefer:
- plain English
- strong claims backed by logic
- short paragraphs
- clear section headings

---

## Design direction
Aim for:
- minimal
- editorial
- clean typography
- generous spacing
- strong hierarchy
- no clutter
- no stock-photo overload
- **mobile-first and fully responsive** — all pages must work well on phones and tablets, not just desktop

Visual tone:
- modern research journal meets strategy studio
- serious but accessible

Prefer:
- off-white or white background
- dark text
- one restrained accent color
- subtle linework and diagrams
- simple cards
- quiet confidence

Do not over-design.

---

## Content priorities

### First 3 articles
1. Why Organizations Must Evolve in the Age of AI
2. Why Most AI Transformations Fail
3. The 5 Levels of AI-Driven Organizational Evolution

### First downloadable or featured framework
- The Evolution of Organizations

### First lead magnet later
- State of AI-Driven Organizations
or
- AI Organizational Evolution Diagnostic

---

## Diagram to create first
Create a clean diagram called:

**The Evolution of Organizations**

### Draft concept
Five stages across a left-to-right progression:

1. Functional Organizations
   - siloed departments
   - top-down planning
   - slow handoffs

2. Agile Organizations
   - cross-functional teams
   - iterative delivery
   - faster feedback loops

3. Platform Organizations
   - shared capabilities
   - internal platforms
   - scalable product operating models

4. AI-Assisted Organizations
   - AI copilots in workflows
   - augmented decisions
   - mixed human + machine execution

5. AI-Native Organizations
   - redesigned operating model
   - AI embedded in core decisions and workflows
   - management systems adapted to AI

### Visual guidance
- horizontal flow
- one card or node per stage
- short labels only
- 2–3 supporting bullets per stage
- use arrows or progression markers
- keep it presentation-friendly
- exportable as SVG and PNG

This diagram should be reusable on:
- homepage
- articles
- LinkedIn posts
- slide decks

---

## Email capture
Use **Kit** for email capture.

### Requirements
- embed a simple signup form in homepage and footer
- collect first name and email at most
- offer a lightweight reason to subscribe:
  “Get new essays and frameworks on how organizations evolve in the age of AI.”
- set up one welcome email
- keep friction low

Do not build a custom email backend unless there is a compelling reason.

---

## First offer to include on site
Yes, include this early.

### Executive Briefing
Create a simple offer block for:

**Executive Briefing: How AI Changes Your Organization**

Format:
- 90–120 minute session
- built for leadership teams
- focused on how AI changes decision systems, team design, management, and operating models

Outcome:
- shared language
- strategic clarity
- next-step recommendations

CTA:
- Inquire about a briefing

This should appear on:
- homepage
- Work With Me page

---

## About page guidance
Frame Joey as:
- product and operations leader
- organizational change practitioner
- advisor on AI and organizational evolution

Do not make the About page read like a generic resume dump.
Focus on:
- point of view
- credibility
- why this work matters now

---

## Contact flow
Use a simple contact method:
- email link
or
- simple form

Keep inquiry options simple:
- Advisory
- Workshop
- Speaking
- Executive Briefing
- Other

---

## Build priorities
### Phase 1
- launch homepage
- create About
- create Thinking index
- publish first article
- embed Kit email form
- deploy to Cloudflare Pages

### Phase 2
- create Work With Me
- add diagram
- add 2 more articles
- create contact flow

### Phase 3
- add Research page
- add downloadable framework or report
- refine visual identity

---

## SEO basics
Prioritize clarity over keyword stuffing.

Use page titles and descriptions that clearly say:
- AI
- organizations
- management
- organizational evolution
- operating models
- leadership

---

## Repo guidance
Keep repo simple and readable.

Suggested structure:

/
  index
  about
  thinking
  work-with-me
  contact
  assets/
    images/
    diagrams/
  content/
    essays/
  styles/

If using Astro or another framework, preserve an equally clear content structure.

---

## Non-goals
Do not:
- build a giant app
- add unnecessary animations
- make a complex CMS before content exists
- create too many pages before the first articles are published

The point is to publish and build authority, not to over-engineer.

---

## Success criteria
The first version is successful if:
- site is live on evolvingorgs.com
- tagline is clear
- one article is published
- one diagram is visible
- one email capture form works
- one executive briefing offer is visible
- the site is easy to update

---

## Changelog
Maintain a `CHANGELOG.md` file at the repo root to track all meaningful work done on this project.

### Format
Each entry should include:
- Date (YYYY-MM-DD)
- What was built or changed
- Why (if not obvious)

### Rules
- Update `CHANGELOG.md` after completing any significant unit of work
- Keep entries concise — one line per item is fine
- Group entries by date
- Do not log trivial edits (typo fixes, whitespace)
- This file is for traceability, not documentation — keep it lean