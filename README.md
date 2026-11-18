# MYFutureJobs Prototype

Clickable landing-page prototype built from the MYFutureJobs user flowchart. Concept A ("Product Page"): light theme, Apple-style product layout, jobseeker search by state, and an employer homepage in the same style.

> Prototype only. Not the official MYFutureJobs website. All jobs, employers, events, people and figures are sample data.

## Open it

Open `index.html` in any modern browser. No build step or server needed. Use the **Flow guide** button to jump to any branch of the flowchart.

## Flows covered

| Area | Flow |
|---|---|
| AI Job Recommendation | Upload resume → AI review (retry if unreadable) → sign in / register → Top 10 vacancies → apply |
| Search Bar | Keyword + state → vacancy results → apply → sign in → job application |
| Trending Jobs | Top 10 jobs and Top 10 industries → vacancy results |
| Career Journey | Student (CareerPathway, CLP, CEP) · Job Seekers (Career Exploration, Job Matching) · Informal to Formal |
| Sign In JS | Redirect to Jobseeker Portal |
| Career Fair | Info → list → event info → register? → login / register → apply event → apply more events? → end |
| MYCEC | Physical (slot booking) or Metaverse (Metaverse MYCEC / Metaverse Carnival) |
| Training | Info → list → apply → training provider website |
| Insight | Career Hub · Galaxy · Labour Market Exchange |
| Collaboration | Prowira · Grab · GLC & GLIC · Carsome → apply job? |
| Initiatives | REPP · Lindung Kerjaya · Budget 2026 |
| Employer | Sign In Employer · Recruitment Support · Statistic · Success Stories · Incentive Programmes |

External destinations (portals, partner sites) are simulated with a redirect dialog.

## Photos

Photos are loaded from Unsplash (Unsplash License). To use your own, put a JPG named after the key in `assets/img/` and it is used first:

| Key | Used in |
|---|---|
| `interview.jpg` | Home "people hired" band |
| `hire.jpg` | Employer "Hire the right people" band |
| `fair.jpg` | Career fair highlight card, Career Fair page |
| `laptop.jpg` | Career Journey bento tile |
| `factory.jpg` | Training page |
| `vr.jpg` | MYCEC highlight card, Metaverse option |

If a photo cannot load, a brand gradient shows instead.

## Files

- `index.html` — current prototype (v2, Concept A, with motion)
- `index-v1.html` — first prototype
- `concepts/` — the three design directions (A, B, C) with screenshots
- `screenshots/` — review screenshots of v2
