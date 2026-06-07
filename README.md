# PCNN Codebook Viewer

A single-file, browser-based viewer for browsing the codebook (data dictionary) of the **Post-COVID Network Netherlands (PCNN)**.

- **Project:** Post-COVID Network Netherlands (PCNN), funded by ZonMw
- **Status:** Read-only viewer for the PCNN community — access controlled (distribution under discussion)
- **Current version:** v1.1
- **License:** Proprietary. All rights reserved. See [LICENSE](LICENSE).

## Project context

This viewer was developed within the Post-COVID Network Netherlands (PCNN) — a national collaborative partnership in which patients, scientists, healthcare professionals, and societal partners work together to coordinate scientific research and patient care for people with post-COVID. Through this coordination, knowledge is systematically built up to better understand post-COVID, improve diagnostics, and develop better treatment options.

The PCNN network actively promotes the utilisation of relevant knowledge to continuously improve care for all adults and children with post-COVID in the Netherlands. PCNN is funded by ZonMw.

The viewer makes the PCNN codebook accessible to project collaborators, supporting FAIR data principles (Findable, Accessible, Interoperable, Reusable).

## What it does

A read-only viewer for the PCNN codebook. Researchers can browse, search, and view variables — but not edit them.

**Key features:**

- Browse all variables, grouped by questionnaire (instrument)
- Family grouping in the instrument dropdown: questionnaires sharing a name prefix (e.g. all `PROMIS-*`) are visually grouped
- Atomic instrument matching: a variable with Instrument = `"DSQ-PEM + DSQ-2"` is shown under both DSQ-PEM and DSQ-2
- Search across multiple fields with four match modes (contains / exact / starts-with / regex), with hit-highlighting in results
- View the full details of any variable
- Export to Excel: download the entire codebook or a single instrument as an Excel file
- Copyright filter: questionnaires marked as restricted (e.g. EQ-5D-5L, PROMIS-29) are replaced with a placeholder row showing who to contact for access

Quick start
The viewer is hosted online and protected with a shared password — there is nothing to download or install.

Open the viewer link in any modern browser (Chrome, Edge, Firefox, Safari): https://hajarhn.github.io/codebook-viewer/
Enter the password (shared separately by the codebook coordinator) and click Unlock.
The codebook loads automatically.

No account or installation is needed.

## Visible fields

Each variable shows these fields, with these display names:

| Display name | Description |
|---|---|
| Theme | Thematic grouping |
| Subdomain | Finer subcategory |
| Instrument | The questionnaire(s) this variable belongs to |
| Variable name CBS | Standardised unique identifier |
| Variable label (NL) | Dutch wording of the question |
| Variable label (EN) | English wording of the question |
| Value label (NL) | Dutch answer options |
| Value label (EN) | English answer options |
| Standardized name (FAIR coding) | Cross-study FAIR-aligned variable name |

## Updating

When a new codebook version is released, you will receive an updated viewer file to replace your local copy. The release date is shown in the **About** dialog inside the viewer.

## Feedback

We welcome suggestions and corrections. Inside the viewer, open the menu and click **Suggest a change** to open a pre-filled email, or use the **Contact** option to reach the codebook coordinator.

## Browser support

| Feature | Chrome / Edge / Firefox / Safari (recent) |
|---|---|
| All viewer features | ✓ |

## Privacy

The viewer runs entirely in your browser. The codebook is bundled directly into the HTML file, and no codebook content or personal data is transmitted or stored anywhere.


## Acknowledgement

If you use this viewer in a paper or presentation, please also acknowledge:

> The PCNN Codebook Viewer was developed within the Post-COVID Network Netherlands (PCNN).

## Contact

**Hajar Hasannejadasl**
Maastricht University Medical Centre+ (MUMC+)
Post-COVID Network Netherlands (PCNN)

- Work: hajar.hasannejadasl@mumc.nl
- Personal: hajar.hasannejad@gmail.com

For corrections, suggestions, or questions, please email or open an issue in this repository.

© 2026 . All rights reserved.
