# University of Pittsburgh (university-of-pittsburgh)

The University of Pittsburgh is a public research university in Pittsburgh, Pennsylvania, United States, ranked #271 in the QS World University Rankings 2025. This repository catalogs Pitt's public developer and API footprint as an APIs.json provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-pittsburgh/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-pittsburgh-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Research Data, Library, United States

## APIs

- **Western Pennsylvania Regional Data Center (WPRDC) CKAN API** — Open data portal (CKAN Action API) operated as a partnership of Pitt, Allegheny County, and the City of Pittsburgh. Docs: https://data.wprdc.org
- **Project Tycho API** — Pitt-hosted global health/epidemiological surveillance data; CSV output, free API key required. Docs: https://www.tycho.pitt.edu/dataset/api/
- **PittAPI (community)** — Unofficial Python library for Pitt course, dining, library, news, laundry, lab, shuttle, people, and textbook data. Docs: https://github.com/pittcsc/PittAPI
- **D-Scholarship@Pitt OAI-PMH** — University Library System institutional repository metadata harvesting endpoint. Docs: https://d-scholarship.pitt.edu

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-pittsburgh-plans-pricing.yml](plans/university-of-pittsburgh-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-pittsburgh-rate-limits.yml](rate-limits/university-of-pittsburgh-rate-limits.yml)
- FinOps: [finops/university-of-pittsburgh-finops.yml](finops/university-of-pittsburgh-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.pitt.edu
- GitHub (official org): https://github.com/University-of-Pittsburgh
- LinkedIn: https://www.linkedin.com/school/university-of-pittsburgh/
- Source Code (Library System dev team): https://github.com/ulsdevteam

## Notes

- Pitt has no single official central developer portal; its API surface is split across research projects (Project Tycho), a regional open-data partnership (WPRDC), library systems (D-Scholarship), and a community-maintained library (PittAPI).
- All URLs were probed on 2026-06-03. The WPRDC CKAN API, Project Tycho, PittAPI repo, and GitHub orgs returned HTTP 200. The D-Scholarship OAI-PMH endpoint returned 403 to an automated client (bot protection — verify interactively). LinkedIn returned 999 (bot block; the page is real).
- No endpoints were fabricated. PittAPI is community/unofficial; verify before relying on it.

## Maintainers

- Kin Lane — kin@apievangelist.com
