---
type: qualitative-data
milestone: MS4
topic: "Governance Recommendations Ideation, Assessment and Prioritisation Workshops"
data_collection_methods:
  - workshops
  - facilitated-discussion
  - live-rice-assessment
stakeholder_groups:
  - ada-owners
  - dreps
  - spos
  - cc-members
  - builders
metrics_covered:
  - "M1 Active voting participation"
  - "M2 DRep delegation barriers"
  - "M3 DRep delegation stickiness"
  - "M4/M5 Voting power concentration"
  - "M6 DRep rationale publication"
  - "M7 Net change in active DReps"
  - "M8 SPO governance engagement"
  - "M10 CC response time"
  - "M11 CC rationale publication"
  - "M12 CC abstain rate"
recommendation_themes:
  - DRep incentives
  - Voter incentives and requirements
  - SPO governance friction
  - CC tooling, incentives and credentials
  - Language barriers and translation
  - In wallet governance
  - Granular per issue delegation
tags:
  - governance
  - qualitative
  - recommendations
  - prioritisation
  - cardano
  - beyondmvg
data_formats:
  - md
---

# MS4, Governance Recommendations Ideation, Assessment and Prioritisation

> Workshops conducted during Beyond MVG Milestone 4 to ideate, debate and
> prioritise the governance recommendations that build on the MS3 metrics
> dashboards. These sessions feed directly into the Milestone 4 State of
> Governance report.

