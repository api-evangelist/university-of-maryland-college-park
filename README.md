# University of Maryland College Park

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Maryland, College Park (UMD) is the flagship public research university of the University System of Maryland and the state's original 1862 land-grant institution. UMD operates no central developer portal and publishes no university-wide API programme. Its entire confirmed programmable footprint is run by three offices. UMD Libraries publish an Open Data site at opendata.lib.umd.edu documenting the interfaces they operate: a keyless FastAPI service for library hours and bookable-space availability, three live OAI-PMH 2.0 endpoints over digital collections, audio/video collections and ArchivesSpace finding aids, an OpenSearch descriptor over the Avalon A/V catalog, and IIIF Image and Presentation servers. The Division of IT operates the university's Shibboleth identity provider, which publishes SAML 2.0 metadata as InCommon entity urn:mace:incommon:umd.edu with the Research and Scholarship category and SIRTFI assurance — the most consequential machine-readable contract UMD runs, and one no vendor catalogues. The campus GIS office runs an ArcGIS Enterprise 12.1 deployment at gis.umd.edu whose REST service catalog, server info and portal endpoints answer keyless JSON while the fourteen service folders beneath them require a token — the machine-readable backend of the official campus map, and undocumented outside the map itself. Everything else that looks like a UMD API is somebody else's engineering. umd.io, the widely cited course, bus and campus-map API, is a student-run independent project on a NameCheap-registered .io domain hosted at DigitalOcean that states plainly it is not the school; the library discovery layer is Ex Libris Primo through the USMAI consortium; the LMS is Instructure Canvas; web archiving is Archive-It; the open-data repository referral is Dryad. Those are recorded here as tenant relationships, not as UMD's contracts. The DRUM institutional repository is genuinely UMD-operated and was serving a maintenance page across every one of its hosts throughout this review.

**Areas:** University · Higher Education · Education · United States · Maryland · Public Research University · Land Grant · Big Ten · Library · Research Data · Digital Collections · Identity Federation

## University of Maryland College Park on APIs.io

