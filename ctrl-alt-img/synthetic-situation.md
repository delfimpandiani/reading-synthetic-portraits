
# ctrl.alt.img as a synthetic situation

## Overview

ctrl.alt.img is an interactive AI photo-booth installation developed by affect lab. The corpus analysed in the accompanying chapter contains portraits generated between **24 May 2024 and 10 February 2025**. During this period, the installation travelled through several venues in the Netherlands:

- Foam Photography Museum, Amsterdam: 1 June–8 September 2024;
- Into The Great Wide Open festival, Vlieland: 29 August–1 September 2024;
- Forum, Groningen: 13–22 September 2024;
- Noorderlicht, Groningen: 26 October 2024–19 January 2025;
- Nederlands Fotomuseum, Rotterdam: 28 September 2024–25 May 2025.

The installation appeared in museums, exhibitions, and a festival setting. These locations likely shaped who encountered the booth and how visitors approached it. Collection dates overlap across sites, so the generation date of an individual portrait does not always establish its venue.

## The booth encounter

The installation consisted of an enclosed black photo booth with an interactive screen. To the researchers’ knowledge, visitors generally interacted with the booth without a human facilitator inside it; some prompt content suggests that a small number of visitors entered together.

Visitors first watched an informational video explaining the project and its context. A later section showed labels entered by previous visitors as inspiration. The video, booth setting, and interface formed part of the invitation to describe oneself.

## Image-production workflow

Each visit followed a fixed sequence:

1. A facial scan estimated ethnicity, gender, and age.
2. Ethnicity was assigned through a highest-percentage match from five predefined categories: **White, Black, Asian, Latino Hispanic, and Middle Eastern**.
3. Gender was predicted through the binary categories **male** and **female**.
4. Age was predicted numerically.
5. Visitors could edit these predictions before proceeding. The available records do not show whether or how often edits occurred.
6. Visitors entered between one and five free-text descriptors of their choice.
7. The system assembled the fields into a fixed English-language prompt template.
8. A diffusion-based image-generation system rendered a portrait.
9. The portrait appeared immediately on screen.
10. Visitors could email the portrait to themselves and were invited to select one of five emotional responses. Response data were unavailable.

The facial scan supplied the demographic prompt fields. It did not otherwise enter the generation workflow.

## Prompt template

The prompt template was approximately:

> “A photo of a [ethnic descriptor] [gender] who is [age] years old who is also [free-text self-description] sitting in a photo booth with a black background.”

Visitors entered between one and five descriptors without a controlled vocabulary or prescribed syntax. They often used commas as separators. Free-text descriptors could indicate appearance, personality, cultural or national affiliation, clothing, objects, activities, poses, or further image instructions.

One example prompt was:

> “A photo of a white man who is 29 years old who is also a italian, handsome, bearded, big nosed, normcore sitting in a photo booth with a black background.”

## Model and technical information

The portraits were generated using a legacy Stable Diffusion-derived system associated with an earlier phase of public diffusion-model development. The exact checkpoint, pipeline, model version, generation settings, and possible embedded stylistic instructions cannot now be recovered. The outputs show recurring distortions and unstable bodily detail. The prompt structure and, to the best of the researchers’ knowledge, the model version remained stable across the collection period.

The corpus provides a time-specific record of this installation. It does not support direct claims about contemporary image generators or unmediated model behaviour.

## Classification as representational infrastructure

The classifier’s ethnic categories and binary gender categories were not neutral background metadata. They produced an initial computational account of the visitor and entered the prompt used to generate the portrait. These racialising and cisheteronormative classifications therefore form part of the representational apparatus under study.

Visitors could edit the predicted fields. The initial classifier output nevertheless shaped the interaction, the available terms of legibility, and the prompt structure.

## Photo-booth framing and stylistic conditions

The prompt explicitly requested a photo booth and black background. Seated bodies, chairs, portrait framing, indoor scenes, front-facing composition, and black backgrounds should therefore be understood in relation to this template. Other patterns, including beautification, revealed skin, body-size emphasis, averted gaze, hand-to-face poses, hand signs, crotch-shot framing, and bodily distortions, were not explicitly solicited by that fixed clause. Their occurrence may reflect interactions among participant descriptors, demographic fields, template design, model behaviour, and unknown settings.

## Analytic implication

Every ctrl.alt.img portrait emerged through a stacked sociotechnical arrangement: facial classification; restricted ethnic and gender categories; participant edits and self-description; a fixed prompt template; photo-booth framing; black-background instruction; interface constraints; venue-specific participation; and an image-generation system whose technical details remain partly unavailable.

The corpus contains no unscaffolded model output. The object of analysis is the model as activated through this particular arrangement.

---