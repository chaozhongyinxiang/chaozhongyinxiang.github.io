---
title: "ToppMiR: ranking microRNAs in biological context"
excerpt: "A computational workbench to prioritize miRNAs provided disease context represented by messengerRNA targets.<br/><img src='/images/toppmir_net.png'>"
collection: portfolio
---
Identifying functionally significant microRNAs and their correspondingly most important messenger RNA targets in specific biological contexts is a critical task to improve our understanding of molecular mechanisms underlying organismal development, physiology and disease. We have developed [ToppMiR](https://academic.oup.com/nar/article/42/W1/W107/2437383), a web-based analytical workbench that allows miRs and mRNAs to be co-analyzed via biologically centered approaches in which gene function associated annotations are used to train a machine learning-based analysis engine.  
![workflow](https://chaozhongyinxiang.github.io/images/toppmir_work.png)
<br/>
ToppMiR learns about biological contexts based on gene associated information from expression data or from a user-specified set of genes that relate to context-relevant knowledge or hypotheses. Within the biological framework established by the genes in the training set, its associated information content is then used to calculate a features association matrix composed of biological functions, protein interactions and other features. This scoring matrix is then used to jointly rank both the test/candidate miRs and mRNAs. ToppMir is [publicly available](https://toppmir.cchmc.org/).
<br/>
![workflow](https://chaozhongyinxiang.github.io/images/toppmir_rank.png)
<br/>
