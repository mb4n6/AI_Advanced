# AI Advanced

This repository contains materials used in the **AI Advanced seminar**, including datasets, examples, and supporting resources for practical exercises in artificial intelligence and machine learning.

The goal of this repository is to provide participants with a **hands-on environment** to explore AI techniques, data analysis, and model experimentation.

---

# Contents

## Datasets

This repository contains multiple datasets used in the seminar exercises.

### 1. NSL-KDD Dataset

The repository includes the **NSL-KDD dataset**, a well-known benchmark dataset used in research on **intrusion detection systems (IDS)** and machine learning.

The dataset is a refined version of the original **KDD’99 dataset** and aims to address several of its limitations, such as redundant records and biased evaluation results.

Because publicly available datasets for network intrusion detection are limited, **NSL-KDD remains a widely used benchmark** for comparing different machine learning approaches.

---

### Available Dataset Files

| File | Description |
|-----|-------------|
| `KDDTrain+.ARFF` | Full training dataset with binary labels (ARFF format) |
| `KDDTrain+.TXT` | Full training dataset with attack types and difficulty level |
| `KDDTrain+_20Percent.*` | Reduced subset (20%) of the training data |
| `KDDTest+.ARFF` | Full test dataset with binary labels |
| `KDDTest+.TXT` | Full test dataset including attack types |
| `KDDTest-21.*` | Test dataset excluding the hardest difficulty level |

---

## Dataset Background

The **NSL-KDD dataset** was proposed to improve the evaluation of machine learning methods for intrusion detection.

Key improvements compared to the original **KDD’99 dataset** include:

- Removal of redundant records in the training set  
- Removal of duplicate records in the test set  
- More balanced sampling across difficulty levels  
- Reasonable dataset size that allows experiments on the full dataset  

These improvements help produce **more reliable and comparable evaluation results** for different intrusion detection methods.

---

## Synthetic Police Investigation Dataset

This repository also includes a **synthetic police investigation dataset** designed for educational purposes in AI, data science, and digital investigation analysis.

The dataset contains **500 synthetic investigation cases** and is intended to simulate simplified structures of investigative data.

The data can be used for:

- machine learning classification
- risk scoring
- exploratory data analysis
- data visualization
- ensemble model experimentation

⚠️ **Important**

The dataset is **fully synthetic** and does **not contain real investigative or personal data**.

---

### File

| File | Description |
|-----|-------------|
| `polizei_testdatensatz_500faelle.csv` | Synthetic dataset with 500 investigation cases |

---

### Dataset Structure

Each row represents a **synthetic investigation case**.

| Field | Description |
|------|-------------|
| `case_id` | unique case identifier |
| `deliktart` | type of offense |
| `tatmittel` | instrument or method used |
| `tatort_stadt` | city where the offense occurred |
| `tatzeit` | timestamp of the offense |
| `schadenshoehe_eur` | estimated financial damage |
| `anzahl_verdaechtige` | number of suspects |
| `vorstrafen_bekannt` | known previous convictions |
| `digitale_spuren` | digital traces available (0/1) |
| `gps_daten_vorhanden` | geolocation data available (0/1) |
| `video_cctv` | CCTV/video evidence available (0/1) |
| `risiko_klasse` | synthetic risk class (low / medium / high) |

---
