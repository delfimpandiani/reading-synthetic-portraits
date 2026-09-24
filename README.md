# Reading Synthetic Portraits: A Protocol for Representational Power

This repository accompanies the chapter **“Reading Synthetic Portraits: A Protocol for Representational Power.”** It provides materials for studying aesthetic, affective, and compositional forms of representational power in synthetic portraits.

The repository presents a theory-informed, inductive feature-coding protocol. The approach connects feminist, postcolonial, and affect scholarship with systematic inspection of synthetic-image collections. It supports researchers who want to examine representational questions that extend beyond demographic presence and distribution, including gaze, posture, gesture, beautification, bodily exposure, composition, affect, and cultural legibility.

## What this repository contains

- A transferable eight-stage protocol for analysing synthetic portraits.
- Guiding questions for documenting a synthetic situation.
- A codebook template for creating visually observable feature categories.
- Annotation guidance, including inclusion criteria, exclusion criteria, exemplar images, and borderline cases.
- The ctrl.alt.img-derived 157-feature taxonomy.
- A decision log documenting how features were discussed, merged, separated, retained, and removed.
- Prompt-parsing documentation and metadata schemas.
- Scripts for feature prevalence, co-occurrence, and descriptive metadata comparisons.
- Aggregated outputs used in the accompanying chapter.

## The central methodological claim

Synthetic portraits are produced through sociotechnical arrangements that include models, prompts, interfaces, classifications, participants, settings, and curatorial choices. The protocol therefore examines generated images together with the conditions through which they were produced.

Feminist, postcolonial, and affect scholarship provides a sensitising orientation toward othering, racialised embodiment, objectification, visual hierarchy, gender display, affect, and intersectionality. Corpus inspection supplies the observable feature categories and their boundaries. Collaborative codebook development and pilot coding make those categories open to scrutiny and revision.

## The ctrl.alt.img case

The ctrl.alt.img materials demonstrate the protocol through a participatory AI photo-booth installation. Visitors encountered a facial classifier, editable demographic predictions, free-text self-description, a fixed prompt template, photo-booth framing, and a diffusion-based image-generation system. The installation therefore provides a situated case for examining how classification, participation, prompting, interface design, and model behaviour shape synthetic portraits.

The ctrl.alt.img codebook arose from this specific arrangement. It should be treated as a resource for adaptation, critique, expansion, and correction. It does not provide a universal or complete taxonomy of representational harm.

## Quick start

1. Read `docs/protocol.md`.
2. Complete the synthetic-situation documentation in `docs/synthetic-situation-template.md` for your own corpus.
3. Read `docs/theory-to-codebook.md` before defining features.
4. Copy `codebook/codebook-template.csv` and create a project-specific codebook.
5. Pilot the codebook on a documented sample and revise definitions.
6. Use the scripts in `analysis/` to generate descriptive summaries.
7. Interpret outputs in relation to the full synthetic situation and your theoretical orientation.

## Responsible reuse

This protocol supports systematic analysis. It does not turn representational harm into a neutral metric, establish causal effects of individual prompt fields, or provide a general measure of model bias. Use the method with contextual caution, transparency about uncertainty, and attention to the communities represented in the corpus.

See `data/data-access-and-ethics.md` for restrictions and guidance concerning the ctrl.alt.img materials.

## Citation

If you use or adapt these materials, cite the accompanying chapter. If you reuse or adapt the protocol, cite the chapter and describe your modifications to the protocol, codebook, theoretical orientation, and corpus documentation.


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