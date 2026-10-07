# Hi, I'm Loreen Mahmoud

I'm a researcher working on **machine learning for network security**, with a focus on intrusion detection for **5G and Open RAN**. I completed my PhD in Computer Science & Engineering at the **Indian Institute of Technology (IIT) Roorkee** in August 2026.

My work aims to make security models **reliable, robust, and deployable**: models that not only score well on benchmarks, but keep working inside real networks, under real-time constraints, and under attack.

## Research interests

- Network intrusion detection
- Deep learning and transformer architectures for security
- Adversarial machine learning and robustness of AI-based detectors
- Zero Trust Architecture
- 5G / Open RAN security

## Projects

### ZORAN-Sec: Zero Trust intrusion detection for Open RAN
A Zero Trust-compliant intrusion detection framework that maps the policy decision and enforcement components onto the Open RAN architecture. At its core is **LightSecFormer**, a lightweight transformer for continuous, tabular network telemetry, built for resource-constrained inference.

- Deployed as an xApp on a testbed built with a real **srsRAN** base station and the **FlexRIC** Near-RT RIC
- Ingests live E2SM-KPM telemetry
- P99 processing latency of **0.75 ms** (about 13x below the 10 ms Near-RT RIC budget), 501 MB RAM, under half a CPU core

### DSEM-NIDS: Deep stacking ensemble for network intrusion detection
A deep stacking ensemble model designed to reduce false positive and false negative rates together, while keeping model complexity and scalability under control.

### ORAN-TWIN-IDS *(in progress)*
A dataset generation framework that extends benign Open RAN commercial traffic-twinning data with controlled, parameterised attack injection (DoS, scanning, and physical-layer interference) at two intensity levels. It produces over 3.6 million temporal windows described by 78 statistical features. Not yet published.

### Adversarial examples for intrusion detection
A method for generating adversarial examples against intrusion detection models using Logical Analysis of Data (LAD), a non-gradient technique.

## Publications

**Journal articles**
- L. Mahmoud, M. Liyanage, S. Gangopadhyay. *ZORAN-Sec: A Zero Trust–Compliant Intrusion Detection Framework for Open RAN With a Lightweight Transformer.* IEEE Open Journal of the Communications Society, vol. 7, pp. 6308–6333, 2026. [Link](https://ieeexplore.ieee.org/document/11547171)
- L. Mahmoud, M. Liyanage, J. Singla, S. Gangopadhyay. *DSEM-NIDS: Enhanced Network Intrusion Detection System Using Deep Stacking Ensemble Model.* IEEE Open Journal of the Computer Society, 2025. [DOI](https://doi.org/10.1109/OJCS.2025.3581036)

**Conference papers**
- L. Mahmoud, A. Hussain, S. Gangopadhyay. *Tabular or Image Input? Transformers for NIDS: A Comparative Study.* ICISC 2025, Springer, 2026. [DOI](https://doi.org/10.1007/978-981-95-8034-7_2)
- L. Mahmoud, S. Pillai, S. Gangopadhyay. *Interpretable Ensemble Learning Model for Enabling an IDS to Detect DNS Attacks.* ISPR 2024, CCIS vol. 2304, Springer, 2025, pp. 85–101. [DOI](https://doi.org/10.1007/978-3-031-82153-0)
- S. Chauhan, L. Mahmoud, T. Sheth, S. Gangopadhyay, A. K. Gangopadhyay. *Generating Adversarial Examples Using LAD.* IDEAL 2023, LNCS vol. 14404, Springer, pp. 154–165. [DOI](https://doi.org/10.1007/978-3-031-48232-8_15)
- S. Chauhan, L. Mahmoud, S. Gangopadhyay, A. K. Gangopadhyay. *A Comparative Study of LAD, CNN and DNN for Detecting Intrusions.* IDEAL 2022, LNCS vol. 13756, Springer, pp. 443–455. [DOI](https://doi.org/10.1007/978-3-031-21753-1_43)
- L. Mahmoud, R. Praveen. *Network Security Evaluation Using Deep Neural Network.* ICITST 2020, IEEE, pp. 1–4. [DOI](https://doi.org/10.23919/ICITST51030.2020.9351326)
- L. Mahmoud, R. Praveen. *Artificial Neural Networks for Detecting Intrusions: A Survey.* ICRCICN 2020, IEEE, pp. 41–48. [DOI](https://doi.org/10.1109/ICRCICN50933.2020.9296181)

## Tools and platforms

srsRAN · FlexRIC · O-RAN Near-RT RIC / xApps · deep learning and transformer models

## Contact

- Email: loreen_fm@cs.iitr.ac.in
- [Google Scholar](https://scholar.google.com/citations?user=ra6l3HEAAAAJ\&hl=en) · [LinkedIn](https://www.linkedin.com/in/loreen-mahmoud-363638152/) · [Webpage](sites.google.com/cs.iitr.ac.in/loreen-mahmoud)

Code for my published work is available on request.
