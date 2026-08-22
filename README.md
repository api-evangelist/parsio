# Parsio (parsio)

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

Parsio is an AI-powered document and email parser that extracts structured data from PDFs, emails, and other documents. The Parsio REST API lets developers create mailboxes (parsers), upload documents and emails for parsing, retrieve the extracted structured JSON, and subscribe to webhooks for parsed-data delivery, with four extraction engines (template, AI, GPT, and AI OCR).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/parsio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/parsio/refs/heads/main/apis.yml)

## Tags

- AI
- Document Parsing
- Email Parsing
- OCR
- Data Extraction

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Parsio Mailboxes API

List, retrieve, create, update, and delete mailboxes (parsers), and manage their table fields and parsing templates. Each mailbox represents a configured parser bound to one of Parsio's extraction engines.

- **Human URL:** [https://help.parsio.io/public-api/parsio-public-api](https://help.parsio.io/public-api/parsio-public-api)
- **Base URL:** `https://api.parsio.io`

#### Tags

- Mailboxes
- Parsers
- Templates

#### Properties

- [Documentation](https://help.parsio.io/public-api/parsio-public-api)
- [API Reference](https://help.parsio.io/public-api)
- [OpenAPI](openapi/parsio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/parsio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/parsio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Parsio Documents API

Upload PDFs and files (synchronously or asynchronously), submit HTML or plain-text documents for parsing, list documents with pagination and filters, retrieve the extracted structured JSON for a document, reparse, and skip documents.

- **Human URL:** [https://help.parsio.io/public-api/parse-pdf-and-files-using-api-1](https://help.parsio.io/public-api/parse-pdf-and-files-using-api-1)
- **Base URL:** `https://api.parsio.io`

#### Tags

- Documents
- Upload
- Parsing

#### Properties

- [Documentation](https://help.parsio.io/public-api/parse-pdf-and-files-using-api-1)
- [API Reference](https://help.parsio.io/public-api/parse-html-and-text-documents-using-api-1)
- [OpenAPI](openapi/parsio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/parsio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/parsio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Parsio Webhooks API

List, retrieve, create, update, and delete webhooks bound to a mailbox to receive parsed data in real time. Supported events include doc.parsed, doc.parsed.flat, doc.fail, doc.received, and table.parsed.

- **Human URL:** [https://help.parsio.io/public-api/parsio-public-api](https://help.parsio.io/public-api/parsio-public-api)
- **Base URL:** `https://api.parsio.io`

#### Tags

- Webhooks
- Events
- Delivery

#### Properties

- [Documentation](https://help.parsio.io/public-api/parsio-public-api)
- [OpenAPI](openapi/parsio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/parsio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/parsio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/parsio)
- [Website](https://parsio.io)
- [Documentation](https://help.parsio.io/public-api)
- [Plans](plans/parsio-plans-pricing.yml)
- [Rate Limits](rate-limits/parsio-rate-limits.yml)
- [Fin Ops](finops/parsio-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
