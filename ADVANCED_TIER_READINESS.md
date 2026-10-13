# GEST — Crossref Advanced Tier Readiness

**Status:** Technical readiness documentation for review. This document does not claim Crossref accreditation.

## 1. Alternative metadata delivery options

GEST provides web-based metadata workflows and is developing an OJS integration prototype.

- Smart Deposit AI: https://provider.gest.co.in/smart-deposit
- Rich Metadata Deposit: https://provider.gest.co.in/rich-metadata-deposit
- Rich Metadata Audit: https://provider.gest.co.in/rich-metadata-audit
- OJS integration source: https://github.com/GEST-India/gest-crossref-ojs-plugin

**Evidence to demonstrate:** Show which workflows prepare metadata, which validate it, and which submit deposits. Demonstrate an end-to-end submission separately.

## 2. Recommended and optional metadata

The platform's intended metadata coverage includes:

- Authors, ORCID iDs, and affiliations
- Abstracts and publication dates
- References and citation information
- Funding and licence information
- Full-text URLs and applicable policy metadata
- Other supported fields appropriate to the content type

**Evidence to demonstrate:** Representative XML records, field mappings, validation results, and examples of optional fields populated correctly.

## 3. Current schema support

GEST targets Crossref schema **5.5.0** for full metadata deposits.

Official documentation:
https://www.crossref.org/documentation/schema-library/metadata-deposit-schema/

**Evidence to demonstrate:** Reproducible XSD validation results for representative record types. XML schema validation does not prove that Crossref has accepted or processed a deposit.

## 4. Basic-tier capabilities must also be demonstrated

Advanced-tier applicants must meet the Basic-tier requirements as well, including:

- Register required metadata on behalf of members.
- Support and display multiple client prefixes.
- Maintain DOI resolution following platform migrations.
- Provide active platform support to members.
- Follow Crossref DOI display guidelines.
- Maintain communication with Crossref and/or participate in training.
- Notify Crossref about qualifying large-scale metadata updates.
- Use member credentials when registering content on their behalf.
- Follow appropriate credential security and account-protection practices.

## 5. Suggested technical evidence

1. Demonstration of Smart Deposit AI, including human review of extracted fields.
2. Demonstration of the rich metadata workflow and its validation output.
3. Sample XML files and validation logs for schema 5.5.0.
4. OJS installation instructions and a clean installation test.
5. Test-system deposit receipt and confirmation of processing status.
6. Evidence of multi-prefix support, credential isolation, error handling, and client support procedures.

## 6. Important limitations

- A metadata extraction or JSON export is not a completed Crossref deposit.
- An XML validation result is not proof of successful deposit processing.
- Prototype availability is not proof of production readiness.
- GEST must not describe itself as an accredited Advanced-tier provider unless Crossref grants that status.

## Official programme requirements

https://www.crossref.org/community/service-providers/
