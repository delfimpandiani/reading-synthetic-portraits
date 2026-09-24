# Reading Synthetic Portraits: A Protocol for Critical and Systematic Analysis of Representational Power

This repository provides a reusable, theory-informed protocol for developing systematic analyses of representational power in synthetic portraits, and accompanies the book chapter:

> Martinez Pandiani, D. S., Klein, E., Menebhi, D., & Voorzanger, L.  
> (2026). *Mapping the Latent Image: Analyzing Representational Power and Harm in Synthetic Portraits.*  
> In G. de Seta, A. Knuutila, & M. Pohjonen (Eds.), *Synthetic Situations: Ethnographic Methods for Post-Artificial Worlds*. Routledge. Forthcoming.

Synthetic portraits shape public visual culture through more than demographic visibility. They organise gaze, posture, gesture, composition, beautification, bodily exposure, atmosphere, cultural legibility, and other visual conditions through which people become recognisable, desirable, vulnerable, ordinary, threatening, or available for scrutiny.

Existing systematic evaluations of synthetic imagery often examine demographic presence and distribution. Critical visual scholarship offers accounts of style, affect, embodiment, visual hierarchy, and composition. This repository connects these approaches through a practical method for developing and using feature-based codebooks in relation to a specific synthetic situation.

## The protocol

The protocol supports a process in which researchers:

1. document the **synthetic situation** through which a corpus was produced;
2. establish a theoretical orientation that guides attention toward questions of representational power;
3. inspect images for recurring visual patterns;
4. formulate provisional seed features with observable visual bases;
5. develop a codebook collaboratively;
6. pilot and refine feature definitions;
7. analyse occurrence, accumulation, co-occurrence, and contextualised metadata patterns where appropriate;
8. interpret findings in relation to theory and the full sociotechnical conditions of image production.

Theory guides what becomes visible as a question of representational power. The corpus supplies feature candidates, the boundaries of their definitions, and the evidence for retaining, revising, or discarding them.

## Repository structure

```text
reading-synthetic-portraits/
│
├── protocol/
│   Reusable resources for researchers working with any synthetic-image corpus.
│
├── ctrl-alt-img/
│   A completed, situated application of the protocol to ctrl.alt.img,
│   a participatory AI photo-booth installation analysed through feminist,
│   postcolonial, and affect-theoretical approaches to representational power.
│
└── teaching-kit/
    Materials for teaching and workshop use, including worksheets,
    exercises, a facilitator guide, and assessment resources.
```

## Start here

- **Apply the method to your own corpus:** see [`protocol/`](protocol/). It includes the eight-stage protocol, Synthetic Situation Worksheet, theory-to-codebook guide, codebook template, annotation guidance, interpretation guidance, and flowchart.
- **See a completed example:** see [`ctrl-alt-img/`](ctrl-alt-img/). It includes a completed Synthetic Situation Worksheet, a 157-feature codebook in CSV and illustrated PDF form, and a taxonomy image.
- **Teach the method:** see [`teaching-kit/`](teaching-kit/). It includes student and facilitator materials, worksheets, exercises, and assessment resources.

## Responsible reuse

The protocol supports systematic analysis. It does not provide a universal taxonomy of representational harm, establish causal effects of a model or prompt field, or offer a general measure of model bias. Use it with contextual caution, transparency about uncertainty, and attention to the communities represented in a corpus.

The full ctrl.alt.img portrait corpus and raw prompts are not distributed through this repository. The installation involved public participation and participant self-description; unrestricted sharing may create contextual-integrity, exposure, and residual-identification risks.

## Acknowledgements

We thank the affect lab and Dr. Natalie Dixon for providing access to ctrl.alt.img data.


## Citation

Please cite the accompanying chapter when using, discussing, teaching, or adapting the methodological approach developed in this repository.

```bibtex
@incollection{martinez_pandiani_mapping_2026,
  author    = {Martinez Pandiani, Delfina S. and Klein, Emily and
               Menebhi, Dalila and Voorzanger, Lux Lemore},
  title     = {Mapping the Latent Image: Analyzing Representational Power
               and Harm in Synthetic Portraits},
  booktitle = {Synthetic Situations: Ethnographic Methods for
               Post-Artificial Worlds},
  editor    = {de Seta, Gabriele and Knuutila, Aleksi and
               Pohjonen, Matti},
  publisher = {Routledge},
  year      = {2026},
  note      = {Forthcoming}
}
```

Please also cite this repository when you reuse, adapt, or build on specific repository materials, including:

```bibtex
@software{martinez_pandiani_reading_2026,
  author  = {Martinez Pandiani, Delfina S. and Klein, Emily and
             Menebhi, Dalila and Voorzanger, Lux Lemore},
  title   = {Reading Synthetic Portraits: A Protocol for Critical and Systematic Analysis of Representational Power},
  year    = {2026},
  publisher = {GitHub},
  url     = {https://github.com/delfimpandiani/reading-synthetic-portraits}
}
```