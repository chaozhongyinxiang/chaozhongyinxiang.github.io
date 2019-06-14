---
title: "Phenoxome: ranking pathogenic variants given phenotypic context"
excerpt: "A comprehensive computational framework to prioritize genetic variants based upon the likelihood of the variant being pathogenic given the phenotype of the patient. <br/><img src='/images/phenoxome_workflow.png'>"
collection: portfolio
---

Clinical exome sequencing has become the preferred diagnostic platform for complex pediatric disorders with suspected monogenic etiologies. Despite rapid advancements, the major challenge still resides in identifying the casual variants among the thousands of variants detected during CES testing, and thus establishing a molecular diagnosis. To improve the clinical exome diagnostic efficiency, we developed Phenoxome, a robust phenotype-driven model that adopts a network-based approach to facilitate automated variant prioritization. Phenoxome dissects the phenotypic manifestation of a patient in concert with their genomic profile to filter and then prioritize variants that are likely to affect the function of the gene (potentially pathogenic variants). 
<br/>
![workflow](https://chaozhongyinxiang.github.io/images/phenoxome_workflow.png)
<br/>
Phenoxome first annotates and filter variants based on a set of features such as population allele frequency, predicted protein effects and [HGMD](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5429360/) annotations. It then compiles a personalized gene panel from the patient's phenotypes described using [HPO terms](https://hpo.jax.org/app/).
<br/>
![pgp](https://chaozhongyinxiang.github.io/images/pgp.png)
<br/>
