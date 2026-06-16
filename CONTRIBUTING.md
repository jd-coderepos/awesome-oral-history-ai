# Contributing

Thank you for helping improve this community resource. This repository is a Markdown-only curated awesome list, not a data mirror, software platform, or project-specific bibliography.

The goal of these guidelines is to make community and automated pull requests easy to review.

## Quick Contribution Rules

- Add only publicly verifiable resources.
- Prefer one resource per pull request, or a small themed batch of up to five resources.
- Add concise awesome-list entries, not long descriptions.
- Link to an official or institutionally reliable source.
- Do not add restricted data, copied testimony text, scraped content, PDFs, media files, notebooks, scripts, or generated datasets.
- If access, license, format, or relevance is unclear, add the item to `Needs Verification` instead of the main list.

## Where to Add a Resource

Use this decision path:

1. If the resource is clearly relevant and publicly verifiable, add it to one primary section in `README.md`.
2. If it also helps users browse by task or language, add it to the matching index section.
3. If the access status is clear, add it under the correct `Browse by Access` subsection.
4. If any core facts are unclear, add it only to `Needs Verification`.

Primary sections:

- `Open Datasets`
- `Access-Limited Archives`
- `Catalogs & Discovery`
- `Annotations & Benchmarks`
- `Vocabularies & Authorities`
- `Tools & Platforms`

Indexes:

- `Tasks & Methods`
- `Browse by Language`
- `Browse by Access`

## Entry Format

Use this one-line format for main list entries:

```markdown
- [Resource Name](https://official.example.org/) - One concise, neutral sentence. 📄 `Text` 🟢 `Open`
```

Use the shortest accurate description possible. Avoid promotional wording.

## Required Information

Every main-list resource should have enough public documentation to verify:

- Resource name.
- Official URL.
- Maintainer, institution, or project.
- One-sentence description.
- Modality, such as text, audio, video, metadata, model, or tool.
- Language coverage, if documented.
- Access level.
- License or terms, if available.
- Relevant tasks, such as ASR, search, RAG, NER, entity linking, sentiment analysis, OCR, or responsible AI evaluation.
- Ethical, legal, or access constraints, if relevant.

## Tags

Use the README legend tags exactly. Include symbols when adding tags to resource lines.

Access tags:

- 🟢 `Open`: direct download under stated terms.
- 🔵 `Web`: searchable or viewable online, but bulk download may not be available.
- 🟡 `Metadata`: public records or descriptions are available, but full content may not be.
- 🟠 `Register`: account, registration, request, or approval needed.
- 🔴 `Institutional`: reading room, access site, subscribing institution, or approved network needed.
- ⚫ `Restricted`: explicit permission, data agreement, or special license needed.
- ❓ `Verify`: access, license, scope, or format is not confirmed.

Modality tags:

- 📄 `Text`
- 🔊 `Audio`
- 🎞️ `Video`
- 🧩 `Multimodal`
- 🔍 `OCR`
- 🗂️ `Metadata`
- 🏷️ `NER`
- 🧭 `Authority`
- 🛠️ `Tool`
- 🤖 `Model`

Do not call something `Open` unless there is a clear download path and stated license or terms.

## Main List or Needs Verification

Add to the main list only when all of these are true:

- The URL is official or institutionally reliable.
- The resource is directly relevant to oral history, testimony, archives, cultural heritage, or sensitive narrative collections.
- Access status is clear enough to tag.
- The description can be supported by public documentation.
- The entry does not expose personal data or protected content.

Add to `Needs Verification` when:

- The resource was mentioned in a paper, talk, or notes but has no clear public landing page.
- The license, access status, language coverage, or format is unclear.
- It may be relevant but needs review before being presented as usable.
- It appears to be based on restricted testimony data and reuse terms are not public.

## Automated PR Checklist

Automated pull requests should include this information in the PR body:

```markdown
## Resource

- Name:
- Official URL:
- Maintainer / institution:
- Proposed README section:
- Proposed tags:
- Access status:
- License / terms URL:
- Language coverage:
- Why it belongs:

## Verification

- [ ] I used an official or institutionally reliable URL.
- [ ] I did not add restricted data, copied testimony content, or personal data.
- [ ] I checked whether the resource belongs in the main list or Needs Verification.
- [ ] I used the README tag vocabulary.
- [ ] I added a concise, neutral one-sentence description.
- [ ] I updated relevant browse sections, if applicable.
```

## Sensitive-Data Policy

Do not contribute:

- Restricted testimony data.
- Scraped testimony content.
- Personal data copied from archives.
- Mirrors of protected audio, video, transcripts, images, or documents.
- Model-training recipes that assume unauthorized reuse of restricted collections.

Respect archive terms, consent contexts, survivor and interviewee dignity, and community expectations. When in doubt, link to official metadata or documentation rather than copying content.

## Review Checklist

Maintainers can review a PR by checking:

- Does the PR touch only Markdown guidance/list files?
- Is each new URL official or institutionally reliable?
- Is each new resource directly relevant?
- Are access and modality tags accurate?
- Is the license or terms page linked or easy to find?
- Are language coverage and formats supported by public documentation?
- Is the wording concise, neutral, and non-promotional?
- Does the PR avoid personal data and protected content?
- Should the item be moved to `Needs Verification`?

## Style Guide

- Use one line per resource.
- Keep descriptions short and factual.
- Use sentence case.
- Keep tags short and consistent.
- Do not overclaim.
- Use `unknown`, `access unclear`, or ❓ `Verify` when uncertain.
- Prefer 🔵 `Web` or 🟡 `Metadata` when full download is not clearly available.
- Do not quote non-public notes, correspondence, restricted documents, or project materials.
