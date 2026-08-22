# Azure Storage Accounts (azure-storage-accounts)

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

Azure Storage is Microsoft's cloud storage solution offering highly available, massively scalable storage for blobs, files, queues, tables, and disks.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Blob Storage, Cloud Storage, File Storage, Queue Storage, Storage, Table Storage

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Azure Storage Accounts
Azure Storage is Microsoft's cloud storage solution offering highly available, massively scalable storage for blobs, files, queues, tables, and disks.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/storageservices/](https://learn.microsoft.com/en-us/rest/api/storageservices/)

#### Tags:

 - Blob Storage, Management, Storage

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/storageservices/)
- [OpenAPI](openapi/azure-storage-accounts-blob-openapi.yaml)
- [OpenAPI](openapi/azure-storage-accounts-management-openapi.yaml)

## Common Properties


## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Blob](openapi/azure-storage-accounts-blob-openapi.yaml)
- [Management](openapi/azure-storage-accounts-management-openapi.yaml)

### JSON Schema

- [Lease Container Request](json-schema/azure-storage-accounts-lease-container-request-schema.json)
- [List Container Item](json-schema/azure-storage-accounts-list-container-item-schema.json)
- [Container Properties](json-schema/azure-storage-accounts-container-properties-schema.json)
- [Identity](json-schema/azure-storage-accounts-identity-schema.json)
- [Encryption](json-schema/azure-storage-accounts-encryption-schema.json)
- [Custom Domain](json-schema/azure-storage-accounts-custom-domain-schema.json)
- [Legal Hold](json-schema/azure-storage-accounts-legal-hold-schema.json)
- [Blob Container](json-schema/azure-storage-accounts-blob-container-schema.json)
- [Lease Container Response](json-schema/azure-storage-accounts-lease-container-response-schema.json)
- [Management Policy Base Blob](json-schema/azure-storage-accounts-management-policy-base-blob-schema.json)

### JSON-LD

- [Azure Storage Accounts Context](json-ld/azure-storage-accounts-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Storage Accounts](capabilities/shared/azure-storage-accounts.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|----------|
| [Azure Storage Accounts Management](capabilities/azure-storage-accounts-management.yaml) | Azure Storage Accounts | 5 | Cloud Engineer |

## Vocabulary

- [Azure Storage Accounts Vocabulary](vocabulary/azure-storage-accounts-vocabulary.yaml)

## Rules

- [Azure Storage Accounts Spectral Rules](rules/azure-storage-accounts-spectral-rules.yml) — 15 rules enforcing Azure Storage Accounts API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
