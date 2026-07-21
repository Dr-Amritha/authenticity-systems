# Authenticity Lens — Structured Provenance Inventory Template

**Version:** 0.1 (GTC Prototype Draft)
**Framework:** Authenticity Lens, Smart Story Labs
**Developed by:** Dr Amritha Subhayan Krishnan
**License:** CC BY 4.0

---

## How to Use This Template

This template guides you through a structured three-layer assessment of a piece of media content. Work through each layer in sequence. Each layer builds on the previous one. At the end you will have a completed provenance inventory — a reasoned, interpretable authenticity assessment that you can share, contest, and act upon.

**What you need before starting:**
- The media content you are assessing (video, image, audio, or text)
- Access to the tools listed in Layer 1 (all free and open access)
- Approximately 20–30 minutes for a thorough assessment

**Scoring guide:**
- **0** — No concern identified
- **1** — Minor concern, warrants attention
- **2** — Significant concern, warrants further investigation
- **3** — Strong concern, treat with serious caution

---

## Content Identification

| Field | Your entry |
|---|---|
| Content title or description | |
| URL or file reference | |
| Date encountered | |
| Platform or source | |
| Assessor name | |
| Assessment date | |

---

## LAYER 1 — Technical Markers

*This layer uses tool-assisted analysis to examine the technical properties of the content. Run each tool listed and record the outputs.*

### 1.1 Metadata Analysis

