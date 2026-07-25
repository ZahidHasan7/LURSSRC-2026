# From Forgetting to Factuality: Formalizing the Unlearning–Hallucination Interaction in Large Language Models

This repository contains the research paper and associated resources for **From Forgetting to Factuality**, a study on the intersection of machine unlearning and LLM hallucinations.

## Abstract
Machine unlearning, the selective removal of learned knowledge from trained models, has become mandatory under privacy regulations such as the GDPR and the EU AI Act. Yet its effect on model factuality remains empirically understudied. In this work, we reveal a critical oversight in the current research agenda. While unlearning algorithms aim to remove particular knowledge, they also inadvertently create hallucinations by disrupting shared parameter spaces that encode related knowledge.

We formulate this problem within the **Unlearning-Hallucination Interaction Framework (UHIF)**, where it is represented as a three-dimensional trade-off between unlearning effectiveness, utility preservation, and hallucination risk. Through a systematic review of 57 papers published between 2020 and 2026, we present the first taxonomy of 15+ unlearning techniques and evaluate their properties across hallucination dimensions. 

Finally, we propose the **HalUnlearn-Bench** protocol for benchmarking unlearning algorithms across four complementary measures of unlearning completeness, utility preservation, and hallucination resistance.

## Contents
- `paper.txt` - The source manuscript.
- `M. M. Zahid_Hasan_Shakera_Jannat_Ema_FromForgettingToFactuality_Formatted_LURSSRC2026 (2).pdf` - Compiled camera-ready PDF.

## HalUnlearn-Bench
The pilot notebook and full implementation used to produce Table VII are available at:
[Halunlearn Bench Pilot Notebook](https://github.com/ZahidHasan7/Paper/blob/main/Halunlearn%20bench%20pilot.ipynb)

## Authors
- **M. M. Zahid Hasan** - B.Sc. in Software Engineering, Shahjalal University of Science and Technology
- **Shakera Jannat Ema** - B.Sc. in Software Engineering, Shahjalal University of Science and Technology

## Affiliation
**LURS - Leading University Research Society**  
Leading University, Sylhet, Bangladesh