Everything profiled for University of Maryland College Park is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-maryland-college-park/](https://apis.io/providers/university-of-maryland-college-park/)** — or go straight to one of the APIs or properties below.

### APIs (20)

- [UMD Libraries Digital Collections OAI-PMH](https://apis.io/apis/university-of-maryland-college-park/digital-collections-oai/) — OAI-PMH 2.0 harvesting endpoint over UMD Libraries' Fedora-backed digital collections. Identify reports repositoryName "UMD Libraries" and adminEmail…
- [UMD Libraries Audio/Video Collections OAI-PMH and OpenSearch](https://apis.io/apis/university-of-maryland-college-park/av-collections-oai/) — The Libraries' Avalon Media System deployment for audio and video collections, with an OAI-PMH 2.0 endpoint (repositoryName "UMD Libraries", adminEmail…
- [UMD Archival Collections OAI-PMH](https://apis.io/apis/university-of-maryland-college-park/archival-collections-oai/) — OAI-PMH 2.0 endpoint over the Libraries' ArchivesSpace instance, exposing finding aids for Special Collections and the Performing Arts collections. Identify…
- [UMD Shibboleth Identity Provider — SAML 2.0 Metadata](https://apis.io/apis/university-of-maryland-college-park/identity-federation/) — The university's own Shibboleth identity provider, publishing a SAML 2.0 EntityDescriptor as InCommon entity urn:mace:incommon:umd.edu with scope umd.edu,…
- [UMD Libraries IIIF Services](https://apis.io/apis/university-of-maryland-college-park/iiif-services/) — IIIF Image and Presentation services operated by UMD Libraries — a Cantaloupe 5.0.5 image server and Papaya 1.2.0, the Libraries' own IIIF Presentation API…
- [UMD Enterprise GIS — ArcGIS REST Services](https://apis.io/apis/university-of-maryland-college-park/enterprise-gis/) — The university's own ArcGIS Enterprise deployment — ArcGIS Server 12.1.0 and Portal 2026.1 at gis.umd.edu — and the machine-readable backend behind the…
- [DRUM — Digital Repository at the University of Maryland](https://apis.io/apis/university-of-maryland-college-park/drum/) — UMD Libraries' DSpace 7 institutional repository of UMD scholarship and research data, and the university's DOI-minting surface. UMD Libraries document a…
- [Testudo Schedule of Classes](https://apis.io/apis/university-of-maryland-college-park/testudo-soc/) — The Office of the Registrar's public Schedule of Classes, a server-rendered web application for browsing course offerings by term and department. It is the…
- [umd.io — student-run University of Maryland data API](https://apis.io/apis/university-of-maryland-college-park/umd-io/) — A read-only REST API over UMD course, section, professor, campus bus, building/map and major data, covering ground the university itself does not expose…
- [UMD Discover — library discovery layer](https://apis.io/apis/university-of-maryland-college-park/umd-discover/) — UMD's library catalog and discovery layer, delivered as Ex Libris Primo through the University System of Maryland and Affiliated Institutions (USMAI)…
- [UMD Web Archives on Archive-It](https://apis.io/apis/university-of-maryland-college-park/archive-it/) — UMD Libraries' web archiving programme, operated as Archive-It organization 408 at the Internet Archive. UMD Libraries document Archive-It's OpenSearch…
- [UMD Collection on the Internet Archive](https://apis.io/apis/university-of-maryland-college-park/internet-archive/) — The University of Maryland, College Park collection at the Internet Archive, documented by UMD Libraries as one of their ten Open Data services with…
- [UMD Research Data on Dryad](https://apis.io/apis/university-of-maryland-college-park/dryad/) — UMD Libraries refer researchers to Dryad for open research-data deposit and document Dryad's v2 REST API as the access route, scoped to UMD by ROR…
- [BTAA Geoportal — UMD geospatial contributions](https://apis.io/apis/university-of-maryland-college-park/btaa-geoportal/) — The Big Ten Academic Alliance Geoportal, a consortium-operated discovery layer for geospatial data to which UMD Libraries contribute records. Operated by…
- [ELMS-Canvas — UMD learning management system](https://apis.io/apis/university-of-maryland-college-park/elms-canvas/) — UMD's learning management system, an Instructure Canvas tenancy at umd.instructure.com fronted by elms.umd.edu. Requests to the tenancy redirect to UMD's…
- [University of Maryland College Park Art API](https://apis.io/apis/university-of-maryland-college-park/university-of-maryland-college-park-art-api/) — The Art API from University of Maryland College Park — 3 operation(s) for art.
- [University of Maryland College Park Makerspace API](https://apis.io/apis/university-of-maryland-college-park/university-of-maryland-college-park-makerspace-api/) — The Makerspace API from University of Maryland College Park — 1 operation(s) for makerspace.
- [University of Maryland College Park Mckeldin API](https://apis.io/apis/university-of-maryland-college-park/university-of-maryland-college-park-mckeldin-api/) — The Mckeldin API from University of Maryland College Park — 3 operation(s) for mckeldin.
- [University of Maryland College Park Mspal API](https://apis.io/apis/university-of-maryland-college-park/university-of-maryland-college-park-mspal-api/) — The Mspal API from University of Maryland College Park — 3 operation(s) for mspal.
- [University of Maryland College Park Stem API](https://apis.io/apis/university-of-maryland-college-park/university-of-maryland-college-park-stem-api/) — The Stem API from University of Maryland College Park — 3 operation(s) for stem.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (3)

The data models the API reads and writes.

- [UMD Libraries today's open status](https://apis.io/schemas/university-of-maryland-college-park/university-of-maryland-college-park-hours-today/)
- [UMD Libraries space availability](https://apis.io/schemas/university-of-maryland-college-park/university-of-maryland-college-park-space-availability/)
- [UMD Libraries raw space records](https://apis.io/schemas/university-of-maryland-college-park/university-of-maryland-college-park-space-details/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [umd.io API Vocabulary](https://apis.io/vocabularies/university-of-maryland-college-park/university-of-maryland-college-park-vocabulary/)

#### Examples (4)

Example requests and responses.

- [University Of Maryland College Park Art Details Example](https://apis.io/examples/university-of-maryland-college-park/university-of-maryland-college-park-art-details-example/)
- [University Of Maryland College Park Mckeldin Availability Example](https://apis.io/examples/university-of-maryland-college-park/university-of-maryland-college-park-mckeldin-availability-example/)
- [University Of Maryland College Park Mckeldin Hours Today Example](https://apis.io/examples/university-of-maryland-college-park/university-of-maryland-college-park-mckeldin-hours-today-example/)
- [University Of Maryland College Park Stem Availability Example](https://apis.io/examples/university-of-maryland-college-park/university-of-maryland-college-park-stem-availability-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [University of Maryland College Park API Rules](https://apis.io/rules/university-of-maryland-college-park/university-of-maryland-college-park-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Maryland College Park Authentication](https://apis.io/security/university-of-maryland-college-park/university-of-maryland-college-park-authentication/)
- [University Of Maryland College Park Domain Security](https://apis.io/security/university-of-maryland-college-park/university-of-maryland-college-park-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [University Of Maryland College Park Scopes](https://apis.io/scopes/university-of-maryland-college-park/university-of-maryland-college-park-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Maryland College Park Plans Pricing](https://apis.io/plans/university-of-maryland-college-park/university-of-maryland-college-park-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Maryland College Park Rate Limits](https://apis.io/rate-limits/university-of-maryland-college-park/university-of-maryland-college-park-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Maryland College Park Finops](https://apis.io/finops/university-of-maryland-college-park/university-of-maryland-college-park-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.umd.edu)
- [Documentation](https://opendata.lib.umd.edu/services/)
- [API reference](https://opendata.lib.umd.edu/apis/)
- [Support](https://opendata.lib.umd.edu/contact/)
- [Blog](https://today.umd.edu/rss)
- [Privacy policy](https://umd.edu/privacy-notice)
- [GitHub](https://github.com/umd-lib)

## API Evangelist rating

**Kin Score 30.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 36.5 |
| Contract governance | 7.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 45.2 |
| Access clarity | 15.8 |

**Agent readiness 18.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-maryland-college-park/](https://apis.io/providers/university-of-maryland-college-park/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Maryland College Park: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-maryland-college-park/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
