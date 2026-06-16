# Awesome Holocaust Testimony and Oral History AI Resources

> A curated list of datasets, archives, annotations, vocabularies, tools, and models for AI/NLP research on Holocaust testimonies and oral-history collections, organized by modality, language, purpose, and responsible-use status.

> Status: early curated draft. Some resources are verified; others are listed under "Needs Verification" until access, licensing, and scope are confirmed.

This is a human-curated awesome-list style collection of publicly findable resources relevant to Holocaust testimony, oral history, digital humanities, archives, cultural heritage, NLP, speech recognition, semantic search, retrieval-augmented generation, multimodal AI, and responsible AI.

The list is especially interested in resources useful for semantic search, RAG, automatic speech recognition, named entity recognition, entity linking, emotion and sentiment analysis, multilingual retrieval, access-aware retrieval, and responsible small-model evaluation.

This repository does not host, mirror, scrape, or redistribute testimony data. Each linked resource remains governed by its own license, access conditions, ethical restrictions, and terms of use.

## Contents

- [Scope](#scope)
- [How to Use This List](#how-to-use-this-list)
- [Access Legend](#access-legend)
- [Modality Legend](#modality-legend)
- [Browse by Language](#browse-by-language)
- [Browse by Purpose](#browse-by-purpose)
- [Browse by Access](#browse-by-access)
- [Browse by Modality](#browse-by-modality)
- [Curated Resources](#curated-resources)
- [Access-Limited Reference Collections](#access-limited-reference-collections)
- [Needs Verification](#needs-verification)
- [Relevance for KI.OH: Ask the Archivist and Semantic Search](#relevance-for-kioh-ask-the-archivist-and-semantic-search)
- [Dataset x Purpose Matrix](#dataset-x-purpose-matrix)
- [Responsible Use](#responsible-use)
- [Contributing](#contributing)
- [Suggested GitHub Topics](#suggested-github-topics)
- [License](#license)

## Scope

This list includes resources that are directly useful for AI/NLP research on Holocaust testimony and oral-history collections:

- Holocaust testimony resources and oral-history interview resources.
- Audiovisual narrative interviews, transcripts, subtitles, and aligned text.
- TEI/XML and other structured scholarly text resources.
- ASR, speech, audio, video, and multimodal resources.
- Scanned or digitized historical documents where OCR, layout analysis, or entity extraction are relevant.
- NER, entity-linking, sentiment, emotion, topic, narrative-trajectory, and thematic annotation resources.
- Controlled vocabularies, gazetteers, thesauri, authority files, and entity-linking targets.
- Semantic search, RAG, access-aware retrieval, evaluation, and small-model resources tied to these data types.

Out of scope:

- General Holocaust history resources without clear data, tool, archive, or AI/NLP relevance.
- Generic NLP datasets with no oral-history, testimony, archival, cultural-heritage, or sensitive-narrative relevance.
- Unverified datasets presented as open.
- Scraped testimony data, mirrors of protected content, or redistributed restricted materials.
- Resources with unclear provenance, unless they are explicitly placed under [Needs Verification](#needs-verification).

## How to Use This List

The list can be browsed in four ways:

1. By language.
2. By purpose or task.
3. By access level.
4. By modality.

Because this is pure GitHub Markdown, browsing is implemented through manually curated anchor-link indexes. Each resource has one canonical entry in [Curated Resources](#curated-resources), and browse sections link back to those canonical entries.

## Access Legend

| Label | Meaning |
| --- | --- |
| 🟢 Open download | Dataset or resource can be downloaded directly under stated terms. |
| 🔵 Public web access | Resource can be searched or viewed online, but bulk download may not be available. |
| 🟡 Metadata only | Public metadata, catalog records, dashboards, or descriptions are available, but not full content. |
| 🟠 Registration required | Access requires a free account, registration, or request. |
| 🔴 Institutional access | Access requires a subscribing institution, reading room, or approved access site. |
| ⚫ Licensed/restricted | Use requires explicit permission, a data agreement, or special license. |
| ❓ Needs verification | Public availability, license, or scope is not yet confirmed. |

## Modality Legend

| Label | Meaning |
| --- | --- |
| Text / Transcripts | Plain text, transcript segments, interviews, answers, or testimony text. |
| TEI / XML | Structured text encoded as TEI, XML, or similar scholarly formats. |
| Audio | Speech recordings or audio-derived resources. |
| Video | Video testimony or video-derived material. |
| Multimodal | Resources combining text, audio, video, images, gestures, facial expression, or paraverbal cues. |
| Images / Scans | Scanned documents, images, or OCR-relevant historical material. |
| Metadata / Catalog | Catalog records, collection descriptions, indexes, dashboards, or archival metadata. |
| Annotations | NER, sentiment, emotion, topic, narrative, or other labeled data. |
| Vocabularies / Authority Data | Controlled vocabularies, gazetteers, thesauri, authority records, or entity-linking targets. |
| Models / Tools | Software or machine-learning models directly relevant to the resources and tasks. |

## Browse by Language

### English

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - English testimony transcripts in HTML-like form.
- [Placing the Holocaust](#placing-the-holocaust) - English testimony-derived place taxonomy, models, and datasets.
- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) - English-oriented Holocaust place NER model.

### German

- [Oral-History.Digital](#oral-historydigital) - German platform for narrative audiovisual interview collections.
- [GND](#gnd) - German authority data useful for entity linking.
- [ELSST](#elsst) - multilingual social-science thesaurus including German.

### Yiddish

- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - Yiddish survivor interviews with aligned transcripts and downloadable audio/transcript formats.

### Hebrew

- No verified resource yet. Relevant leads should remain under [Needs Verification](#needs-verification) until public documentation confirms language coverage, access, and terms.

### Polish

- No verified resource yet. Relevant leads should remain under [Needs Verification](#needs-verification) until public documentation confirms language coverage, access, and terms.

### Czech

- [ELSST](#elsst) - multilingual social-science thesaurus including Czech.

### Dutch

- [ELSST](#elsst) - multilingual social-science thesaurus including Dutch.

### Italian

- No verified resource yet. Relevant leads should remain under [Needs Verification](#needs-verification) until public documentation confirms language coverage, access, and terms.

### Multilingual

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - video testimony archive across many countries and languages.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - testimonies recorded in witnesses' preferred languages.
- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - Yiddish with transliteration and metadata.
- [EHRI Portal](#ehri-portal) - Holocaust archival discovery across institutions and countries.
- [GND](#gnd) - authority records useful across multilingual metadata workflows.
- [GeoNames](#geonames) - global place names for geocoding and place linking.
- [ELSST](#elsst) - multilingual thesaurus for social-science data discovery.

### Language coverage unclear

- [Arolsen Archives Online Search](#arolsen-archives-online-search) - interface is multilingual; item-level document languages vary.
- [OHMS Viewer](#ohms-viewer) - tool language depends on the implementing collection and transcript files.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - multilingual archive; use item-level metadata for specific language claims.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - multilingual collection; use item-level metadata for specific language claims.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - multilingual collection; use item-level metadata for specific language claims.

## Browse by Purpose

### Semantic Search and Retrieval

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - transcript text suitable for segment retrieval experiments under its stated terms.
- [EHRI Portal](#ehri-portal) - archival discovery and entity-rich metadata.
- [Oral-History.Digital](#oral-historydigital) - platform model for cross-collection interview search.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - public catalog and interview search reference.

### Retrieval-Augmented Generation

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - open transcript sample for RAG prototyping.
- [Placing the Holocaust](#placing-the-holocaust) - place-focused datasets and models for grounded retrieval.
- [EHRI Portal](#ehri-portal) - metadata and archival descriptions for provenance-aware retrieval.
- [GND](#gnd) - authority identifiers for grounding generated answers.

### Ask-the-Archivist / Research Assistant Design

- [EHRI Portal](#ehri-portal) - model for archive discovery across dispersed holdings.
- [Oral-History.Digital](#oral-historydigital) - interview portal and research-environment reference.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - reference for catalog search and restricted/public access distinctions.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - reference for request-based access workflows.

### Automatic Speech Recognition

- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - Yiddish audio and time-aligned transcripts.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - important access-limited ASR evaluation context.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - large access-controlled audiovisual reference collection.

### Speech Disfluency, Pauses, and Paraverbal Cues

- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - aligned speech and transcript material for spoken-language analysis.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - long-form testimony reference for speech phenomena.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - multimodal testimony reference collection.

### Named Entity Recognition

- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) - fine-tuned Holocaust place NER model.
- [Placing the Holocaust](#placing-the-holocaust) - taxonomy, models, and datasets for place-based testimony analysis.
- [GND](#gnd) - authority data for person, corporate body, event, geographic, topic, and work entities.

### Entity Linking and Authority Control

- [GND](#gnd) - stable authority identifiers and downloadable metadata.
- [GeoNames](#geonames) - global place-name database and downloadable gazetteer data.
- [ELSST](#elsst) - multilingual subject vocabulary for thematic indexing.
- [EHRI Portal](#ehri-portal) - archival metadata and linked discovery context.

### Multilingual and Cross-Lingual Retrieval

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - multilingual archive for access-aware reference design.
- [EHRI Portal](#ehri-portal) - cross-institutional Holocaust archive discovery.
- [ELSST](#elsst) - multilingual thesaurus for cross-lingual data discovery.
- [GeoNames](#geonames) - multilingual place-name lookup and geocoding.

### Yiddish and Low-Resource Language Processing

- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - primary Yiddish oral-history speech and transcript resource.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - access-controlled reference collection for multilingual testimony.

### Sentiment, Emotion, and Narrative Trajectories

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - transcript data that may support careful exploratory sentiment or trajectory analysis.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - multimodal reference collection; access restrictions apply.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - long-form testimony collection; access restrictions apply.

### Topic Modeling and Thematic Indexing

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - long-form transcript text for topic modeling experiments.
- [ELSST](#elsst) - controlled vocabulary for social-science subject indexing.
- [EHRI Portal](#ehri-portal) - archival metadata discovery and thematic context.

### OCR and Historical Scanned Documents

- [Arolsen Archives Online Search](#arolsen-archives-online-search) - digitized archival records and online search reference.

### Video and Multimodal Analysis

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - large video testimony archive.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - video testimony archive with request/location-based access.
- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - video-sourced interviews with audio and transcripts.

### Metadata, Catalog Search, and Archive Discovery

- [EHRI Portal](#ehri-portal) - Holocaust archival discovery portal.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - public catalog for oral histories.
- [Oral-History.Digital](#oral-historydigital) - cross-collection interview portal and research environment.
- [Arolsen Archives Online Search](#arolsen-archives-online-search) - public online archive search.

### Access-Control-Aware Search

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - access-site and archive-access distinctions.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - registration, request, and location-aware access.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - many interviews online, some restricted to reading rooms.
- [Oral-History.Digital](#oral-historydigital) - platform model for registered research environments.

### Small-Model Evaluation

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - compact open transcript benchmark candidate.
- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) - small NER model for domain comparison.
- [GND](#gnd) - authority data for small-model entity-linking experiments.
- [GeoNames](#geonames) - gazetteer baseline for place-linking tests.

### Responsible AI, Bias, and Hallucination Testing

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - sensitive testimony-derived text for careful RAG failure-mode testing under source terms.
- [EHRI Portal](#ehri-portal) - provenance-rich archival metadata for grounded answers.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - access-controlled collection for ethical workflow design, not unrestricted training.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - licensed/restricted reference collection for responsible access patterns.

## Browse by Access

### 🟢 Open Download

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - Hugging Face dataset with Apache-2.0 license and downloadable Parquet.
- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) - Hugging Face model with MIT license.
- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - downloadable audio and transcripts under CSYE terms.
- [GND](#gnd) - authority data available in multiple formats under CC0.
- [GeoNames](#geonames) - free gazetteer downloads under CC BY 4.0.
- [ELSST](#elsst) - multilingual thesaurus under CC BY-SA 4.0.

### 🔵 Public Web Access

- [Placing the Holocaust](#placing-the-holocaust) - public Hugging Face organization with datasets and models.
- [EHRI Portal](#ehri-portal) - searchable public portal for Holocaust-related archival material.
- [EHRI Online Editions](#ehri-online-editions) - public digital editions.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - public catalog/search; full availability varies by interview.
- [Arolsen Archives Online Search](#arolsen-archives-online-search) - public online archive search interface.
- [Oral-History.Digital](#oral-historydigital) - public portal information and interview portal.

### 🟡 Metadata Only

- [EHRI Portal](#ehri-portal) - often points to external holdings rather than providing full content.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - public collection information; full access depends on site/account conditions.
- [Oral-History.Digital](#oral-historydigital) - public discovery and platform information; collection-level access varies.

### 🟠 Registration Required

- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - account, access request, and approval required for viewing.
- [Oral-History.Digital](#oral-historydigital) - registered users can use research-environment functions where enabled.

### 🔴 Institutional Access

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - full archive access is tied to access sites and institutional arrangements.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - non-Yale access requires physical presence at an access site or access-site VPN/EZproxy.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - some restricted interviews require reading room access.

### ⚫ Licensed or Restricted

- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - reuse in publications and media requires licensing.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - use is governed by USC Shoah Foundation access and permission terms.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - collection-specific terms and restrictions apply.

### ❓ Needs Verification

- [Needs Verification](#needs-verification) - leads with unclear public access, license, format, or scope.

## Browse by Modality

### Text / Transcripts

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - HTML-like transcript text.
- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - time-aligned Yiddish transcripts and transliteration.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - interview catalog and online viewing for many items.

### TEI / XML

- [EHRI Online Editions](#ehri-online-editions) - digital edition context; encoding details should be checked per edition.
- [OHMS Viewer](#ohms-viewer) - uses exported interview XML/cache files for synchronized transcript viewing.

### Audio

- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - downloadable audio.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - audiovisual testimony collection.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - video testimony archive with audio.

### Video

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - video testimonies.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - video testimonies.
- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - video-sourced testimony interviews.

### Multimodal

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - audiovisual testimony with rich indexing.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - long-form audiovisual testimony.
- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - audio, transcripts, subtitles, and metadata.

### Images / Scanned Documents

- [Arolsen Archives Online Search](#arolsen-archives-online-search) - digitized archival documents.

### Metadata / Catalog Records

- [EHRI Portal](#ehri-portal) - archival metadata and collection descriptions.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - oral-history catalog search.
- [Arolsen Archives Online Search](#arolsen-archives-online-search) - people/topic/archive-tree search.
- [Oral-History.Digital](#oral-historydigital) - cross-collection interview discovery.

### Named Entity Annotations

- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) - Holocaust place NER model.
- [Placing the Holocaust](#placing-the-holocaust) - place-taxonomy resources and related NER datasets/models.

### Sentiment / Emotion Annotations

- [Needs Verification](#needs-verification) - current candidate outputs and papers need public URL, license, and data availability checks.

### Vocabularies / Authority Data

- [GND](#gnd) - authority data for cultural and academic collections.
- [GeoNames](#geonames) - global placename gazetteer.
- [ELSST](#elsst) - multilingual social-science thesaurus.

### Models / Tools

- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) - fine-tuned GLiNER model.
- [OHMS Viewer](#ohms-viewer) - open-source viewer for synchronized oral-history transcript/index presentation.
- [Oral-History.Digital](#oral-historydigital) - platform reference for oral-history processing and research workflows.

## Curated Resources

### Text and Transcript Corpora

#### Placing Holocaust Testimonies 1k

- **URL:** [Hugging Face dataset](https://huggingface.co/datasets/placingholocaust/testimonies-1k)
- **Modality:** Text / Transcripts
- **Languages:** English
- **Scale:** 949 rows
- **Format:** Parquet; HTML-like testimony text
- **Access:** 🟢 Open download
- **License / terms:** Apache-2.0 on Hugging Face; verify source collection constraints before reuse.
- **Relevant purposes:** Semantic search; RAG; long-document QA; topic modeling; summarization; responsible AI testing.
- **KI.OH / small-model use:** Useful as a compact transcript set for segment retrieval, query rewriting, reranking, and hallucination tests.
- **Notes:** Dataset card says the testimonies are from the United States Holocaust Memorial Museum and are in a temporary HTML format.

#### Corpus of Spoken Yiddish in Europe

- **URL:** [Official site](https://www.yiddishcorpus.org/csye/)
- **Modality:** Audio; Video; Text / Transcripts; Multimodal
- **Languages:** Yiddish; transliteration; metadata language coverage varies
- **Scale:** Hundreds of video-recorded survivor interviews, with the corpus still expanding
- **Format:** Video with subtitles; downloadable audio; transcripts in multiple formats
- **Access:** 🟢 Open download
- **License / terms:** Free of charge under CSYE Terms of Use.
- **Relevant purposes:** Yiddish ASR; forced alignment; orthographic comparison; dialect variation; code-switching; low-resource NLP.
- **KI.OH / small-model use:** Strong candidate for speech and transcript alignment tests in a low-resource testimony setting.
- **Notes:** CSYE is sourced from Holocaust survivor testimonies and explicitly supports linguistic research, instruction, and commemoration.

### TEI/XML and Structured Testimony Data

#### EHRI Online Editions

- **URL:** [Official page](https://www.ehri-project.eu/ehri-online-editions/)
- **Modality:** Text / Transcripts; Metadata / Catalog
- **Languages:** Multilingual; edition-specific
- **Scale:** Multiple published online editions
- **Format:** Digital editions; edition-specific formats
- **Access:** 🔵 Public web access
- **License / terms:** See source terms for each edition.
- **Relevant purposes:** Digital editions; annotation; archival context; structured publication; RAG grounding.
- **KI.OH / small-model use:** Useful for testing citation-aware retrieval over curated editions rather than raw testimony data.
- **Notes:** Encoding and download options should be checked edition by edition.

#### OHMS Viewer

- **URL:** [GitHub repository](https://github.com/uklibraries/ohms-viewer)
- **Modality:** TEI / XML; Text / Transcripts; Audio; Video; Models / Tools
- **Languages:** Collection-dependent
- **Scale:** Tool, not a dataset
- **Format:** PHP viewer for OHMS-exported interview files
- **Access:** 🟢 Open download
- **License / terms:** GPL-3.0 for the viewer repository.
- **Relevant purposes:** Synchronized transcripts; oral-history access workflows; transcript/index search; timecoded navigation.
- **KI.OH / small-model use:** Useful as a reference pattern for linking retrieval hits to timecoded interview moments.
- **Notes:** The public OHMS website may block automated access, but the viewer source is public on GitHub.

### NER and Entity Linking Resources

#### Placing the Holocaust

- **URL:** [Hugging Face organization](https://huggingface.co/placingholocaust)
- **Modality:** Text / Transcripts; Annotations; Models / Tools
- **Languages:** English; others unknown
- **Scale:** Organization lists several datasets and models; scale varies by resource
- **Format:** Hugging Face datasets and models
- **Access:** 🔵 Public web access
- **License / terms:** See individual dataset and model cards.
- **Relevant purposes:** Place-based NER; spatial concepts; semantic search; entity-aware retrieval; Holocaust landscape analysis.
- **KI.OH / small-model use:** Useful for comparing place-aware NER and query expansion over testimony transcripts.
- **Notes:** The project defines a place taxonomy for named and unnamed places in survivor testimony.

#### Placing Holocaust GLiNER Small

- **URL:** [Hugging Face model](https://huggingface.co/placingholocaust/gliner_small-v2.1-holocaust)
- **Modality:** Models / Tools; Annotations
- **Languages:** English; model behavior in other languages unknown
- **Scale:** Fine-tuned model; training data linked from the model card
- **Format:** PyTorch / GLiNER model
- **Access:** 🟢 Open download
- **License / terms:** MIT on Hugging Face.
- **Relevant purposes:** Named entity recognition; place extraction; small-model evaluation; domain adaptation.
- **KI.OH / small-model use:** Direct candidate for baseline NER tests against historical, biographical, and testimony-derived language.
- **Notes:** Model card lists place-oriented labels such as populated place, country, region, building, and environmental feature.

### Audio, ASR, and Speech Resources

#### USC Shoah Foundation Visual History Archive

- **URL:** [Official collections page](https://sfi.usc.edu/what-we-do/collections)
- **Modality:** Video; Audio; Metadata / Catalog; Multimodal
- **Languages:** Multilingual
- **Scale:** 60,000+ video testimonies; public page lists 45 languages and 204 access sites
- **Format:** Video testimonies; searchable archive; metadata and indexing
- **Access:** 🔴 Institutional access
- **License / terms:** Governed by USC Shoah Foundation access and permission terms.
- **Relevant purposes:** Multimodal research; archive discovery; access-control-aware retrieval; ASR reference; multilingual search.
- **KI.OH / small-model use:** Important reference collection for designing access-aware workflows and evaluation protocols without redistributing protected content.
- **Notes:** Treat as a reference and access-controlled archive, not as an open dataset.

#### Fortunoff Video Archive on Aviary

- **URL:** [Aviary portal](https://fortunoff.aviaryplatform.com/)
- **Modality:** Video; Audio; Metadata / Catalog; Multimodal
- **Languages:** Multilingual; witnesses recorded in preferred languages
- **Scale:** More than 4,400 testimonies and over 12,000 recorded hours
- **Format:** Video testimony portal; metadata; access requests
- **Access:** 🟠 Registration required; 🔴 Institutional access; ⚫ Licensed/restricted for reuse
- **License / terms:** Viewing and reuse governed by Fortunoff/Yale and Aviary terms; licensing required for publication or media reuse.
- **Relevant purposes:** ASR evaluation context; access-aware retrieval; interview-style comparison; multimodal analysis.
- **KI.OH / small-model use:** Useful for designing request-based access models and evaluating how retrieval systems should handle restricted testimony.
- **Notes:** Non-Yale researchers must register, request access, and be at an access site or access-site VPN/EZproxy.

### Video and Multimodal Resources

#### USHMM Oral History Archive

- **URL:** [Official page](https://www.ushmm.org/collections/the-museums-collections/about/oral-history)
- **Modality:** Video; Audio; Text / Transcripts; Metadata / Catalog
- **Languages:** Multilingual; item-specific
- **Scale:** Tens of thousands of interviews
- **Format:** Public catalog/search; online viewing for many interviews; some reading-room-only access
- **Access:** 🔵 Public web access; 🔴 Institutional access for restricted items
- **License / terms:** See USHMM collection terms and item records.
- **Relevant purposes:** Archive discovery; metadata search; oral-history reference; access-aware retrieval.
- **KI.OH / small-model use:** Useful for modeling distinctions between public catalog visibility, online viewability, and reading-room restrictions.
- **Notes:** USHMM states most interviews can be viewed online, while some are restricted to museum reading rooms.

### Sentiment, Emotion, and Narrative-Trajectory Resources

No sentiment, emotion, or narrative-trajectory dataset has been moved into the verified main list yet. Candidate papers and outputs are tracked under [Needs Verification](#needs-verification) until public data, licenses, formats, and reuse terms are confirmed.

### Metadata, Catalogs, and Archive Discovery

#### EHRI Portal

- **URL:** [Official portal](https://portal.ehri-project.eu/)
- **Modality:** Metadata / Catalog; Vocabularies / Authority Data
- **Languages:** Multilingual; archive-specific
- **Scale:** Cross-institutional Holocaust archival discovery portal
- **Format:** Archival descriptions; collection records; research guides; entity-rich metadata
- **Access:** 🔵 Public web access; 🟡 Metadata only for many holdings
- **License / terms:** See EHRI and source archive terms.
- **Relevant purposes:** Archive discovery; entity-aware search; metadata search; RAG grounding; multilingual retrieval.
- **KI.OH / small-model use:** Useful for testing retrieval over archival metadata and grounding answers in collection-level provenance.
- **Notes:** EHRI is a discovery infrastructure; linked holding institutions may control access to full materials.

#### Oral-History.Digital

- **URL:** [Official site](https://www.oral-history.digital/)
- **Modality:** Metadata / Catalog; Audio; Video; Text / Transcripts; Models / Tools
- **Languages:** German; collection-specific
- **Scale:** Platform and portal for multiple audiovisual narrative interview collections
- **Format:** Interview portal; indexing platform; research environment
- **Access:** 🔵 Public web access; 🟠 Registration required for some research functions; collection-specific restrictions
- **License / terms:** See platform and collection-specific terms.
- **Relevant purposes:** Oral-history infrastructure; metadata/search; access models; transcription and indexing workflows.
- **KI.OH / small-model use:** Useful reference for designing community-facing search and research-assistant workflows around sensitive interviews.
- **Notes:** Public documentation describes it as an interview portal, indexing platform, and research environment.

#### Arolsen Archives Online Search

- **URL:** [Official online search](https://arolsen-archives.org/en/archive/online-search/)
- **Modality:** Images / Scans; Metadata / Catalog; Text / Transcripts
- **Languages:** Multilingual interface; item languages vary
- **Scale:** Large online archive of Nazi persecution records; exact online item counts should be checked at source
- **Format:** Digitized documents; people records; topic search; archive tree
- **Access:** 🔵 Public web access
- **License / terms:** See Arolsen Archives terms of use.
- **Relevant purposes:** OCR; document search; entity extraction; archival metadata; historical place/person linking.
- **KI.OH / small-model use:** Useful for testing metadata search and OCR-aware retrieval over digitized historical documents.
- **Notes:** This is not an oral-history dataset, but it is relevant for archival context, OCR, and entity-linking workflows.

### Vocabularies and Authority Data

#### GND

- **URL:** [German National Library page](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html)
- **Modality:** Vocabularies / Authority Data
- **Languages:** German-centered; usable in multilingual linking workflows
- **Scale:** Large authority file; exact current record count should be checked at source
- **Format:** MARC 21; MARC21-XML; RDF/XML; JSON-LD; Turtle; SRU; OAI
- **Access:** 🟢 Open download
- **License / terms:** CC0 1.0
- **Relevant purposes:** Entity linking; authority control; query expansion; person/place/organization disambiguation.
- **KI.OH / small-model use:** Strong candidate for evaluating entity-aware retrieval and authority-grounded answer generation.
- **Notes:** Particularly useful for cultural, academic, library, archive, and museum collections.

#### GeoNames

- **URL:** [Official site](https://www.geonames.org/)
- **Modality:** Vocabularies / Authority Data
- **Languages:** Multilingual place names
- **Scale:** More than eleven million placenames
- **Format:** Search interface; web services; downloadable gazetteer data
- **Access:** 🟢 Open download
- **License / terms:** CC BY 4.0
- **Relevant purposes:** Place linking; geocoding; query expansion; map interfaces; spatial retrieval.
- **KI.OH / small-model use:** Useful baseline for place normalization, while testing failures around historical names and spelling variants.
- **Notes:** Historical place names, camp/ghetto names, and testimony-specific spatial references may require domain-specific augmentation.

#### ELSST

- **URL:** [Official site](https://elsst.cessda.eu/)
- **Modality:** Vocabularies / Authority Data
- **Languages:** Czech; Dutch; English; Finnish; French; German; Greek; Hungarian; Icelandic; Lithuanian; Norwegian; Romanian; Slovenian; Spanish; Swedish
- **Scale:** Over 3,400 concepts
- **Format:** Multilingual thesaurus / concept scheme
- **Access:** 🟢 Open download
- **License / terms:** CC BY-SA 4.0
- **Relevant purposes:** Thematic indexing; multilingual retrieval; social-science metadata; query expansion.
- **KI.OH / small-model use:** Useful for testing controlled-vocabulary expansion and multilingual subject search.
- **Notes:** Broad social-science vocabulary, not Holocaust-specific.

### Tools and Models

Tool and model entries are distributed above where they are most relevant:

- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small)
- [OHMS Viewer](#ohms-viewer)
- [Oral-History.Digital](#oral-historydigital)

## Access-Limited Reference Collections

### USC Shoah Foundation Visual History Archive Access Notes

Publicly visible: collection description, summary statistics, access-site information, and public-facing Visual History Archive entry point.

Access-limited: full archive access depends on institutional access sites, archive accounts, and USC Shoah Foundation terms.

Research value: a major multilingual, multimodal testimony reference collection for understanding search, indexing, access control, metadata, ASR needs, and responsible-use constraints.

Evaluation use: useful for designing protocols, metadata-only workflows, synthetic access labels, and access-aware retrieval without downloading or redistributing protected testimony.

### Fortunoff Video Archive on Aviary Access Notes

Publicly visible: collection overview, search interface, and access workflow details.

Access-limited: viewing requires registration, request approval, and in many cases an access site or Yale-related access path.

Research value: long-form Holocaust testimony collection with varied languages and interview styles.

Evaluation use: useful for modeling registration, request, license, and location-sensitive access flows.

### USHMM Oral History Archive Access Notes

Publicly visible: oral-history collection description and catalog/search access.

Access-limited: many interviews are viewable online, but some are restricted to museum reading rooms.

Research value: large and diverse oral-history archive for metadata search, cataloging, access classification, and collection comparison.

Evaluation use: useful for public-vs-restricted access classification and metadata-first retrieval design.

### Oral-History.Digital Collections

Publicly visible: platform information and interview portal entry point.

Access-limited: access depends on collection-level publication, registration, and research-environment permissions.

Research value: reference infrastructure for audiovisual narrative interview collections, transcription, indexing, and research workflows.

Evaluation use: useful for studying platform-level design patterns for sensitive oral-history search and analysis.

## Needs Verification

| Resource / Lead | Why it matters | What needs verification |
| --- | --- | --- |
| EHRI-NER | Potential multilingual NER dataset for Holocaust-related texts. | Public URL, dataset card or paper, license, formats, languages, and access. |
| CORHOH | Potential text corpus of Holocaust oral histories for semantic search, RAG, topic modeling, and sentiment analysis. | Official public URL, access terms, license, format, scale, and whether redistribution is allowed. |
| MalachNER dataset | Potential NER dataset for Holocaust testimony text. | Public URL, license, formats, access, and relationship to MALACH resources. |
| HoloBERT or Holocaust-domain language models | Potential domain-adapted model family for testimony or Holocaust-related language. | Model page, training data documentation, license, intended use, and evaluation data. |
| Voci dall'Inferno project data/interface | Potential TEI, semantic-search, and speech-phenomena project. | Public interface, data availability, license, TEI access, and reuse terms. |
| placingholocaust/ushmm-pdfs | Potential PDF/document dataset for OCR and document retrieval experiments. | Dataset card, license, source terms, document provenance, and reuse permissions. |
| UWebASR data collection | Possible ASR/training corpus lead. | Public source, scope, languages, access, license, and whether data are testimony-derived. |
| Fortunoff ASR evaluation data or transcripts | Important ASR benchmark context. | Whether any transcripts or ASR evaluation outputs are public, licensed, or restricted. |
| Yiddish Whisper training data | Important for Yiddish ASR and orthographic comparison. | Public dataset/model URL, training sources, license, and relationship to protected testimony. |
| Hebrew Whisper training data | Important for Hebrew ASR and multilingual testimony workflows. | Public dataset/model URL, training sources, license, and intended use. |
| REYD corpus of audiobooks | Potential Yiddish speech resource. | Official URL, access, license, audio/transcript formats, and relevance to testimony ASR transfer. |
| The Shape of Testimony resources | Potential archive-comparison framework and segmentation resources. | Public paper, code/data availability, archive permissions, and reuse terms. |
| Emotion/sentiment trajectory paper resources | Potential sentiment, emotion, and narrative-trajectory outputs. | Public data, labels, code, model outputs, licenses, and consent/access constraints. |
| ABC-stratified sentiment outputs or labels | Potential sentiment stability resource for Holocaust oral histories. | Whether outputs are public, what corpus underlies them, and whether redistribution is allowed. |
| ASR4Memory | Potential oral-history ASR project/service reference. | Official current URL, project status, models, datasets, service terms, and access conditions. |
| CLARIN VLO records | Discovery route for relevant language resources. | Specific records, persistent IDs, licenses, and whether resources are oral-history/testimony-specific. |
| CLARIN-IT speech phenomenon portal resources | Potential resource for pauses, gaps, utterances, and speech phenomena. | Public interface, downloadable data, formats, license, and testimony relevance. |
| TheirStory | Possible oral-history workflow platform. | Current product/project status, terms, export formats, research relevance, and data handling. |

## Relevance for KI.OH: Ask the Archivist and Semantic Search

This list can support KI.OH-style planning for sensitive, heterogeneous, multilingual, and access-restricted oral-history collections. The most relevant themes are semantic search, RAG, access-aware retrieval, small-model testing, multilingual retrieval, ASR evaluation, and responsible AI evaluation.

### Candidate resources for semantic search prototypes

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - segment retrieval and long-form transcript search.
- [EHRI Portal](#ehri-portal) - archival metadata retrieval and source grounding.
- [Oral-History.Digital](#oral-historydigital) - cross-collection interview search reference.

### Candidate resources for multilingual retrieval

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - access-controlled multilingual reference collection.
- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - Yiddish speech/transcript resource.
- [ELSST](#elsst) - multilingual thesaurus for query expansion and subject indexing.

### Candidate resources for entity-aware search

- [Placing the Holocaust](#placing-the-holocaust) - place taxonomy and Holocaust-oriented NER resources.
- [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) - NER baseline model.
- [GND](#gnd) - authority identifiers.
- [GeoNames](#geonames) - place-name linking.

### Candidate resources for ASR and transcription evaluation

- [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) - Yiddish audio and aligned transcripts.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - access-limited reference for ASR challenges.
- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - large multilingual audiovisual reference.

### Candidate resources for small-model experiments

- Compare multilingual embedding models over transcript segments.
- Test BM25 plus vector hybrid retrieval.
- Test small LLMs for query rewriting.
- Test small LLMs for reranking retrieved passages.
- Test small LLMs for answer critique.
- Test entity-aware query expansion using authority files.
- Test NER on historical, multilingual, and biographical interview text.
- Test summarization of long interview transcripts or segments.
- Test hallucination behavior when the retrieved context is insufficient.
- Test refusal and guardrail behavior for sensitive questions.
- Test access-control filtering using metadata-only or synthetic access labels.
- Test language and dialect robustness, especially for Yiddish, German, English, Polish, Czech, Dutch, Hebrew, Italian, Slavic languages, and multilingual testimony contexts.

### Candidate resources for access-control-aware retrieval

- [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) - access-site and permission-aware design reference.
- [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) - request and location-sensitive access workflow.
- [USHMM Oral History Archive](#ushmm-oral-history-archive) - public online vs reading-room-only distinctions.
- [Oral-History.Digital](#oral-historydigital) - research-environment and collection-level access reference.

### Candidate resources for responsible AI and hallucination testing

- [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) - open transcript data for carefully scoped RAG and hallucination tests.
- [EHRI Portal](#ehri-portal) - provenance-rich metadata for grounding.
- [GND](#gnd) and [GeoNames](#geonames) - authority-based checks for entity claims.
- [Access-Limited Reference Collections](#access-limited-reference-collections) - access patterns to emulate without exposing protected data.

## Dataset x Purpose Matrix

| Symbol | Meaning |
| --- | --- |
| ✅ | Suitable |
| ⚠️ | Possible with constraints |
| ❌ | Not suitable / not available |
| ? | Unknown / needs verification |

| Resource | ASR | NER | Entity Linking | Semantic Search | RAG | Summarization | Sentiment / Emotion | Multimodal | Metadata Search | Access-Control Testing | Small-Model Evaluation |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| [Placing Holocaust Testimonies 1k](#placing-holocaust-testimonies-1k) | ❌ | ⚠️ | ⚠️ | ✅ | ✅ | ✅ | ⚠️ | ❌ | ⚠️ | ⚠️ | ✅ |
| [Corpus of Spoken Yiddish in Europe](#corpus-of-spoken-yiddish-in-europe) | ✅ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ✅ | ✅ | ⚠️ | ✅ |
| [Placing Holocaust GLiNER Small](#placing-holocaust-gliner-small) | ❌ | ✅ | ⚠️ | ⚠️ | ⚠️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| [USC Shoah Foundation Visual History Archive](#usc-shoah-foundation-visual-history-archive) | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ✅ | ✅ | ✅ | ⚠️ |
| [Fortunoff Video Archive on Aviary](#fortunoff-video-archive-on-aviary) | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ⚠️ | ✅ | ✅ | ✅ | ⚠️ |
| [USHMM Oral History Archive](#ushmm-oral-history-archive) | ⚠️ | ⚠️ | ⚠️ | ✅ | ⚠️ | ⚠️ | ⚠️ | ✅ | ✅ | ✅ | ⚠️ |
| [EHRI Portal](#ehri-portal) | ❌ | ⚠️ | ✅ | ✅ | ✅ | ⚠️ | ❌ | ❌ | ✅ | ⚠️ | ✅ |
| [Oral-History.Digital](#oral-historydigital) | ⚠️ | ⚠️ | ⚠️ | ✅ | ⚠️ | ⚠️ | ⚠️ | ✅ | ✅ | ✅ | ⚠️ |
| [Arolsen Archives Online Search](#arolsen-archives-online-search) | ❌ | ⚠️ | ✅ | ✅ | ⚠️ | ⚠️ | ❌ | ⚠️ | ✅ | ⚠️ | ⚠️ |
| [GND](#gnd) | ❌ | ❌ | ✅ | ⚠️ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ | ✅ |
| [GeoNames](#geonames) | ❌ | ❌ | ✅ | ⚠️ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ | ✅ |
| [ELSST](#elsst) | ❌ | ❌ | ⚠️ | ✅ | ⚠️ | ❌ | ❌ | ❌ | ✅ | ❌ | ✅ |

## Responsible Use

Holocaust testimonies and oral-history interviews can contain traumatic, biographical, personal, and legally sensitive content.

- Do not scrape restricted archives.
- Do not redistribute protected testimony data.
- Do not use restricted testimonies for model training without explicit permission.
- Respect archive terms of use and survivor, interviewee, family, and community expectations.
- Distinguish clearly between metadata access and full-content access.
- Avoid decontextualized extraction from testimony material.
- Document model limitations, hallucination risks, language bias, dialect limitations, and failure modes.
- Use synthetic examples, open resources, or metadata-only workflows for public demos when possible.
- For KI.OH-like workflows, prefer access-aware retrieval, auditability, transparency markers, and human-in-the-loop evaluation.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before suggesting a new resource.

New resources should include a public URL, access status, license or terms, language coverage, modality, and purpose. Do not submit restricted data, scraped testimony content, or personal data. If access status is unclear, add the resource to [Needs Verification](#needs-verification) instead of the main list.

TODO: Run `awesome-lint` later if the maintainer wants closer alignment with central Awesome conventions.

## Suggested GitHub Topics

```text
awesome
awesome-list
oral-history
holocaust-testimonies
digital-humanities
language-resources
datasets
nlp
semantic-search
rag
asr
named-entity-recognition
entity-linking
multimodal-ai
speech-recognition
archival-data
responsible-ai
fair-data
cultural-heritage
testimony
```

## License

This curated list is released under CC BY 4.0 unless otherwise stated. Each linked resource remains governed by its own license, access conditions, and terms of use.
