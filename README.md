# CHAI4T
***Causal Hybrid Artificial Intelligence for Trading***

![CHAI4T](https://github.com/user-attachments/assets/2bb7c862-4339-457f-9f16-1aafd89bd475)

### Causal Modeling Foundamental and Overview
- Books
  - [The Book of Why](https://www.amazon.ca/Book-Why-Science-Cause-Effect/dp/1541698967/ref=sr_1_1?crid=1OFQ6OH1HP0KZ&keywords=the+book+of+why&qid=1673832347&sprefix=the+book+of+why%2Caps%2C133&sr=8-1) *Judea Pearl (2020)*
  - [Elements of Causal Inference: Foundations and Learning Algorithms](https://www.amazon.ca/Elements-Causal-Inference-Foundations-Algorithms/dp/0262037319/ref=sr_1_2?crid=1TPOV4CZPTBM0&dib=eyJ2IjoiMSJ9.mKKIWrdHIINP3xMjfNgyHEbt9UnkNqYWjY9qTSl6-Y0iqKEmhFwdSC7CmOczaHlD.5Npmz6JaZkw6tvi7JB26SwsGncnt2BvpkTrvk8e4hpw&dib_tag=se&keywords=Causal+Inference+and+Discovery+in+Python&qid=1750385335&sprefix=causal+inference+and+discovery+in+python+%2Caps%2C49&sr=8-2) *Jonas Peters et al. (2017)*
  - [Causal Machine Learning](https://www.manning.com/books/causal-machine-learning) *Robert Ness (2024)*
  - [Causal Inference and Discovery in Python](https://www.amazon.ca/Causal-Inference-Discovery-Python-learning/dp/1804612987/ref=sr_1_1?crid=1TPOV4CZPTBM0&dib=eyJ2IjoiMSJ9.mKKIWrdHIINP3xMjfNgyHEbt9UnkNqYWjY9qTSl6-Y0iqKEmhFwdSC7CmOczaHlD.5Npmz6JaZkw6tvi7JB26SwsGncnt2BvpkTrvk8e4hpw&dib_tag=se&keywords=Causal+Inference+and+Discovery+in+Python&qid=1750385244&sprefix=causal+inference+and+discovery+in+python+%2Caps%2C49&sr=8-1) *Aleksander Molak (2023)*
- Videos
  - [New Science of Cause and Effect](https://www.youtube.com/watch?v=ZaPV1OSEpHw&list=PLzERW_Obpmv-8z4cjUpUC1ciUIFHkAMSR&index=3) *Judea Pearl (2018)*
  - [Introduction to Causal ML](https://www.youtube.com/watch?v=7Zr6_Gdd0fo&list=PLD7HFcN7LXRf9cqPMGU2N6PLhDk2d6V5M&index=2) *Microsoft Research (2021)*
- Papers
  - [The causal foundations of structural equation modeling](http://ftp.cs.ucla.edu/pub/stat_ser/r370.pdf)  *Judea Pearl (2021)*
  - [Causal machine learning: a survey and open problems](https://arxiv.org/abs/2206.15475) *Kaddour, Jean, et al. (2022)*
  - [A survey of learning causality with data: Problems and methods](https://arxiv.org/pdf/1809.09337) *Guo, Ruocheng et al. (2020)*

### Causal Discovery (function based, independece based, score based, LLM)
- Score based (including continuous optimization/gradient based)
  - [Generalized score functions for causal discovery](https://dl.acm.org/doi/abs/10.1145/3219819.3220104) *Huang, Biwei, et al. (2018)*
  - [Dags with no tears: Continuous optimization for structure learning by Zheng, Xun et al. (2018)](https://arxiv.org/pdf/1803.01422)
  - [D’ya like dags? a survey on structure learning and causal discovery by Vowels et al. (2022)](https://spaces-cdn.owlstown.com/blobs/zc0dpw536od33iswa8v398t3libh)
- Functional based
  - [A survey of causal discovery based on functional causal model](https://www.sciencedirect.com/science/article/abs/pii/S0952197624004160) *Wang, Lei, et al. (2024)*
- Constraint based
  - [Review of Causal Discovery Methods Based on Graphical Models](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2019.00524/full) *Glymour, C., Zhang, K., & Spirtes, P. (2019)*
- LMM based
  - [Bridging causal discovery and large language models: A comprehensive survey of integrative approaches and future directions](https://arxiv.org/pdf/2402.11068) *Wan, Guangya et al. (2024)*
  - [Large Language Models and Causal Inference in Collaboration: A Comprehensive Survey](https://arxiv.org/pdf/2403.09606) *Wang, et al. (2025)*
- Other

### Causal Discovery with time series data
- [Causal discovery from temporal data: An overview and new perspectives](https://dl.acm.org/doi/pdf/10.1145/3705297) *Gong, Chang, et al. (2024)*
- [Dynotears: Structure learning from time-series data](https://arxiv.org/abs/2002.00498) *Pamfil, Roxana, et al. (2020)*
- [Rhino: Deep causal temporal relationship learning with history-dependent noise](https://arxiv.org/abs/2210.14706) *Gong, Wenbo, et al. (2022)*
- [Time-Series Analysis: Why Causality is the Only Way](https://www.causalens.com/blog/time-series-analysis-why-causality-is-the-only-way/) *Causalense*
  
### Causal Deep Learning
- [Causal inference meets deep learning: A comprehensive survey](https://pmc.ncbi.nlm.nih.gov/articles/PMC11384545/pdf/research.0467.pdf) *Jiao, Licheng, et al. (2024)*

### Causal Representative Learning
- [Toward causal representation learning](https://arxiv.org/pdf/2102.11107.pdf) *Schölkopf, Bernhard et al. (2021)*
- [Video Towards causal representative learning](https://www.youtube.com/watch?v=rKZJ0TJWvTk) *Yoshua Bengio (2021)*

### Causal Reinforcement Learning
- [A survey on causal reinforcement learning](https://arxiv.org/pdf/2302.05209) *Zeng, Yan et al. (2024)*

### Causal Modeling Apps
- Causal Identification/Do-calculus
  - [Ananke](https://ananke.readthedocs.io/en/latest/index.html) - Full implementation of Do-calculus in Python
  - [DoWhy](https://github.com/py-why/dowhy) - Partial identification in Python
  - [Tetrad](https://www.cmu.edu/dietrich/philosophy/tetrad/) - Full implementation of Do-calculus in Java
- Causal Inference
  - [DoWhy](https://github.com/py-why/dowhy) - in combination with EconML, covers end to end inference
  - [EconML](https://github.com/py-why/econml)
  - [Ananke](https://ananke.readthedocs.io/en/latest/index.html) - Dynamic treatment/time-varying confounders
  - [CausalML](https://causalml.readthedocs.io/en/latest/about.html) - Full implementation of Do-calculus in Java
- Causal Inference
  - [gCastle](https://github.com/huawei-noah/trustworthyAI/tree/master/gcastle) - PC, GES, NOTEARS, LiNGAM, GAE, RL/CORL (RL-based), HPCI/TTPM (Hawkes process)
  - [Tetrad](https://www.cmu.edu/dietrich/philosophy/tetrad/) - PC, R/FCI, R/GES, LiNGAM
  - [CausalNex](https://github.com/mckinsey/causalnex/) - DY/NOTEARS, DAG-GNN based on Bayesian Network, for time series data
  - [tigramite](https://github.com/jakobrunge/tigramite) - PCMCI/+, LPCMCI, RPCMCI (regime switching), specifically for time series data
  - [causal-learn](https://github.com/py-why/causal-learn) - PC, G/FCI, G/F/GES, LiNAGAM, NOTEARS using Neural nets
  - [tslearn](https://github.com/tslearn-team/tslearn/blob/main/README.md) - Granger causality based
    
### Causal Modeling in Finance
- Overview
  - [Causal Factor Investing: Can Factor Investing Become Scientific? ](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4205613) *López de Prado (2023)*
- Framework
  - [A Protocol for Causal Factor Investing](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5277078) *Lopez de Prado (2025)*
- Using Constraint based model
  - [Causal Network Representations in Factor Investing](https://onlinelibrary.wiley.com/doi/epdf/10.1002/isaf.70001) *Howard et al. (2025)*
  - [Causal discovery in financial markets: A framework for nonstationary time-series data](https://arxiv.org/abs/2312.17375) *Sadeghi et al. (2023)*
- Using LLM
  - [Towards Automating Causal Discovery in Financial Markets and Beyond](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4679414) *Alik et al. (2023)*

### Quant Trading Books
- [Machine Learning for Algorithmic Trading 2ed](https://www.amazon.ca/Machine-Learning-Algorithmic-Trading-alternative/dp/1839217715/ref=sr_1_5?crid=1WKCFI3B1XERF&keywords=machine+learning+for+trading&qid=1673834200&sprefix=machine+learning+for+trading%2Caps%2C116&sr=8-5) *Stefan Jansen (2020)*
- [Advances in financial machine learning](https://www.amazon.ca/Advances-Financial-Machine-Learning-Marcos/dp/1119482089/?_encoding=UTF8&pd_rd_w=srIIn&content-id=amzn1.sym.dbec2bc2-8bcf-4dc6-b4cd-0a11cd6e5d70&pf_rd_p=dbec2bc2-8bcf-4dc6-b4cd-0a11cd6e5d70&pf_rd_r=136-9382348-2538712&pd_rd_wg=BGhaZ&pd_rd_r=e37e979e-b9d2-45b1-bf54-f18ab28a126b&ref_=aufs_ap_sc_dsk) *De Prado, Marcos Lopez. John Wiley & Sons, 2018.*
- [Quantitative Trading: How to Build Your Own Algorithmic Trading Business](https://www.amazon.ca/Quantitative-Trading-Build-Algorithmic-Business/dp/1119800064/ref=pd_bxgy_img_sccl_1/134-0034359-5120134?pd_rd_w=jcpBa&content-id=amzn1.sym.17b2b149-58e2-4824-ba79-851c5f351fdc&pf_rd_p=17b2b149-58e2-4824-ba79-851c5f351fdc&pf_rd_r=592XE7GZ2HW2SWRRTQ5Z&pd_rd_wg=lFwiw&pd_rd_r=c2153cfc-c24a-4611-8308-100492d98404&pd_rd_i=1119800064&psc=1) *Ernest Chan (2021)*
- [Machine Learning in Finance From Theory to Practice](https://www.amazon.ca/Machine-Learning-Finance-Theory-Practice/dp/3030410676/ref=sr_1_13?crid=1WKCFI3B1XERF&keywords=machine+learning+for+trading&qid=1673834200&sprefix=machine+learning+for+trading%2Caps%2C116&sr=8-13) *Matthew Dixon et al (2020)*
