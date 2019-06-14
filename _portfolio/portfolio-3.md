---
title: "Using machine learning to facilitate variant classification in pediatric cancers"
excerpt: "A computational classifier to distinguish sequencing artifacts from *bona fide* variants from next-generation sequencing data in pediatric tumors <br/><br/><img src='/images/pca.png'>"
collection: portfolio
---

Molecular profiling has become essential for tumor risk stratification and treatment selections. However, cancer genome complexity and technical artifacts make identification of real variants a challenge. Clinical labs rely on manual screening, which is costly, subjective, and not scalable. We present a machine learning-based method to distinguish artifacts from true single nucleotide variants (SNVs) detected by NGS from tumor specimens. We compiled a cohort of over 11,000 SNVs from 291 individual tumor samples of pediatric cancer patients from 9 cancer types. The data was randomly split into three subsets that were mutually exclusive: training, validation and test set. 
<br/>
<br/>
![workflow](https://chaozhongyinxiang.github.io/images/aiqc_data.png)
<br/>
<br/>
A three-class classifier using Random Forest model was trained using the data. Besides the two classes of "True" and "Artifact", a variant could also be labeled as "Uncertain" to reflect the confidence of the classification for clinical assurnace. An "Uncertain" variant would require further manual inspection to determine its validity. 
<br/>
<br/>
![workflow](https://chaozhongyinxiang.github.io/images/aiqc_class.png)
<br/>
<br/>
The model was then evaluated and benchmarked using the test set. Over 96% of the SNVs received a definitive label while only 3.4% of the SNVs were labeled as "Uncertain". None of the TP SNVs were misclassified as sequencing artifacts or *vice versa*. Implementing the computational model in the clinical workflow has resulted in improved quality and efficiency. [Read more](https://www.biorxiv.org/content/10.1101/670687v1)
