---
title: 'Uncovering Lies: Deception Detection in a Rolling-Dice Experiment'
description: First evaluation of a new multi modal deception detection approach using the Rolling dice experiment and the real life trial dataset.
background: /assets/theme/images/layout1_overview_onlyImage.jpg
image: /assets/theme/images/ROC.png
categories: [Publication]
tags: [Conference, RollingDice]

---

## Uncovering Lies: Deception Detection in a Rolling-Dice Experiment 

Deception detection is a challenging and interdisciplinary field that has garnered the attention of researchers in psychology, criminology, computer science, and even economics. While automated deception detection presents more obstacles than traditional polygraph tests, it also offers opportunities for novel economic applications. In this study, we propose a novel multimodal approach that combines deep learning with discriminative models to automate deception detection. We tested our approach on two datasets: the Rolling-Dice Experiment, an economically motivated experiment, and a real-life trial dataset for comparison. We utilized video and audio modalities, with video modalities generated through end-to-end learning (CNN). However, for actual deception detection, we employed discriminative approaches due to limited training data in this field. Our results show that the use of multiple modalities and feature selection improves detection results, particularly in the Rolling-Dice Experiment. Furthermore, we observed that due to minimized reactions, deception detection is much more difficult in the Rolling-Dice Experiment than in the high-stake dataset, quantified with an AUC of 0.65 compared to 0.86. Our study highlights the challenges and opportunities of automated deception detection for economic experiments, and our novel multimodal approach shows promise for future research in this field.

![image](/deception/assets/theme/images/ROC.png)

## Citing
```bibtex
@inproceedings{dinges2023uncovering,
  title={Uncovering lies: deception detection in a rolling-dice experiment},
  author={Dinges, Laslo and Fiedler, Marc-Andr{\'e} and Al-Hamadi, Ayoub and Abdelrahman, Ahmed and Weimann, Joachim and Bershadskyy, Dmitri},
  booktitle={International Conference on Image Analysis and Processing},
  pages={293--303},
  year={2023},
  organization={Springer}
}
}
```