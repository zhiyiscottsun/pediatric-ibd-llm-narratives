# Pediatric IBD LLM Narratives

This repository contains the generation prompts and large language model (LLM)-generated child-centered educational narratives used in the study:

**Evaluating Large Language Model-Generated Child-Centered Narratives for Pediatric Inflammatory Bowel Disease: Readability, Linguistic Diversity, and Human-AI Judgment**

## Overview

The study evaluated six LLMs for generating supportive, second-person educational narratives for children aged 6–10 years with inflammatory bowel disease (IBD).

Five clinically grounded scenarios were used:

1. Initial diagnosis and medication initiation
2. Symptom flare-ups
3. Dietary management
4. School attendance and daily routines
5. Hospital visits and follow-up tests

Each model generated one narrative for each scenario, resulting in 30 narratives in total.

## Models

The evaluated models were:

- GPT-5
- Gemini 2.5 Pro
- Claude Sonnet 4.5
- DeepSeek-V3.2
- Llama 4
- Mistral (Le Chat)

Narratives were generated using publicly available web-based interfaces rather than APIs.

## Repository Contents

### `prompts/`

Contains the full generation prompts used for the five pediatric IBD scenarios.

### `generated_narratives/`

Contains the generated narratives for each of the six evaluated LLMs.

## Evaluation

Narratives were evaluated using readability and linguistic diversity measures, semantic similarity analyses, the Patient Education Materials Assessment Tool (PEMAT), the CDC Clear Communication Index (CCI), clinician Likert ratings, and an LLM-based evaluator.

The clinician and LLM-based evaluations used the same four-dimensional Likert rubric:

- **Plausibility:** logical and clinical sensibility without obvious factual or logical errors
- **Relevance:** alignment with the specified scenario and task
- **Clarity:** understandability and age-appropriateness for children aged 6–10 years
- **Practicality:** usefulness and actionability in helping children and families understand and cope with the situation

The full evaluation methods and results are reported in the accompanying manuscript.

## Data Availability

This repository provides the full generation prompts and generated narratives used in the study. Individual clinician ratings and other internal evaluation records are not included.

## Citation

If you use these materials, please cite the accompanying paper:

Sun Z, Liu Y, Wang Z, Zhao H. *Evaluating Large Language Model-Generated Child-Centered Narratives for Pediatric Inflammatory Bowel Disease: Readability, Linguistic Diversity, and Human-AI Judgment.*

Citation details will be updated upon publication.

## Contact

For questions regarding the study materials, please contact zhiyisun@unc.edu.
