---
title: 'Comparing OpenFace and Deep Learning Models for Deception Detection in Video Calls'
description: We introduce a new dataset of semi-controlled online meetings, where OpenFace performs well, and show that CNN-based facial Action Unit predictions outperform it on more challenging in-the-wild datasets.
background: /assets/theme/images/layout1_overview_onlyImage.jpg
image: /assets/theme/images/AUPredictions.png
categories: [Publication]
tags: [Conference, ActionUnits]

---

## Comparing OpenFace and Deep Learning Models for Deception Detection in Video Calls

Detecting deception remotely using only audio and video is tough, especially when facial cues are subtle and vary a lot between people. In this work, we focus on facial Action Units (AUs) to model expressions in a clear and interpretable way. We introduce a new dataset collected in a controlled setting with mock online sales meetings, where participants were instructed to deceive. We also compare our dataset with the Real-life Trial dataset. Our results show that CNN-based AU prediction outperforms OpenFace on large-scale AU benchmarks and in challenging real-world deception scenarios. However, OpenFace still works best in our semi-controlled mock sales setup, where it captures additional AUs. This study highlights the strengths and limitations of different AU-based approaches for automated deception detection.

![image](/deception/assets/theme/images/AUPredictions.png)

## Citing
```bibtex
@inproceedings{dinges2025comparing,
  title={Comparing OpenFace and Deep Learning Models for Deception Detection in Video Calls},
  author={Dinges, Laslo and Fiedler, Marc-Andr{\'e} and Al-Hamadi, Ayoub and Bershadskyy, Dmitri and Weimann, Joachim},
  booktitle={2025 14th International Symposium on Image and Signal Processing and Analysis (ISPA)},
  pages={231--236},
  year={2025},
  organization={IEEE}
}
```