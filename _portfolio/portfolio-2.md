---
title: "Drug repurposing through network clustering"
excerpt: "Identifying potential drug repurposing candidates by community detection on heterogeneous networks.<br/><br/><img src='/images/drug_rep.png'>"
collection: portfolio
---

Drug repositioning is a viable strategy both to replenish the drying out drug pipelines and to surmount the innovation gap. Using known disease-gene and drug-target relationships, we built a weighted disease and drug heterogeneous network. The nodes represent drugs or diseases while the edges represent shared gene, biological process, pathway, phenotype or a combination of these features. 
<br/>
<br/>
![network](https://chaozhongyinxiang.github.io/images/drug_network.png)
<br/>
<br/>
We then applied existing [clustering algorithms](http://www.paccanarolab.org/cluster-one/) to detect tightly connected modules and then assembled putative drug repositioning candidates from these modules. The predictions were then validated using published literature. The method complemented the current computational approaches for drug repositioning discovery. [Read more](https://bmcsystbiol.biomedcentral.com/articles/10.1186/1752-0509-7-S5-S6)
<br/>
<br/>
![example](https://chaozhongyinxiang.github.io/images/drug_example.png)
<br/>
<br/>
