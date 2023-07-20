# Tabular-ML (big update coming soon)

Tabular-ML

| Title                                                                                                                                                             | Date     | Highlights                                                                                                                                                            | AI-Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a href="https://arxiv.org/pdf/2307.00467.pdf">MissDiff: Training Diffusion Models on Tabular Data with Missing Values</a>                                        | Jul 2023 |                                                                                                                                                                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| <a href="https://arxiv.org/pdf/2307.08175.pdf">On the Need for a Language Describing Distribution Shifts: Illustrations on Tabular Datasets</a>                   | Jul 2023 |                                                                                                                                                                       | <details><summary>Show</summary>The paper discusses the need for a language describing distribution shifts in tabular datasets and its implications on algorithmic and operational interventions. It highlights the prevalence of Y/X-shifts (changes in conditional relationships between outcome and covariates) in tabular data. The authors build "WhyShift," an empirical testbed of curated real-world shifts, to characterize the type of shift and benchmark performance over it. The study emphasizes the importance of understanding distribution differences for methodological research and algorithmic development in handling distribution shifts effectively. The paper presents a comprehensive benchmark with specified shift patterns and evaluates various methods on multiple distribution shifts.</details>                                                                                                                                                                                                                                                                                                                                                                                                                       |
| <a href="https://arxiv.org/pdf/2307.08175.pdf">Multi-Objective Optimization of Performance and Interpretability of Tabular Supervised Machine Learning Models</a> | Jul 2023 |                                                                                                                                                                       | <details><summary>Show</summary>The authors propose a model-agnostic framework for optimizing supervised machine learning models for tabular data, considering both predictive performance and interpretability. They quantify interpretability using three measures: feature sparsity, interaction sparsity, and non-monotone feature effects. The framework generates diverse models by treating hyperparameter optimization as a multi-objective problem and incorporating feature selection, interaction, and monotonicity constraints. They introduce an efficient evolutionary algorithm to solve the optimization problem. In experiments, the framework outperforms state-of-the-art models in terms of performance and interpretability.</details>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| <a href="https://arxiv.org/abs/2305.02997.pdf">When Do Neural Nets Outperform Boosted Trees on Tabular Data?</a>                                                  | May 2023 |                                                                                                                                                                       | <details><summary>Show</summary>In this work the authors conduct a comprehensive analysis of tabular data in machine learning, comparing 19 algorithms on 176 datasets and analyzing over 965 metafeatures. The debate on whether neural networks (NNs) or gradient-boosted decision trees (GBDTs) perform better on tabular data is explored, and the authors find that the difference in performance between the two approaches is often negligible. They also show that for many datasets, a strong baseline method or well-tuned GBDT is sufficient, and extensive hyperparameter tuning on NNs may not be necessary. The analysis reveals that GBDTs perform better on datasets with skewed and heavy-tailed feature distributions, while NNs excel on more regular datasets. The insights provided act as a guide for practitioners to choose the appropriate approach for their specific datasets. The codebase and raw results are made available for further research and comparison.</details>                                                                                                                                                                                                                                               |
| <a href="https://arxiv.org/pdf/2305.10308.pdf">Rethinking Data Augmentation for Tabular Data in Deep Learning</a>                                                 | May 2023 |                                                                                                                                                                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| <a href="https://arxiv.org/pdf/2304.12654.pdf">CoDi: Co-evolving Contrastive Diffusion Models for Mixed-type Tabular Synthesis</a>                                | Apr 2023 |                                                                                                                                                                       | <details><summary>Show</summary>In this work, the authors propose a method called CoDi for tabular data synthesis that utilizes two diffusion models to handle continuous and discrete variables separately but conditioned on each other. The two diffusion models are co-evolved during training by reading conditions from each other. Additionally, a contrastive learning method is introduced to further bind the diffusion models. The proposed approach significantly improves the quality of synthetic data over state-of-the-art methods, as demonstrated in experiments with 11 real-world tabular datasets and 8 baseline methods. The method effectively models the distribution of real-world tabular data by processing mixed-type tabular data in the proper spaces. The contributions of this work include separate training of diffusion models for continuous and discrete variables, co-evolving conditional diffusion models, and the introduction of a contrastive learning method to reinforce the binding between the models. The proposed CoDi method addresses existing challenges in tabular data synthesis and shows promising results in improving the quality, diversity, and sampling time of generated data.</details> |
| <a href="https://arxiv.org/pdf/2301.02819.pdf">EXCELFORMER : A Neural Network Surpassing GBDTs on Tabular Data</a>                                                | Jan 2023 | 1.outperforms GBTD on 28 public datasets 2.intra-feature / inter-feature attention 3.MIXUP for tabular data                                                           |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| <a href="https://arxiv.org/pdf/2207.08815.pdf">Why do tree-based models still outperform deep learning on typical tabular data?</a>                               | Jul 2022 | 1. new dataset benchmark 2. accounts for hyperparameter cost 3. MLPs not good at irregular target function/uninformative features/non-rotationally invariant features |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
