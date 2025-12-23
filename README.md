# Dogs vs Cats – ML Image Classification (Evaluation Focus)

This repository contains an exploratory ML image classification project prepared collaboratively for a GDG session.

As a first hands-on ML project, the focus was on learning by building, with particular attention to how evaluation choices affect perceived model performance and generalisation.

---

## Overview
The goal of this project was to build and experiment with an ML image classification model to distinguish between dog and cat images.

Rather than optimising for maximum accuracy, the project prioritised understanding the end-to-end workflow and the impact of evaluation decisions during model development.

---

## Key Insight
Validation accuracy can become misleading once it begins to influence training decisions such as tuning epochs or other parameters.

A strictly held-out test set, evaluated only at the end, provides a more reliable indication of true model generalisation and helps avoid optimisation bias.

---

## Contents
- Google Colab notebook containing the full workflow:
  - Dataset loading and preprocessing
  - Train, validation, and test split strategy
  - Model training using transfer learning
  - Evaluation on an untouched test set
  - Optional interactive demo for qualitative inspection

---

## Collaboration
This project was developed collaboratively as a shared learning exercise.

**Contributors:**
- Saijalpreet Kaur
- Sukhmanjeet Kaur
- Aayush Kafle

All contributors worked together during experimentation, discussion, and preparation, without strictly divided roles.

---

## Notes
- This repository reflects a learning-focused project rather than a production-ready system  
- External resources were used for guidance, with emphasis on understanding and questioning results rather than copying outcomes  
- The primary focus is on evaluation discipline and correct interpretation of model performance
