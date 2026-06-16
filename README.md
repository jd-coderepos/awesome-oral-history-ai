# Awesome Holocaust Testimony and Oral History AI Resources [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Status: Curated Draft](https://img.shields.io/badge/status-curated%20draft-yellow.svg)](#contributing)

> A curated list of datasets, archives, tools, models, and vocabularies for AI/NLP research with Holocaust testimonies and oral-history collections.

This list helps researchers quickly find public and access-limited resources for transcription, search, retrieval, annotation, entity linking, multimodal analysis, and responsible use of oral-history materials.

This repository does not host, mirror, scrape, or redistribute testimony data. Each linked resource remains governed by its own license, access conditions, ethical restrictions, and terms of use.

## Quick Browse

| Datasets & Archives | Tasks & Methods | Modality & Language | Access & Reuse |
| --- | --- | --- | --- |
| [Open Datasets](#open-datasets) | [Search & Retrieval](#search--retrieval) | [📄 Text & Transcripts](#text--transcripts) | [🟢 Open Download](#open-download) |
| [Access-Limited Archives](#access-limited-archives) | [RAG & QA](#rag--qa) | [🔊 Audio & ASR](#audio--asr) | [🔵 Public Web Access](#public-web-access) |
| [Catalogs & Discovery](#catalogs--discovery) | [ASR & Alignment](#asr--alignment) | [🎞️ Video & Multimodal](#video--multimodal) | [🟠 Registration Required](#registration-required) |
| [Annotations & Benchmarks](#annotations--benchmarks) | [🏷️ NER & Entity Linking](#ner--entity-linking) | [Yiddish & Low-Resource](#yiddish--low-resource) | [🔴 Institutional / ⚫ Restricted](#institutional--restricted) |
| [Vocabularies & Authorities](#vocabularies--authorities) | [Sentiment, Emotion & Topics](#sentiment-emotion--topics) | [Multilingual Resources](#multilingual-resources) | [❓ Needs Verification](#needs-verification) |
| [Tools & Platforms](#tools--platforms) | [🤖 LLM Evaluation](#llm-evaluation) | [🔍 Images, OCR & Documents](#images-ocr--documents) | [Responsible Use](#responsible-use) |

## Contents

- [Open Datasets](#open-datasets)
- [Access-Limited Archives](#access-limited-archives)
- [Catalogs & Discovery](#catalogs--discovery)
- [Annotations & Benchmarks](#annotations--benchmarks)
- [Vocabularies & Authorities](#vocabularies--authorities)
- [Tools & Platforms](#tools--platforms)
- [Tasks & Methods](#tasks--methods)
- [Browse by Language](#browse-by-language)
- [Browse by Access](#browse-by-access)
- [Needs Verification](#needs-verification)
- [Responsible Use](#responsible-use)
- [Contributing](#contributing)

## Legend

### Access Tags

| Tag | Meaning |
| --- | --- |
| 🟢 `Open` | Direct download under stated terms. |
| 🔵 `Web` | Public online search or viewing; bulk download may not be available. |
| 🟡 `Metadata` | Public descriptions, catalog records, or metadata; full content may not be available. |
| 🟠 `Register` | Account, registration, request, or approval required. |
| 🔴 `Institutional` | Access site, reading room, subscribing institution, or approved network required. |
| ⚫ `Restricted` | Explicit permission, licensing, or a data agreement required. |
| ❓ `Verify` | Access, license, scope, or format still needs confirmation. |

### Modality Tags

| Tag | Meaning |
| --- | --- |
| 📄 `Text` | Transcripts, subtitles, documents, or plain text. |
| 🔊 `Audio` | Speech recordings or audio-derived resources. |
| 🎞️ `Video` | Video testimony or video-derived material. |
| 🧩 `Multimodal` | Combined text, audio, video, images, gesture, or paraverbal cues. |
| 🔍 `OCR` | Scanned documents, PDFs, images, OCR, or layout extraction. |
| 🗂️ `Metadata` | Catalog records, collection descriptions, indexes, or archival metadata. |
| 🏷️ `NER` | Named entity recognition datasets, annotations, or models. |
| 🧭 `Authority` | Gazetteers, thesauri, authority files, or entity-linking targets. |
| 🛠️ `Tool` | Software, services, or platforms. |
| 🤖 `Model` | Machine-learning or language models. |

## Open Datasets

- [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k) - English Holocaust survivor testimony transcripts from the Placing the Holocaust project. 📄 `Text` 🟢 `Open` `RAG` `Search`
- [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org/csye/) - Open-access digital language archive sourced from Yiddish-speaking Holocaust survivor interviews, with audio and aligned transcripts. 🔊 `Audio` 📄 `Text` `Yiddish` 🟢 `Open`
- [Densho Digital Repository](https://ddr.densho.org/) - Public repository of Japanese American incarceration oral histories, photographs, documents, and other primary sources. 📄 `Text` 🎞️ `Video` 🗂️ `Metadata` 🔵 `Web`
- [LLM4OralHistoryAnalysis](https://github.com/kc6699c/LLM4OralHistoryAnalysis) - Code, prompts, and datasets for LLM-based topic classification and sentiment analysis on Japanese American incarceration oral histories. 📄 `Text` 🤖 `Model` `Annotations` 🟢 `Open`

## Access-Limited Archives

- [USC Shoah Foundation Visual History Archive](https://sfi.usc.edu/what-we-do/collections) - Large multilingual video testimony archive with controlled access through the Visual History Archive. 🎞️ `Video` 🧩 `Multimodal` 🔴 `Institutional`
- [Fortunoff Video Archive on Aviary](https://fortunoff.aviaryplatform.com/) - Yale's Holocaust testimony archive on Aviary, with registration, request, and access-site requirements. 🎞️ `Video` 🔊 `Audio` 🟠 `Register` ⚫ `Restricted`
- [USHMM Oral History Archive](https://www.ushmm.org/collections/the-museums-collections/about/oral-history) - United States Holocaust Memorial Museum oral-history collection; many interviews are online, while some require reading-room access. 🎞️ `Video` 🔊 `Audio` 🗂️ `Metadata` 🔵 `Web`
- [Oral-History.Digital](https://www.oral-history.digital/) - German interview portal, indexing platform, and research environment for audiovisual narrative interviews. 🔊 `Audio` 🎞️ `Video` 🗂️ `Metadata` 🟠 `Register`

## Catalogs & Discovery

- [EHRI Portal](https://portal.ehri-project.eu/) - Cross-institutional discovery portal for Holocaust-related archival material. 🗂️ `Metadata` 🔵 `Web` `Discovery`
- [EHRI Online Editions](https://www.ehri-project.eu/ehri-online-editions/) - Digital editions from the European Holocaust Research Infrastructure. 📄 `Text` 🗂️ `Metadata` 🔵 `Web`
- [Arolsen Archives Online Search](https://arolsen-archives.org/en/archive/online-search/) - Public search for digitized records on Nazi persecution. 🔍 `OCR` 🗂️ `Metadata` 🔵 `Web`
- [CLARIN Virtual Language Observatory](https://vlo.clarin.eu/) - Discovery interface for language resources and tools across CLARIN repositories. 🗂️ `Metadata` `Discovery` ❓ `Verify`

## Annotations & Benchmarks

- [Placing the Holocaust](https://huggingface.co/placingholocaust) - Project organization with place-focused Holocaust testimony datasets and NER models. 🏷️ `NER` 📄 `Text` 🤖 `Model`
- [Placing Holocaust GLiNER Small](https://huggingface.co/placingholocaust/gliner_small-v2.1-holocaust) - Fine-tuned GLiNER model for Holocaust place and spatial-entity recognition. 🏷️ `NER` 🤖 `Model` 🟢 `Open`
- [LLM4OralHistoryAnalysis](https://github.com/kc6699c/LLM4OralHistoryAnalysis) - Annotated oral-history classification and sentiment-analysis resources. `Annotations` `Sentiment` 🤖 `Model`
- [Designing Spontaneous Speech Search Interface for Historical Archives](https://arxiv.org/abs/1312.4706) - Paper on search interface design for large audiovisual testimony archives. `Search` `Interface` `Paper`
- [Human and Automatic Speech Recognition Performance on German Oral History Interviews](https://arxiv.org/abs/2201.06841) - ASR study on German oral-history interviews. `ASR` `German` `Paper`

## Vocabularies & Authorities

- [GND](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html) - Integrated Authority File for persons, corporate bodies, events, geographic entities, topics, and works. 🧭 `Authority` 🟢 `Open`
- [GeoNames](https://www.geonames.org/) - Global gazetteer and web service for place-name lookup and geocoding. 🧭 `Authority` 🟢 `Open`
- [ELSST](https://elsst.cessda.eu/) - European Language Social Science Thesaurus for multilingual social-science subject indexing. 🧭 `Authority` `Multilingual` 🟢 `Open`
- [EHRI Portal](https://portal.ehri-project.eu/) - Useful as a Holocaust-specific archival authority and discovery context, even when full content remains external. 🗂️ `Metadata` 🧭 `Authority` 🔵 `Web`

## Tools & Platforms

- [OHMS Viewer](https://github.com/uklibraries/ohms-viewer) - Open-source viewer for synchronized oral-history transcripts, indexes, and media playback. 🛠️ `Tool` 📄 `Text` 🟢 `Open`
- [Aviary](https://www.aviaryplatform.com/) - Audiovisual publishing and access platform built for libraries, archives, and oral histories. 🛠️ `Tool` 🔊 `Audio` 🎞️ `Video` ⚫ `Restricted`
- [Oral-History.Digital](https://www.oral-history.digital/) - Platform for interview indexing, transcription-related workflows, search, and registered research use. 🛠️ `Tool` 🗂️ `Metadata` 🟠 `Register`
- [Oral History in the Digital Age](https://ohda.matrix.msu.edu/) - Best-practice resource for digital oral-history collection, curation, access, metadata, transcription, and ethics. `Guidance` 🛠️ `Tooling`
- [BAS Web Services](https://clarin.phonetik.uni-muenchen.de/BASWebServices/interface/WebMAUSBasic) - CLARIN/BAS speech-processing services such as segmentation and labelling. `ASR` `Alignment` 🛠️ `Tool`
- [Speech Technology Services for Oral History Research](https://arxiv.org/abs/2405.02333) - Overview paper on speech technology services for oral-history research, including BAS, LINDAT, and Whisper workflows. `ASR` `Paper` `Guidance`

## Tasks & Methods

### Search & Retrieval

- [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k) - Transcript set for segment retrieval and search experiments.
- [EHRI Portal](https://portal.ehri-project.eu/) - Metadata-rich archival discovery.
- [Oral-History.Digital](https://www.oral-history.digital/) - Cross-collection interview search reference.
- [Designing Spontaneous Speech Search Interface for Historical Archives](https://arxiv.org/abs/1312.4706) - Faceted search and speech-archive interface design.

### RAG & QA

- [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k) - Open transcript sample for retrieval-grounded QA prototypes.
- [EHRI Online Editions](https://www.ehri-project.eu/ehri-online-editions/) - Curated edition context for citation-aware retrieval.
- [GND](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html) - Authority grounding for generated answers.

### ASR & Alignment

- [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org/csye/) - Audio, subtitles, and transcripts for Yiddish speech research.
- [BAS Web Services](https://clarin.phonetik.uni-muenchen.de/BASWebServices/interface/WebMAUSBasic) - Speech segmentation and alignment services.
- [Speech Technology Services for Oral History Research](https://arxiv.org/abs/2405.02333) - Practical overview of ASR services and workflows for oral history.
- [Human and Automatic Speech Recognition Performance on German Oral History Interviews](https://arxiv.org/abs/2201.06841) - Evaluation reference for German oral-history ASR.

### NER & Entity Linking

- [Placing the Holocaust](https://huggingface.co/placingholocaust) - Place taxonomy and Holocaust-oriented NER resources.
- [Placing Holocaust GLiNER Small](https://huggingface.co/placingholocaust/gliner_small-v2.1-holocaust) - Small place/entity extraction model.
- [GND](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html) - Authority-control target for persons, places, organizations, events, and topics.
- [GeoNames](https://www.geonames.org/) - Place-linking and geocoding baseline.

### Sentiment, Emotion & Topics

- [LLM4OralHistoryAnalysis](https://github.com/kc6699c/LLM4OralHistoryAnalysis) - Topic classification and sentiment analysis with LLMs on oral-history text.
- [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k) - Possible transcript source for careful exploratory sentiment or topic modeling.

### LLM Evaluation

- [LLM4OralHistoryAnalysis](https://github.com/kc6699c/LLM4OralHistoryAnalysis) - Prompting, RAG, and model comparison for oral-history understanding.
- [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k) - Small open transcript set for retrieval and hallucination tests.
- [Oral History in the Digital Age](https://ohda.matrix.msu.edu/) - Ethics and access context for responsible AI workflows.

## Browse by Language

### English

- [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k)
- [Placing the Holocaust](https://huggingface.co/placingholocaust)
- [Densho Digital Repository](https://ddr.densho.org/)
- [LLM4OralHistoryAnalysis](https://github.com/kc6699c/LLM4OralHistoryAnalysis)

### German

- [Oral-History.Digital](https://www.oral-history.digital/)
- [GND](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html)
- [Human and Automatic Speech Recognition Performance on German Oral History Interviews](https://arxiv.org/abs/2201.06841)

### Yiddish & Low-Resource

- [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org/csye/)

### Multilingual Resources

- [USC Shoah Foundation Visual History Archive](https://sfi.usc.edu/what-we-do/collections)
- [Fortunoff Video Archive on Aviary](https://fortunoff.aviaryplatform.com/)
- [EHRI Portal](https://portal.ehri-project.eu/)
- [GeoNames](https://www.geonames.org/)
- [ELSST](https://elsst.cessda.eu/)
- [CLARIN Virtual Language Observatory](https://vlo.clarin.eu/)

### Images, OCR & Documents

- [Arolsen Archives Online Search](https://arolsen-archives.org/en/archive/online-search/)
- [Densho Digital Repository](https://ddr.densho.org/)

### Text & Transcripts

- [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k)
- [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org/csye/)
- [Densho Digital Repository](https://ddr.densho.org/)

### Audio & ASR

- [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org/csye/)
- [BAS Web Services](https://clarin.phonetik.uni-muenchen.de/BASWebServices/interface/WebMAUSBasic)
- [Speech Technology Services for Oral History Research](https://arxiv.org/abs/2405.02333)

### Video & Multimodal

- [USC Shoah Foundation Visual History Archive](https://sfi.usc.edu/what-we-do/collections)
- [Fortunoff Video Archive on Aviary](https://fortunoff.aviaryplatform.com/)
- [USHMM Oral History Archive](https://www.ushmm.org/collections/the-museums-collections/about/oral-history)
- [Densho Digital Repository](https://ddr.densho.org/)

## Browse by Access

### Open Download

- 🟢 [Placing Holocaust Testimonies 1k](https://huggingface.co/datasets/placingholocaust/testimonies-1k)
- 🟢 [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org/csye/)
- 🟢 [Placing Holocaust GLiNER Small](https://huggingface.co/placingholocaust/gliner_small-v2.1-holocaust)
- 🟢 [LLM4OralHistoryAnalysis](https://github.com/kc6699c/LLM4OralHistoryAnalysis)
- 🟢 [GND](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html)
- 🟢 [GeoNames](https://www.geonames.org/)
- 🟢 [ELSST](https://elsst.cessda.eu/)
- 🟢 [OHMS Viewer](https://github.com/uklibraries/ohms-viewer)

### Public Web Access

- 🔵 [Densho Digital Repository](https://ddr.densho.org/)
- 🔵 [EHRI Portal](https://portal.ehri-project.eu/)
- 🔵 [EHRI Online Editions](https://www.ehri-project.eu/ehri-online-editions/)
- 🔵 [USHMM Oral History Archive](https://www.ushmm.org/collections/the-museums-collections/about/oral-history)
- 🔵 [Arolsen Archives Online Search](https://arolsen-archives.org/en/archive/online-search/)
- 🔵 [Oral History in the Digital Age](https://ohda.matrix.msu.edu/)

### Registration Required

- 🟠 [Fortunoff Video Archive on Aviary](https://fortunoff.aviaryplatform.com/)
- 🟠 [Oral-History.Digital](https://www.oral-history.digital/)

### Institutional / Restricted

- 🔴 [USC Shoah Foundation Visual History Archive](https://sfi.usc.edu/what-we-do/collections)
- 🔴 ⚫ [Fortunoff Video Archive on Aviary](https://fortunoff.aviaryplatform.com/)
- ⚫ [Aviary](https://www.aviaryplatform.com/)

## Needs Verification

These leads look relevant but should not be presented as open or reusable until public access, license, scope, and formats are confirmed.

| Resource / Lead | Why it matters | Needs verification |
| --- | --- | --- |
| EHRI-NER | Potential multilingual NER dataset for Holocaust-related texts. | Public URL, license, formats, and languages. |
| CORHOH | Potential text corpus of Holocaust oral histories. | Official URL, access terms, license, format, and scale. |
| MalachNER | Potential Holocaust testimony NER resource. | Public dataset location, license, and relationship to MALACH. |
| HoloBERT / Holocaust-domain models | Potential domain-adapted model family. | Model cards, training data documentation, license, and intended use. |
| Voci dall'Inferno | Potential TEI, semantic-search, and speech-phenomena project. | Public interface, downloadable data, terms, and formats. |
| UWebASR | Possible ASR/training corpus lead. | Public source, scope, language coverage, and license. |
| Yiddish / Hebrew Whisper training data | Relevant for low-resource ASR. | Dataset/model URL, source data, and reuse terms. |
| REYD corpus | Possible Yiddish speech transfer resource. | Official URL, access, license, and transcript availability. |
| The Shape of Testimony | Archive-comparison and segmentation research. | Public paper, code/data, archive permissions, and reuse terms. |
| Sentiment/emotion trajectory outputs | Relevant to narrative and affect modeling. | Public labels, outputs, corpus terms, and ethical constraints. |
| ASR4Memory | Oral-history ASR project/service lead. | Current official URL, status, models, datasets, and service terms. |
| CLARIN-IT speech phenomenon resources | Possible resources for pauses, gaps, and utterances. | Public records, download availability, license, and testimony relevance. |
| TheirStory | Oral-history workflow platform lead. | Current status, export formats, research fit, and terms. |

## Responsible Use

Holocaust testimonies and oral-history interviews can contain traumatic, biographical, personal, and legally sensitive content.

- Do not scrape restricted archives.
- Do not redistribute protected testimony data.
- Do not use restricted testimonies for model training without explicit permission.
- Respect archive terms of use and survivor, interviewee, family, and community expectations.
- Distinguish clearly between metadata access and full-content access.
- Avoid decontextualized extraction from testimony material.
- Document model limitations, hallucination risks, language bias, dialect limitations, and failure modes.
- Prefer synthetic examples, open resources, or metadata-only workflows for public demos.
- Use access-aware retrieval, auditability, transparency markers, and human-in-the-loop evaluation for sensitive collections.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before suggesting a new resource.

New resources should include a public URL, access status, license or terms, language coverage, modality, and purpose. Do not submit restricted data, scraped testimony content, or personal data. If access status is unclear, add the resource to [Needs Verification](#needs-verification) instead of the main list.

## License

This curated list is released under CC BY 4.0 unless otherwise stated. Each linked resource remains governed by its own license, access conditions, and terms of use.
