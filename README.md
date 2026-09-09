<h1>Hi, I'm Giuseppe 👋</h1>

<h3>PhD Student in Computer Science @ University of Salerno — Computer Vision &amp; Deep Learning</h3>

I work on **robust and explainable deep learning for vision**: domain generalization in medical imaging, adversarial robustness of deepfake detectors, and spatio-temporal models for video. Below you'll find my publications, the competitions I've won, and the code behind most of them.

💼 [LinkedIn](https://www.linkedin.com/in/giuseppe-genito-961a841a7) · ✉️ ggenito7@gmail.com

---

## 🔬 Publications

- **Manifold-Guided Adversarial Attack of Deepfake Detectors via Dual-Branch Autoencoder Projection**
  *ACM International Conference on Multimedia (MM '26), 2026* — [doi.org/10.1145/3767308.3837703](https://doi.org/10.1145/3767308.3837703)
  DÆLTA, a black-box Latent Transformation Attack built on a dual-branch autoencoder. The solution that won the [ACM AADD Challenge 2026](https://iplab.dmi.unict.it/mfs/acm-aadd-challenge-2026/). I coordinated the team and led the experimental phase.

- **Dino2-DR: A Trustworthy and Explainable Vision Transformer for Cross-Domain Diabetic Retinopathy Grading**
  *IEEE/CVF ICCV Workshops (BISCUIT), 2025, pp. 584–593* — [paper](https://openaccess.thecvf.com/content/ICCV2025W/BISCUIT/html/Cascone_Dino2-DR_A_Trustworthy_and_Explainable_Vision_Transformer_for_Cross-Domain_Diabetic_ICCVW_2025_paper.html) · [code](https://github.com/CASALab-Unisa/Dino2-DR)
  Grew out of my MSc thesis: I designed and ran the full experimental campaign. New state of the art on cross-domain diabetic retinopathy grading.

- **A Streaming Pancreas Twin: Online Regression and Behavioral Clustering from CGM Data**
  *Extended abstract, [11th International Digital Public Health Conference (DPH 2026)](https://dphconf.org/programme-2/main-track/), Barcelona, June 2026*
  Presenting author — I gave the talk in the main track.

## 🏆 Awards

- 🥇 **1st out of 21 universities worldwide** — ACM AADD Challenge 2026 (deepfake detection)
- 🥇 **1st place** — [ITADATAhack 2025](https://journal.opendataplayground.com/itadatahack-2025/), CINI Data Science Lab national hackathon
- 🥇 **1st place** — [DataPizza × SIAE Challenge 2025](https://hackathon-siae.datapizza.com/), route optimization under constraints
- 🥈 **2nd place** — [ITADATAhack 2023](https://journal.opendataplayground.com/itadatahack-2023/), multiclass/multilabel classification of EU laws
- 🥈 **2nd place** — [Emotional Intelligence Hackathon 2024](https://journal.opendataplayground.com/emotional-intelligence-hackathon/), Milano Digital Week

---

## 👨‍💻 Projects

### 📺 Computer Vision

- **[Dino2-DR](https://github.com/CASALab-Unisa/Dino2-DR)** — Official implementation and pretrained models from our ICCV 2025 Workshop paper. DINOv2 fine-tuned for diabetic retinopathy grading under domain shift, evaluated with two protocols:
  - *Leave-One-Domain-Out (LODO):* six models trained on five of six public DR datasets (APTOS, DeepDRiD, FGADR, IDRiD, Messidor2, RLDR), each holding one domain out for testing.
  - *Fixed-Source Multi-Target (FSMT):* a single model trained on the two largest and most diverse datasets (EyePACS, DDR), then evaluated on the six held-out domains.
- **[Spoken Language Recognition without Audio](https://github.com/giusgenito/Spoken-Language-Recognition-without-Audio)** — Lip-reading model (ConvLSTM2D + feature-level fusion) that tells 8 spoken languages apart from video alone, with no audio signal.
- **[Brain Tumor Semantic Segmentation](https://github.com/giusgenito/Brain_Tumor_Semantic_Segmentation)** — U-Net built from scratch in PyTorch for tumour segmentation on brain MRI, with a hand-written training loop (early stopping, checkpointing, LR scheduling on the Dice coefficient).

### 🗣️ Natural Language Processing

- **[Emotion Detection on Twitter](https://github.com/giusgenito/Emotion-Detection-Challenge-on-Twitter)** — Multiclass emotion classification: TF-IDF over n-grams and a hard-voting ensemble of 10 heterogeneous models (XGBoost, LightGBM, SVM, MLP). 🥈 Milano Digital Week hackathon.
- **[Text Summarization with mBART](https://github.com/giusgenito/Text-Summarization)** — mBART fine-tuned on an Italian corpus scraped ad hoc from *Il Post*, evaluated with ROUGE and BLEU.
- **[Classification of EU Laws](https://github.com/giusgenito/ItaDataHack2023)** — Multiclass and multilabel classification of European Union laws into chapters and subchapters. 🥈 ITADATAhack 2023.

### 💾 Machine Learning &amp; Reinforcement Learning

- **[HDFS Log Anomaly Classification](https://github.com/giusgenito/HDFS-Log-Anomaly-Classification)** — Hierarchical anomaly detection on Hadoop file system logs at three levels of granularity (binary, multiclass, multilabel), with ADASYN/SMOTE rebalancing and LightGBM tuned via Bayesian optimization (Optuna). 🥇 ITADATAhack 2025.
- **[Q-Learning Trading Algorithm](https://github.com/giusgenito/Development-of-a-Trading-Algorithm-using-Q-learning-to-Maximize-Profits.)** — Reinforcement learning agent trained to maximize returns on historical market data.

### 📊 Data Analysis, GIS &amp; Databases

- **[Statistical Analysis of the mpg dataset](https://github.com/giusgenito/StatisticaEAnalisiDati)** — Exploratory and inferential statistics in R.
- **[Fuel Stations in Florence](https://github.com/giusgenito/Distributori-di-carburante-a-Firenze)** — Spatial analysis of fuel station distribution.
- **[Open Source Web Map with QGIS](https://github.com/giusgenito/Open-Source-Web-Map-with-QGIS)** — Interactive web map built with open source GIS tooling.
- **[MongoDB Interaction Interface](https://github.com/giusgenito/MongoDB_Interaction_Interface_using_Zara_Dataset)** — Query and visualization interface over a NoSQL Zara dataset.

---

## 🛠️ Tech Stack

**Languages:** Python · C++ · R · C# · Dart
**Deep Learning &amp; ML:** PyTorch · TensorFlow · Keras · Hugging Face · Scikit-learn · OpenCV · Optuna · XGBoost · LightGBM
**Data:** Pandas · NumPy · Matplotlib · Seaborn · NLTK
**Databases &amp; Tools:** MongoDB · MySQL · Git &amp; GitHub · Jupyter · Google Colab · Flask · LaTeX · Linux

---

## 📫 Connect

[<img align="left" alt="Giuseppe Genito | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="Giuseppe Genito | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

<br />

[linkedin]: https://www.linkedin.com/in/giuseppe-genito-961a841a7
[instagram]: https://www.instagram.com/giuseppegenitoo/

![Visitor Count](https://komarev.com/ghpvc/?username=giusgenito&style=flat-square)
