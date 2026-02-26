---
name: GAME
description: Buyer-Seller-Deception-Game dataset
background: /assets/theme/images/layout1_overview_onlyImage.jpg
permalink: /databases/GAME/
---

![image](/deception/assets/theme/images/Sessions_collage.jpg)

## Description of the Buyer-Seller-Deception-Game dataset (first Layout)
This dataset stems from a large-scale incentivized economic experiment focused on deception in buyer-seller interactions — a central issue in markets with asymmetric information. In our study, sellers were financially motivated to deceive buyers about a product’s true quality, mimicking real-world incentives in markets such as used cars or salary negotiations.

We recorded 500 high-resolution videos of online interactions in which participants engaged in a structured decision-making task. Sellers knew the true value (a card color) and had a clear incentive to mislead buyers; buyers had to detect deception to earn rewards. This setup reliably induces both honest and deceptive behavior under real financial stakes.

* The experimental design avoids common pitfalls in lie detection datasets:

* Ground truth is known with certainty.

* Participants are truly incentivized to lie well.

* Deceptive behavior is repeatable and cross-validated across participants using a round-robin design (each seller interacts with multiple buyers).

All videos were recorded under controlled lab conditions (4K webcams, 60 fps, stable lighting), with sound-isolated setups to ensure data quality. The experiment was built with oTree and MTVE and follows strict ethical and methodological standards as outlined in Bershadskyy (2024). A full replication package is included to support further data collection and extensions.

This dataset is a robust foundation for training and evaluating lie detection algorithms in economically relevant settings — offering higher realism and data quality than previously available resources.

## Release
__A full release of the database is planned and intended to be made freely available for academic use!__

Status Overview for Layout1:
* [x]  Publication of the database description in a peer-reviewed journal
    * 10 Feb 2026 – Paper accepted; publication coming soon
    * 26 Feb 2026 – Paper published: [https://doi.org/10.1016/j.iswa.2026.200636](https://doi.org/10.1016/j.iswa.2026.200636)
* [ ]  Post-processing and final consistency checks of the dataset
* [ ]  Legal review and compliance with data protection and institutional policies

![image](/deception/assets/theme/images/sample_video_heat.gif)

## Database Access 
* __Coming soon__

### Paper citation
When using this dataset, please cite the associated papers according to the license. A BibTeX entry is provided for convenience.

```bibtex
@article{DINGES2026200636,
title = {Buyer–Seller-Deception-Game Dataset: A new comprehensive dataset for facial expression based deception detection in economic contexts},
journal = {Intelligent Systems with Applications},
volume = {29},
pages = {200636},
year = {2026},
issn = {2667-3053},
doi = {https://doi.org/10.1016/j.iswa.2026.200636},
url = {https://www.sciencedirect.com/science/article/pii/S2667305326000116},
author = {Laslo Dinges and Marc-André Fiedler and Ayoub Al-Hamadi and Dmitri Bershadskyy and Joachim Weimann},
keywords = {New deception detection dataset, Facial action-units, EmotioNet, Audio, Experimental economics}
```

## Future Layouts
In the ongoing second layout, buyers can choose to receive assistance from an AI-based deception detection system after the seller's recommendation — or, in a sublayout, receive the true card color with 100% accuracy directly from the experimenter.

In upcoming layouts, we will increase the financial stakes and allow all participants to both deceive and detect deception. Unlike the fixed roles in the first two layouts (seller vs. buyer), roles will be assigned randomly to reflect more dynamic and complex negotiation scenarios.