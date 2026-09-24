# ctrl.alt.img: A Situated Instance of the Synthetic Portrait Feature-Coding Protocol

This folder documents how the **theory-informed, inductive feature-coding protocol for synthetic images** was applied to **ctrl.alt.img**, a participatory AI photo-booth installation developed by affect lab.

The general protocol provides reusable worksheets, guidance, and templates for researchers who want to analyse a synthetic-image corpus through a theory-informed process of corpus inspection, feature formation, codebook development, coding, and contextual interpretation. This folder contains the completed ctrl.alt.img materials that resulted from applying that process to one particular synthetic situation.

## What is in this folder

| File | Contents | Role in the protocol |
|---|---|---|
| `ctrlaltimg-synthetic-situation-worksheet.md` | A completed version of the general Synthetic Situation Worksheet. It documents the installation, venues, dates, classifier, prompt structure, participant interaction, model information, technical unknowns, data conditions, and analytic implications. | **Stage 1: Situate the synthetic-image system** |
| `ctrlaltimg-codebook.csv` | The machine-readable ctrl.alt.img feature codebook. It contains the 157 features developed through the research process, with their codes, themes, feature names, definitions, example references, and coding notes. | **Stages 3–6: Corpus inspection, seed features, collaborative codebook development, and pilot refinement** |
| `ctrlaltimg-codebook.pdf` | A readable version of the codebook. It includes visual examples that clarify how feature definitions were applied. | **Stages 5–6: Codebook development, annotation guidance, and pilot refinement** |
| `ctrlaltimg-codebook-taxonomy.png` | A visual map of the 157-feature taxonomy and its thematic clusters. | **Outcome of collaborative feature formation and taxonomy development** |

## How to read these materials

### 1. Begin with the completed synthetic-situation worksheet

Read `ctrlaltimg-synthetic-situation-worksheet.md` first. It explains the conditions through which the portraits were produced and the limits those conditions place on interpretation, as ctrl.alt.img portraits were produced through a stacked arrangement of:

- facial classification with constrained ethnic and gender categories;
- participant edits and self-description;
- a fixed prompt template including photo-booth and black-background instructions;
- a screen interface and instructional video;
- cultural venues and public participation;
- a legacy diffusion-based image-generation system.

The corpus contains no unscaffolded model output. Its portraits should be analysed as outputs of this particular synthetic situation.

### 2. Use the taxonomy diagram for orientation

Open `ctrlaltimg-codebook-taxonomy.png` to see the overall structure of the 157-feature taxonomy and its clusters. The diagram provides a high-level map of the feature space developed through the research process.

### 3. Consult the PDF codebook for visual clarification

Use `ctrlaltimg-codebook.pdf` when you want to understand how a feature was recognised visually. The PDF includes examples and is the most useful resource for reading feature definitions in relation to images.

### 4. Use the CSV codebook for searching, filtering, and adaptation

Use `ctrlaltimg-codebook.csv` when you want to:

- search features by theme or name;
- inspect definitions and coding notes;
- compare the codebook with a new corpus;
- adapt features for another synthetic-image situation;
- identify features that require revision, merging, splitting, or removal;
- use the taxonomy in a teaching or collaborative coding exercise.

## Relationship to the reusable protocol

This folder should be read alongside the repository’s general `protocol/` folder.

| General protocol resource | ctrl.alt.img material |
|---|---|
| Synthetic Situation Worksheet | `ctrlaltimg-synthetic-situation-worksheet.md` |
| Codebook Template | `ctrlaltimg-codebook.csv` |
| Theory-to-Codebook Guide | The documented feature taxonomy, definitions, examples, and notes in the ctrl.alt.img codebook |
| Annotation Guide | The codebook’s definitions, example images, and coding notes in the PDF and CSV |
| Interpretation and Limits Guide | The synthetic-situation worksheet and the accompanying chapter |

The general protocol explains how to move from theory to a feature-based codebook. The ctrl.alt.img materials show what that movement produced in one particular case.

## Reuse, adaptation, and critique

The ctrl.alt.img codebook is a situated research output. It reflects:

- the theoretical orientations used in this research;
- the visual patterns present in this corpus;
- the installation’s classifier, categories, prompt template, and interface;
- the public and institutional settings in which the portraits were generated;
- collaborative decisions about feature definitions and coding boundaries.

Researchers, students, and educators may use these materials as an example, starting point, comparison object, or teaching resource. Reuse should include adaptation and critique. A feature may travel well to another corpus, require a revised definition, overlap with another feature, or fail to apply in a different synthetic situation.

The materials do not provide a universal taxonomy of representational features nor harm, a general evaluation of diffusion models, or causal evidence about prompt fields, demographic categories, training data, or model architecture.

## Data access

This folder does not include the full ctrl.alt.img portrait corpus or raw prompts.

## Citation

If you use or adapt these materials, cite the accompanying chapter:

```
@incollection{martinez_pandiani_mapping_2026,
  author    = {Martinez Pandiani, D. S. and Klein, E. and Menhebi, D. and Voorzanger, L.},
  title     = {Mapping the Latent Image: Analyzing Representational Power and Harm in Synthetic Portraits},
  booktitle = {Synthetic Situations: Ethnographic Methods for Post-Artificial Worlds},
  editor    = {de Seta, Gabriele and Knuutila, Aleksi and Pohjonen, Matti},
  publisher = {Routledge},
  year      = {2026},
  note      = {Forthcoming}
}
```