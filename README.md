# Awesome-Insurance-Fraud-Detection

## Top Insurance Fraud Detection Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Claims Fraud, Underwriting Fraud, Network Analytics, AI Scoring & SIU Investigation Support*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Insurance Fraud Detection**. These systems score policies and claims for fraud risk, detect organized networks, support Special Investigation Units (SIU), and help insurers reduce leakage while controlling false positives.



**Examples** include Shift Technology, FRISS, Featurespace, SAS Fraud Management, FICO Falcon, Feedzai, Sift, Fraud.net, Quantexa, DataVisor, Guidewire Predictive Analytics, BAE Systems NetReveal, and Actimize (the category leaders).



**Open-source emphasis**: Domain-specific insurance fraud platforms are almost entirely commercial. Practical open options center on **graph-based fraud toolboxes**, **anomaly detection libraries**, **entity-resolution frameworks**, and general ML pipelines that teams can adapt for claims and policy data. This section lists the strongest available open resources and is realistic about the insurance-specific gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Shift Technology](https://www.shift-technology.com/)**  

  AI-powered insurance fraud and claims intelligence platform focused on detecting fraud, errors, and recovery opportunities across the claims lifecycle.



- **[FRISS](https://www.friss.com/)**  

  Insurance-specific fraud detection platform covering underwriting and claims fraud with network analysis, scoring, and SIU support.



- **[Featurespace](https://www.featurespace.com/)**  

  Adaptive behavioral analytics platform used for real-time fraud and financial crime detection, including insurance and payments use cases.



- **[SAS Fraud Management / SAS Fraud Framework](https://www.sas.com/)**  

  Enterprise fraud and financial crime solutions from SAS, applied to insurance claims, underwriting, and related risk detection.



- **[FICO Falcon](https://www.fico.com/)**  

  Widely deployed fraud detection platform (historically strong in payments) also applied to insurance and broader financial crime scenarios.



- **[Feedzai](https://feedzai.com/)**  

  AI-driven fraud prevention platform used across financial services and increasingly in insurance and claims-related risk detection.



- **[Sift](https://sift.com/)**  

  Digital trust and fraud platform focused on online and transactional fraud; adaptable components used in insurance digital channels.



- **[Fraud.net](https://www.fraud.net/)**  

  Fraud detection and prevention platform offering AI models and consortium-style intelligence for various industries including insurance.



- **[Quantexa](https://www.quantexa.com/)**  

  Contextual decision intelligence platform using entity resolution and network analytics for fraud, financial crime, and risk use cases.



- **[DataVisor](https://www.datavisor.com/)**  

  AI fraud and risk platform specializing in detecting large-scale, coordinated fraud attacks using unsupervised techniques.



- **[Guidewire Predictive Analytics / Insurance analytics](https://www.guidewire.com/)**  

  Predictive and analytics capabilities within the Guidewire ecosystem supporting claims and fraud-related insights.



- **[BAE Systems NetReveal](https://www.baesystems.com/)**  

  Financial crime and fraud detection platform used by insurers and financial institutions for network analytics and investigation.



- **[Actimize (NICE)](https://www.niceactimize.com/)**  

  Financial crime and fraud management suite applied to insurance and broader enterprise fraud detection and investigation.



## Open-Source GitHub Projects

- **[UGFraud and graph-based fraud toolboxes](https://github.com/safe-graph/UGFraud)**  

  Open unsupervised graph-based fraud detection toolbox implementing MRF, dense-block, and related algorithms for bipartite and network fraud patterns.



- **[Rift and open graph fraud intelligence platforms](https://github.com/)**  

  Open-source graph-oriented fraud systems combining entity resolution, anomaly detection, hybrid ML, and investigative workflows.



- **[PyOD / anomaly detection open libraries](https://github.com/yzhao062/pyod)**  

  Comprehensive Python toolkit for detecting outliers and anomalies—commonly used as a building block in fraud scoring pipelines.



- **[Scikit-learn and open ML pipelines for fraud](https://github.com/scikit-learn/scikit-learn)**  

  Standard open ML library used to train supervised and semi-supervised fraud models on labeled claims and policy data.



- **[NetworkX / graph analytics open stacks](https://github.com/networkx/networkx)**  

  Open graph libraries for building and analyzing claim, policyholder, and provider networks to surface suspicious clusters.



- **[Entity resolution open frameworks](https://github.com/)**  

  Tools for deduplicating and linking parties, providers, and claims—critical for network fraud detection.



- **[Imbalanced-learn and fraud-class imbalance tools](https://github.com/scikit-learn-contrib/imbalanced-learn)**  

  Open libraries for handling rare-event (fraud) class imbalance in model training.



- **[Explainable AI open toolkits (SHAP, LIME)](https://github.com/shap/shap)**  

  Libraries that help investigators understand model scores—important for SIU trust and regulatory expectations.



- **[Case management open systems for investigations](https://github.com/)**  

  Open ticketing and case tools adapted for SIU investigation workflows (not insurance-specific).



- **[Synthetic data and fraud simulation open projects](https://github.com/)**  

  Tools for generating synthetic claims/policy data to test detection pipelines without exposing real PII.



### Additional Strong Open-Source Options

- Building network analytics with **open graph libraries + anomaly detectors** on claims and party data.

- Training supervised models with **scikit-learn / gradient boosting** where labeled fraud outcomes exist.

- Using open **entity resolution** to improve link analysis before commercial or custom scoring.

- Accepting that insurance-tuned models, real-time claims scoring, SIU case management, and proven false-positive control still favor commercial platforms (Shift Technology, FRISS, Featurespace, SAS, Feedzai, Quantexa, FICO, Actimize, etc.).

- Focusing open-source efforts on transparency of models, data ownership, and research/experimentation.



**Frameworks for building custom systems**: Ingest claims and policy data → resolve entities → build graphs of parties/providers → score with open anomaly or supervised models → route high-risk cases to investigators → monitor drift and fairness. Suitable for insurers with strong data science teams. Most carriers still rely on commercial insurance fraud platforms for production detection and operational integration.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Fraud detection systems process sensitive personal and financial data and can affect claim outcomes. Models must be validated for bias, accuracy, and regulatory compliance. Open-source or self-built systems require careful governance. This list is not legal, actuarial, or compliance advice.



---

**Made for insurance fraud leaders, SIU teams, and data scientists fighting claims and underwriting fraud.**

Let's keep detection effective, explainable, and as open as practical.