**Tool:** ExifTool (https://exiftool.org/) or Jeffrey's Exif Viewer (https://exif.regex.info/)

| Marker | Finding | Score (0–3) |
|---|---|---|
| Creation date consistent with claimed date | | |
| Device or software metadata present and consistent | | |
| GPS or location data consistent with claimed origin | | |
| Editing software traces present (e.g. Photoshop, Premiere, AI generation tools) | | |
| Metadata stripped or absent (itself a signal) | | |

**Layer 1.1 notes:**

---

### 1.2 Content Provenance Credentials

**Tool:** C2PA Verify (https://verify.contentauthenticity.org/)

| Marker | Finding | Score (0–3) |
|---|---|---|
| C2PA content credentials present | | |
| Credentials verified and unaltered | | |
| Chain of provenance complete | | |
| Absence of credentials noted (not proof of inauthenticity but relevant) | | |

**Layer 1.2 notes:**

---

### 1.3 Synthetic Content Detection

**Tools:** SynthID (Google DeepMind) / OpenAI detection tools / Forensically (https://29a.ch/photo-forensics/)

| Marker | Tool used | Finding | Score (0–3) |
|---|---|---|---|
| Synthetic watermark detected (SynthID) | | | |
| Compression artefact anomalies (Forensically ELA) | | | |
| Clone detection anomalies (Forensically) | | | |
| AI-generated content signals (OpenAI / other) | | | |
| Facial or body generation anomalies (if applicable) | | | |

**Layer 1.3 notes:**

---

### Layer 1 Summary

| | |
|---|---|
| Total technical markers score | / 36 |
| Key concerns identified | |
| Tools used | |
| Confidence in technical assessment | Low / Medium / High |

---

## LAYER 2 — Aesthetic Markers

*This layer uses structured human assessment to examine how the content looks and sounds. These are the conventions that documentary and journalistic media have developed over decades to signal authenticity. Generative systems increasingly reproduce these conventions — which is why this layer requires human interpretive judgement rather than automated detection.*

### 2.1 Visual Credibility Signals

| Marker | Assessment | Score (0–3) |
|---|---|---|
| Camera stability consistent with claimed context (e.g. handheld instability in field reporting) | | |
| Lighting consistent with claimed time, location, and conditions | | |
| Environmental detail (background, crowd, infrastructure) consistent with claimed setting | | |
| Visual quality consistent with claimed device and conditions (compression, resolution, grain) | | |
| Shadow and reflection consistency | | |
| Movement and physics naturalness (people, objects, environment) | | |

**Layer 2.1 notes:**

---

### 2.2 Audio Credibility Signals

| Marker | Assessment | Score (0–3) |
|---|---|---|
| Environmental sound consistent with claimed setting | | |
| Audio-visual synchronisation natural | | |
| Background noise consistent and continuous | | |
| Voice characteristics consistent across the content | | |
| Acoustic environment consistent with claimed space | | |

**Layer 2.2 notes:**

---

### 2.3 Documentary and Journalistic Framing Conventions

| Marker | Assessment | Score (0–3) |
|---|---|---|
| Framing and composition consistent with claimed genre (news, documentary, citizen journalism) | | |
| On-screen text, lower thirds, or captions consistent with claimed source | | |
| Editorial choices (cuts, transitions, pacing) consistent with claimed production context | | |
| Visual style consistent across the content | | |

**Layer 2.3 notes:**

---

### Layer 2 Summary

| | |
|---|---|
| Total aesthetic markers score | / 45 |
| Key concerns identified | |
| Most significant aesthetic signals | |
| Confidence in aesthetic assessment | Low / Medium / High |

---

## LAYER 3 — Narrative Markers

*This layer examines how the content tells its story. Authentic documentary content follows recognisable narrative conventions developed through journalistic and documentary practice. Generative systems increasingly reproduce these conventions. This layer requires the most human interpretive judgement and is the most resistant to automation — which is why it is the most important layer for restoring human responsibility in the verification process.*

### 3.1 Testimonial Structure

| Marker | Assessment | Score (0–3) |
|---|---|---|
| Witness or speaker identity verifiable or consistent | | |
| Testimony internally consistent throughout | | |
| Testimony consistent with other known accounts of the same event | | |
| Emotional register appropriate to claimed experience | | |
| Specific detail level appropriate (neither suspiciously vague nor suspiciously precise) | | |

**Layer 3.1 notes:**

---

### 3.2 Emotional and Rhetorical Signals

| Marker | Assessment | Score (0–3) |
|---|---|---|
| Emotional urgency proportionate to claimed event | | |
| Rhetorical framing neutral or appropriately positioned for claimed genre | | |
| Absence of manipulative or disproportionate emotional amplification | | |
| Call to action (if present) proportionate and appropriate to claimed context | | |

**Layer 3.2 notes:**

---

### 3.3 Contextual and Factual Consistency

| Marker | Tool / Source used | Assessment | Score (0–3) |
|---|---|---|---|
| Claims cross-referenced with established fact-checking sources (Google Fact Check, Snopes, etc.) | | | |
| Named persons, places, and events verifiable through independent sources | | | |
| Timeline consistent with independently verified events | | | |
| Visual content reverse-searched and origin verified (Google Images, TinEye) | | | |

**Layer 3.3 notes:**

---

### 3.4 Symbolic and Cultural Framing

| Marker | Assessment | Score (0–3) |
|---|---|---|
| Symbolic imagery consistent with claimed context and cultural setting | | |
| Narrative arc consistent with claimed genre conventions | | |
| Cultural and linguistic register consistent with claimed origin | | |
| Absence of anachronistic or culturally inconsistent elements | | |

**Layer 3.4 notes:**

---

### Layer 3 Summary

| | |
|---|---|
| Total narrative markers score | / 54 |
| Key concerns identified | |
| Most significant narrative signals | |
| Confidence in narrative assessment | Low / Medium / High |

---

## PROVENANCE INVENTORY — COMPOSITE ASSESSMENT

### Score Summary

| Layer | Score | Maximum | Percentage |
|---|---|---|---|
| Layer 1 — Technical markers | | 36 | |
| Layer 2 — Aesthetic markers | | 45 | |
| Layer 3 — Narrative markers | | 54 | |
| **Total** | | **135** | |

*Note: A higher score indicates more markers of concern identified. This is not a probability of inauthenticity — it is a structured map of where concern was identified and why.*

---

### Composite Interpretation

**Where concern was concentrated:**
*(Describe which specific markers across which layers raised the most significant concerns, and why)*

**Where the content appeared consistent:**
*(Describe which markers showed no concern and what that suggests)*

**Key uncertainties:**
*(Describe what could not be assessed with confidence and why)*

**What further investigation would be most valuable:**
*(Describe the single most important next step for verification)*

---

### Assessment Conclusion

| | |
|---|---|
| Overall authenticity concern level | None / Low / Moderate / High / Very High |
| Recommended action | Accept as authentic / Treat with caution / Do not use without further verification / Do not use |
| Reasoning for recommendation | |
| Assessor confidence | Low / Medium / High |

---

### Call to Action

*Complete this section. This is the most important part of the inventory.*

Based on this assessment, what is your responsibility as the person who encountered this content?

| Question | Your response |
|---|---|
| Will you share this content? Why or why not? | |
| Who else needs to know about your findings? | |
| What action does this content call for, if authentic? | |
| What action does this content call for, if inauthentic? | |
| Have you documented your assessment for others to review and contest? | |

---

## Assessment Record

| Field | Entry |
|---|---|
| Assessment completed by | |
| Date and time | |
| Time taken | |
| Tools used | |
| Peer reviewed by (if applicable) | |
| Assessment version | |

---

*This template is part of the Authenticity Lens framework — a human-centred, three-layer provenance inventory for synthetic media verification developed by Dr Amritha Subhayan Krishnan, Smart Story Labs.*
*License: CC BY 4.0 | Contact: skamritha@gmail.com | amrithask@smartstorylabs.com*
*Global Trust Challenge Prototyping Phase 2026 | ORCID: 0000-0002-4505-5609*
