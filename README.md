# PCNN Codebook Viewer

A browser-based, read-only viewer for the codebook (data dictionary) of the Post-COVID Network Netherlands (PCNN).

**Project:** Post-COVID Network Netherlands (PCNN), funded by ZonMw
**Status:** Read-only viewer for the PCNN community access controlled (distribution under discussion)
**Current version:** v2.5 (November 2026)
**License:** Proprietary. All rights reserved. See [LICENSE](LICENSE).

## Project context

This viewer was developed within the Post-COVID Network Netherlands (PCNN) a national collaborative partnership in which patients, scientists, healthcare professionals and societal partners work together to coordinate scientific research and patient care for people with post-COVID. Through this coordination, knowledge is systematically built up to better understand post-COVID, improve diagnostics and develop better treatment options.

The PCNN network actively promotes the utilisation of relevant knowledge to continuously improve care for all adults and children with post-COVID in the Netherlands. PCNN is funded by ZonMw.

The viewer makes the PCNN central codebook accessible to project collaborators and supports the FAIR data principles (Findable, Accessible, Interoperable, Reusable).

## What it does

The viewer shows the **published** part of the PCNN central codebook: every variable with its question in Dutch and English, its answer options and its FAIR code. Researchers can browse, search, view and download but not edit. The codebook itself is maintained by the codebook team in the PCNN Codebook Editor.

**Key features**

- **Browse by questionnaire (instrument).** Related questionnaires are grouped in the dropdown (for example all PROMIS-\*). A variable that belongs to two questionnaires (for example `DSQ-PEM + DSQ-2`) is shown under both, in each questionnaire's own order.
- **Instructions.** When a questionnaire has an instruction text, it is shown above its variables.
- **Answer options** are shown as a clear list of codes and labels, in Dutch and English.
- **Links to terminologies.** FAIR codes link directly to the concept: `sct_…` opens the SNOMED CT browser, `lnc_…` LOINC (loinc.org) and `ncit_…` the NCI Thesaurus (EVS Explore). Project-specific `pcnn_` codes have no external link.
- **Derived variables** (ƒx) show their formula and the variables it uses.
- **Search** across all questionnaires in the fields you choose, with four match modes (contains / exact / starts with / regex) and the matches highlighted.
- **Export to Excel:** all variables or selected questionnaires, in one sheet or one sheet per questionnaire.
- **Copyright protection:** questionnaires that may not be shown (for example EQ-5D-5L and PROMIS-29, or any questionnaire marked *restricted* in the codebook) appear as a placeholder with a contact address — on screen and in Excel.
- **Always up to date:** the viewer reads the latest published codebook each time it is opened.

## Quick start

The viewer is hosted online and protected with a shared password — there is nothing to download or install.

1. Open the viewer in any modern browser (Chrome, Edge, Firefox, Safari): **https://hajarhn.github.io/codebook-viewer/**
2. Enter the password (shared separately by the codebook coordinator) and click **Unlock**.
3. Choose a questionnaire in **Instrument**, or use the **Search** tab.

No account or installation is needed. A step-by-step guide with screenshots is available from the codebook coordinator.

## Fields shown

| Display name | Description |
| --- | --- |
| Theme | Thematic grouping |
| Subdomain | Finer subcategory |
| Instrument | The questionnaire(s) this variable belongs to |
| Variable name CBS | Standardised unique identifier |
| Variable label (NL) | Dutch wording of the question |
| Variable label (EN) | English wording of the question |
| Value label (NL) | Dutch answer options |
| Value label (EN) | English answer options |
| Standardized name (FAIR coding) | FAIR code of the variable (SNOMED CT, LOINC, NCIt or a project code), linked to the terminology |

## Updating

There is nothing to update on your side. The viewer reads the current published codebook directly from the PCNN codebook database every time it is opened; refresh the page to see the latest changes. Questionnaires that are still being reviewed are not shown until they are published.

## Feedback

We welcome suggestions and corrections. Click **✎ Suggest a change** next to a variable, or open **ℹ️ About → Suggest a change / report issue**: your own e-mail program opens with a pre-filled message, which is only sent when you press Send. **ℹ️ About → Contact** gives the address of the codebook coordinator.

## Browser support

| Feature | Chrome / Edge / Firefox / Safari (recent) |
| --- | --- |
| All viewer features | ✓ |

## Privacy and security

- The codebook contains **descriptions of variables only** (metadata) — never participant or patient data.
- The viewer loads the published codebook from the PCNN codebook database (Supabase, EU region) over an encrypted connection, with read-only access. It cannot change anything in the codebook.
- The password keeps the page within the PCNN network; it is a shared access code, not a personal account.
- The viewer does not collect or store any personal data. A suggestion is sent from your own e-mail program, only when you choose to send it.

## Acknowledgement

If you use this viewer in a paper or presentation, please acknowledge:

> The PCNN Codebook Viewer was developed within the Post-COVID Network Netherlands (PCNN).

## Contact

Hajar Hasannejadasl
Maastricht University Medical Centre+ (MUMC+)
Post-COVID Network Netherlands (PCNN)

Work: hajar.hasannejadasl@mumc.nl
Personal: hajar.hasannejad@gmail.com

For corrections, suggestions or questions, please e-mail or open an issue in this repository.

© 2026 Hajar Hasannejadasl. All rights reserved.
