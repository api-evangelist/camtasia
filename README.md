# Camtasia (camtasia)

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

Camtasia is a screen recording and video editing software by TechSmith that allows users to create professional videos, tutorials, and presentations with built-in editing tools, effects, and media assets. Camtasia itself does not publish a public REST API, but it integrates tightly with TechSmith Screencast for sharing, and TechSmith publishes a public Screencast oEmbed API plus the Camtasia Screen Recorder SDK for embedding recording capabilities into third-party applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Screen Recording
- Video Editing
- Tutorial Creation
- E-Learning
- Screencast
- oEmbed
- SDK

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### TechSmith Screencast oEmbed API

Public oEmbed API for TechSmith Screencast (app.screencast.com), the cloud destination where Camtasia videos and images are shared. The oEmbed endpoint returns embed HTML, thumbnail, and metadata for a given Screencast content URL, letting content platforms and CMSes render Screencast shares inline the same way they render YouTube or Vimeo. Documentation is maintained in a public GitHub repository.

- **Human URL:** [https://github.com/TechSmith/screencast-public-api-docs](https://github.com/TechSmith/screencast-public-api-docs)
- **Base URL:** `https://app.screencast.com/services/oembed`

#### Tags

- oEmbed
- Screencast
- Embedding
- Video

#### Properties

- [Documentation](https://github.com/TechSmith/screencast-public-api-docs/blob/main/sections/oembed.md)
- [Repository](https://github.com/TechSmith/screencast-public-api-docs)
- [JSON-LD](json-ld/camtasia-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Postman Collection](collections/camtasia-asset-library.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camtasia-asset-library.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/camtasia-project-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camtasia-project-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)


#### Tags

- SDK
- Screen Recording
- Embedded

#### Properties

- [Product Page](https://www.techsmith.com/camtasia.html)
- [Postman Collection](collections/camtasia-asset-library.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camtasia-asset-library.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/camtasia-project-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/camtasia-project-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/techsmith-corporation)
- [Website](https://www.techsmith.com/camtasia.html)
- [Screencast](https://www.techsmith.com/screencast/)
- [Getting Started](https://www.techsmith.com/learn/camtasia/)
- [Blog](https://www.techsmith.com/blog/category/camtasia/)
- [Support](https://support.techsmith.com)
- [Public A P I Repository](https://github.com/TechSmith/screencast-public-api-docs)
- [Terms of Service](https://www.techsmith.com/terms.html)
- [Privacy Policy](https://www.techsmith.com/privacy.html)
- [JSON-LD](json-ld/camtasia-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://www.techsmith.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
