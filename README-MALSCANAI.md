# MalScanAI Internship Report – Bilingual Hugo Source

This package is based on the FCAJ Hugo template and contains Vietnamese and English content for:

- Internship report homepage and student information
- Project proposal
- Three published blog posts
- Two Meetup event reports
- MalScanAI deployment workshop
- Personal self-evaluation
- Sharing and feedback

## Content structure

```text
content/
├── _index.md
├── _index.vi.md
├── 1-Worklog/
├── 2-Proposal/
├── 3-BlogsPosted/
├── 4-EventParticipated/
├── 5-Workshop/
├── 6-Self-evaluation/
└── 7-Feedback/
```

## Image structure

```text
static/images/
├── 2-Proposal/
├── 3-BlogsPosted/
└── 5-Workshop/
```

## Run locally

```powershell
hugo server -D
```

## Privacy note

The homepage contains a phone number and e-mail address supplied for the internship report. Review or remove them before publishing the repository publicly.


## Worklog update

The 12-week worklog was imported from `mau_bao_cao_tien_do_12_tuan(1).docx` and converted into bilingual Hugo pages.

The following obvious date-entry errors were normalized:

- `17/05/2023` → `17/05/2026`
- `24/0/2026` → `24/06/2026`
- Week 9: `02/06/2026` → `02/07/2026`
- Week 10 Meetup: `11/06/2026` → `11/07/2026`
- Week 12: `22/06/2026` → `22/07/2026`
