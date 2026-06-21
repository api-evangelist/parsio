# Parsio (parsio)

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
