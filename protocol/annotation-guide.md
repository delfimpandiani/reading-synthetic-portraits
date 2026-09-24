
# Annotation Guide

## Unit of analysis

Use one synthetic image or portrait as the basic unit of analysis unless the project defines another unit explicitly.

## Multi-label coding

An image may contain several features. Code every feature independently unless the codebook specifies a mutually exclusive category.

## Annotation values

| Value | Meaning |
|---|---|
| `1` | Feature is visibly present according to the codebook definition |
| `0` | Feature is visibly absent according to the codebook definition |
| `U` | Uncertain: evidence does not support a confident decision |
| `NA` | Not assessable: crop, occlusion, low resolution, or image failure prevents evaluation |

## Coding procedure

1. Read the feature definition.
2. Inspect the image for visible evidence.
3. Apply inclusion and exclusion criteria.
4. Use `U` or `NA` where appropriate.
5. Add a brief note for uncertain, borderline, or unusual cases.
6. Avoid adding interpretation to the annotation field; record interpretation separately.

## Common guidance

### Cropping and occlusion

Use `NA` when the relevant body part, object, gaze direction, or compositional area cannot be assessed.

### Distortion and image failure

Use `U` if a feature may be present but synthetic distortion prevents a confident judgement. Add a note explaining the uncertainty.

### Emotion, personality, and intention

Do not code inferred traits as visual facts. Use visible descriptions. For example:

- Code “mouth corners visibly raised” only if the codebook defines that feature.
- Avoid coding “happy,” “submissive,” “dangerous,” or “confident” unless the project has developed observable definitions and ethical justification.

### Identity claims

Do not infer identity categories from appearance. Use only documented metadata where ethically appropriate, and distinguish prompted or classified fields from verified self-identification.

## Collaborative annotation

During group coding:

- compare difficult cases;
- record disagreement;
- check whether disagreement results from unclear definitions, overlapping features, or genuinely ambiguous images;
- revise the codebook when necessary;
- version revisions so earlier annotations remain interpretable.
