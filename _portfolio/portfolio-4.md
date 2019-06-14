---
title: "ToppMiR: ranking microRNAs in biological context"
excerpt: "A computational workbench to prioritize miRNAs provided disease context represented by messengerRNA targets.<br/><img src='/images/toppmir.png'>"
collection: portfolio
---

Despite rapid advancements, the major challenge still resides in identifying the casual variants among the thousands of variants detected during clinical exome sequencing testing. To improve the clinical exome diagnostic efficiency, we developed [Phenoxome](https://www.nature.com/articles/s41431-018-0328-7), a robust phenotype-driven model that adopts a network-based approach to facilitate automated variant prioritization. Phenoxome dissects the phenotypic manifestation of a patient in concert with their genomic profile to filter and then prioritize variants that are likely to affect the function of the gene. 
<br/>
<br/>
![workflow](https://chaozhongyinxiang.github.io/images/phe_workflow.png)
<br/>
<br/>
Phenoxome first annotates and filters variants based on a set of features such as population allele frequency, predicted protein effects and [HGMD](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5429360/) annotations. It then compiles a personalized gene panel from the patient's phenotypes described using [HPO terms](https://hpo.jax.org/app/) to rank the genes harboring the variants. As a part of validation, Phenoxome identified the causative variants within the top 10 candidates in more than 70% in the clinical cases. Phenoxome is [publicly available](https://phenoxome.chop.edu/), and we are in the process of improving its performance using more training data and variant characteristics.
<br/>
<br/>
![pgp](https://chaozhongyinxiang.github.io/images/pgp.png)
<br/>
