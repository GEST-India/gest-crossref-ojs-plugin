# GEST Crossref OJS Integration and Smart Deposit AI

GEST is developing scholarly metadata infrastructure to help publishers prepare, validate, review, and submit richer metadata to Crossref.

## GEST Service Provider Hub

- **Main Hub:** https://provider.gest.co.in/
- **Smart Deposit AI:** https://provider.gest.co.in/smart-deposit
- **Rich Metadata Deposit:** https://provider.gest.co.in/rich-metadata-deposit
- **Rich Metadata Audit:** https://provider.gest.co.in/rich-metadata-audit
- **OJS integration prototype:** https://github.com/GEST-India/gest-crossref-ojs-plugin

## Smart Deposit AI

The Smart Deposit workflow assists users in extracting article metadata from supplied content, reviewing extracted fields, viewing validation previews, and exporting structured JSON for subsequent workflow steps.

Metadata preparation and export do not, by themselves, confirm that a DOI deposit has been accepted by Crossref. Live AI-provider operation and successful deposit processing must be verified separately.

## Crossref metadata schema 5.5.0

GEST targets Crossref schema **5.5.0** for full metadata deposits. The metadata workflow is designed to support:

- Article and journal bibliographic details
- Authors, ORCID iDs, and affiliations
- Abstracts and publication dates
- References and citation information
- Funding and licence metadata
- Full-text and text-mining URLs
- Applicable policy and relationship metadata
- Other supported recommended and optional elements

Crossref's official documentation identifies schema 5.5.0 as the recommended version for registering complete metadata.

Official references:
- https://www.crossref.org/documentation/schema-library/metadata-deposit-schema/
- https://www.crossref.org/documentation/schema-library/required-recommended-elements/

## Advanced Service Provider readiness

The GEST platform is being developed around the additional capabilities relevant to Crossref's Advanced Service Provider tier:

1. Alternative metadata delivery workflows, including web-based metadata preparation and an OJS integration prototype.
2. Support for recommended and optional metadata elements.
3. Support for current Crossref metadata schema versions, targeting version 5.5.0.

Advanced-tier readiness also depends on demonstrating the Basic-tier operational requirements, including multiple client prefixes, secure use of member credentials, DOI resolution, and active client support.

See [ADVANCED_TIER_READINESS.md](ADVANCED_TIER_READINESS.md) for the requirements and evidence checklist.

## Current status

This repository represents a **prototype under review**, not Crossref accreditation.

Schema validation, successful live deposit submission, and confirmation that Crossref has processed a deposit are separate checks. Production readiness must be supported by reproducible tests and evidence.

Never publish passwords, API keys, private environment files, database files, or client credentials in this repository.

## Official programme information

https://www.crossref.org/community/service-providers/