The series moved from open ideation (workshop #6) through focused theme
deep dives (DRep incentives, voter incentives, SPO and CC friction,
language barriers, CC credentials) into final consolidated prioritisation
(workshop #13 onwards). Live RICE and MoSCoW assessments were performed
on the Beyond MVG application during several sessions; the resulting
ratings, comments and "Discussed in workshop" admin flags live in the
application database and are surfaced on
https://beyond-mvg.vercel.app/data and
https://beyond-mvg.vercel.app/workshops.

## Quick Navigation

| Section | Contents | Files |
|---------|----------|-------|
| [transcripts/](transcripts/) | YouTube auto-caption transcripts, ASCII cleaned, with frontmatter | 8 MD |
| [visuals/](visuals/) | Beyond MVG application screenshots | placeholder |
| [sources.md](sources.md) | Links to YouTube recordings and Beyond MVG application | 1 MD |

## Sessions

| Workshop | Date | Theme | Video |
|----------|------|-------|-------|
| #6 | 2026-04-16 | Ideating on Governance Recommendations, first walk through of the identify and prioritise app, DRep stickiness debate, granular delegation, mobile UX feedback | [YouTube](https://www.youtube.com/watch?v=i8h1r0GhTy0) |
| #8 | 2026-04-20 | DRep Incentives, Ryan's 100k ADA pilot proposal, stake bleeding style urgency, delivery paths | [YouTube](https://www.youtube.com/watch?v=ij8Nd0o3auE) |
| #9 | 2026-04-22 | Voter Incentives and Requirements, assessment of two recommendations (DRep selection on reward withdrawal; Rosito Voter Incentives R&D) | [YouTube](https://youtu.be/7pyAc4P8TBo) |
| #10 | 2026-04-24 | SPO Governance Friction and CC Metrics, cold key friction, missing tooling, lobbyist effect, social and notification layer | [YouTube](https://youtu.be/2dHSST-hypA) |
| #11 | 2026-04-28 | Language Barriers in Governance, AI translation, DRep localisation responsibility, dedicated translator role, four new recommendations assessed live | [YouTube](https://www.youtube.com/watch?v=7QldP5A_Q10) |
| #12 | 2026-05-02 | Final Recommendations Session, Constitutional Committee credentials, CC tooling and CC incentives elevated to Must tier; workshop retrospective; freeze announcement before MS4 state of analysis | [YouTube](https://youtu.be/kn1iWt3BRbs) |
| #13 | 2026-05-11 | Consolidated Recommendation Prioritisation, Session 1, working through the consolidated nine recommendations (DRep concentration and compensation CPS, in wallet governance) | [YouTube](https://youtu.be/Pcqya2EVPCw) |
| #14 | 2026-05-15 | Governance Takeover Incident Readiness and Incentives, CIP-135 style disaster recovery framework for governance, 1.5% DRep cap with annual delegation reset, Nakamoto coefficient alarms, MoSCoW=Must assessment, default DRep removal in next hard fork | [YouTube](https://youtu.be/U3YXk6CtyGI) |

## Transcripts

Each transcript is the raw YouTube auto-caption for the session, lightly
cleaned to ASCII safe punctuation and prefixed with a YAML frontmatter
block (`workshop_number`, `date`, `title`, `video_url`, `attendees`,
`youtube_description`).

| File | Workshop | Notes |
|------|----------|-------|
| [2026-04-16-workshop-06-transcript.md](transcripts/2026-04-16-workshop-06-transcript.md) | #6 | First identify and prioritise app walk through |
| [2026-04-20-workshop-08-transcript.md](transcripts/2026-04-20-workshop-08-transcript.md) | #8 | DRep incentives deep dive |
| [2026-04-22-workshop-09-transcript.md](transcripts/2026-04-22-workshop-09-transcript.md) | #9 | Voter incentives |
| [2026-04-24-workshop-10-transcript.md](transcripts/2026-04-24-workshop-10-transcript.md) | #10 | SPO and CC friction |
| [2026-04-28-workshop-11-transcript.md](transcripts/2026-04-28-workshop-11-transcript.md) | #11 | Language barriers |
| [2026-05-02-workshop-12-transcript.md](transcripts/2026-05-02-workshop-12-transcript.md) | #12 | Final session, CC credentials, MS4 freeze |
| [2026-05-11-workshop-13-transcript.md](transcripts/2026-05-11-workshop-13-transcript.md) | #13 | Consolidated prioritisation session 1 |
| [2026-05-15-workshop-14-transcript.md](transcripts/2026-05-15-workshop-14-transcript.md) | #14 | Governance takeover incident readiness and DRep cap / reset incentives |

## Recommendation Themes Surfaced

Across the MS4 workshop series the following theme clusters emerged and
were taken forward into the consolidated recommendation set:

1. DRep incentives (workshop #8)
2. Voter incentives and requirements (workshop #9)
3. SPO governance friction, cold key access, tooling, scope of SPO
   protocol parameter votes (workshop #10)
4. CC metrics, response time and rationale publication (workshop #10)
5. Language barriers and translation (workshop #11)
6. CC tooling, CC incentives, CC credential operations (workshop #12)
7. In wallet governance information and one click voting (workshop #13)
8. Per issue or granular delegation (workshop #6, revisited #13)
9. Governance takeover incident readiness, voting power concentration caps and annual delegation reset (workshop #14)

## Application Screenshots

Place Beyond MVG application screenshots used in the sessions inside
[`visuals/`](visuals/). MS4 workshops used the Beyond MVG application
exclusively for live RICE and MoSCoW assessments; no Miro board was used
in this milestone.

## Notes

- Live RICE and MoSCoW ratings produced in these sessions are stored in
  the Beyond MVG application database (observations, recommendation
  assessments and the `discussed_in_workshop` admin flag) and are not
  duplicated in this folder. They are surfaced on
  https://beyond-mvg.vercel.app/data and
  https://beyond-mvg.vercel.app/workshops.
- For the MS3 metrics analysis workshop that preceded the recommendation
  work, see
  [`../ms3-metrics-experience-analysis/`](../ms3-metrics-experience-analysis/).
- For the MS2 surveys, interviews and structured workshop responses,
  including workshop #1 and #3 transcripts, see
  [`../ms2-workshops-surveys-interviews/`](../ms2-workshops-surveys-interviews/).
