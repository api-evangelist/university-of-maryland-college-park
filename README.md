# University of Maryland College Park (university-of-maryland-college-park)

The University of Maryland, College Park (UMD) is the flagship public research university of the University System of Maryland, ranked #218 in the QS World University Rankings 2025. UMD does not operate a central official public developer portal; its most prominent documented public API is the student-run, open-source **umd.io** project.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-maryland-college-park/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-maryland-college-park-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education, Higher Education, University, United States, Open Data, Courses, Student Run

## APIs

- **umd.io API** — Student-run open REST API for UMD data (courses, sections, professors, bus, map/buildings, majors). Base URL `https://api.umd.io/v1`. Docs: https://beta.umd.io — Source: https://github.com/umdio/umdio
- **Testudo Schedule of Classes** — Registrar's public course schedule web interface. https://app.testudo.umd.edu/soc/ — Docs: https://www.testudo.umd.edu/
- **DRUM Institutional Repository** — UMD Libraries' DSpace repository, publicly browsable. https://drum.lib.umd.edu

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-maryland-college-park-plans-pricing.yml](plans/university-of-maryland-college-park-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-maryland-college-park-rate-limits.yml](rate-limits/university-of-maryland-college-park-rate-limits.yml)
- FinOps: [finops/university-of-maryland-college-park-finops.yml](finops/university-of-maryland-college-park-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.umd.edu
- GitHub: https://github.com/umdio
- LinkedIn: https://www.linkedin.com/school/university-of-maryland/

## Notes

- umd.io is a **student-run, unofficial** open-source API, not a service operated by the university. It was verified live (`api.umd.io/v1/courses` returned HTTP 200) with public documentation at beta.umd.io.
- Testudo Schedule of Classes is a public web application, not a documented JSON API; umd.io scrapes it as a source.
- DRUM is publicly browsable (HTTP 200), but standard OAI-PMH/DSpace REST endpoint paths returned 404 during review and are not asserted here.
- No endpoints were fabricated; only URLs confirmed during review are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
