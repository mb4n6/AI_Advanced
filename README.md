# AI Advanced

This repository contains materials used in the **AI Advanced seminar**, including datasets, examples, and supporting resources for practical exercises in artificial intelligence and machine learning.

The goal of this repository is to provide participants with a **hands-on environment** to explore AI techniques, data analysis, and model experimentation.

The materials are used in practical exercises covering:

- Machine Learning
- Ensemble Models
- Data Exploration
- Explainable AI
- Applied AI for security and investigation scenarios

---

# Datasets

This repository includes multiple datasets used in the seminar exercises.

---

# 1. NSL-KDD Dataset

The repository includes the **NSL-KDD dataset**, a well-known benchmark dataset used in research on **intrusion detection systems (IDS)** and machine learning.

The dataset is a refined version of the original **KDD’99 dataset** and aims to address several of its limitations, such as redundant records and biased evaluation results.

Because publicly available datasets for network intrusion detection are limited, **NSL-KDD remains a widely used benchmark** for comparing different machine learning approaches.

## Available Dataset Files

| File | Description |
|-----|-------------|
| `KDDTrain+.ARFF` | Full training dataset with binary labels (ARFF format) |
| `KDDTrain+.TXT` | Full training dataset with attack types and difficulty level |
| `KDDTrain+_20Percent.*` | Reduced subset (20%) of the training data |
| `KDDTest+.ARFF` | Full test dataset with binary labels |
| `KDDTest+.TXT` | Full test dataset including attack types |
| `KDDTest-21.*` | Test dataset excluding the hardest difficulty level |

## Dataset Background

The **NSL-KDD dataset** was proposed to improve the evaluation of machine learning methods for intrusion detection.

Key improvements compared to the original **KDD’99 dataset** include:

- Removal of redundant records in the training set  
- Removal of duplicate records in the test set  
- More balanced sampling across difficulty levels  
- Reasonable dataset size that allows experiments on the full dataset  

These improvements help produce **more reliable and comparable evaluation results** for different intrusion detection methods.

---

# 2. Synthetic Police Investigation Dataset

This repository also contains a **synthetic investigation dataset** designed for educational purposes in AI, data science, and digital investigation analysis.

The dataset simulates simplified investigative case information and can be used for experiments in:

- machine learning classification
- explainable AI

⚠️ **Important**

The dataset is **fully synthetic** and does **not contain real investigative or personal data**.

| File | Description |
|-----|-------------|
| `polizei_testdatensatz_v4_1200faelle.csv` | Synthetic dataset containing 1200 investigation cases |

---

# 3. PayPal Streaming Transaction Dataset

The repository also includes a **synthetic PayPal transaction dataset** designed for machine learning experiments related to **financial investigations and illegal streaming reselling (IPTV / PayTV)**.

The dataset simulates PayPal transactions of a suspected reseller account and can be used to train models that identify suspicious payment patterns.

Typical characteristics of suspicious transactions include:

- small recurring payments (10–50 EUR)
- peer-to-peer payments
- empty item descriptions
- free webmail domains
- evening or night activity
- occasional foreign counterparties

Normal transactions are mixed into the dataset to create **realistic feature overlap**, allowing meaningful ML training.

| File | Description |
|-----|-------------|
| `paypal_streaming_dataset_v3_ml_ready_1200.csv` | Synthetic PayPal dataset with 1200 transactions and ML label (`is_streaming_payment`) |

The dataset can be used for:
- feature engineering exercises
- classification model training
- explainable AI demonstrations

The dataset is **fully synthetic** and does **not contain real investigative or personal data**.

---

# Original Source (NSL-KDD)

The dataset is originally hosted by the **University of New Brunswick (UNB)**.

Since the original hosting location is no longer always available, this repository contains a preserved copy retrieved via the **Internet Archive**.

https://web.archive.org/web/20150205070216/http://nsl.cs.unb.ca/NSL-KDD/

---

# References

Tavallaee, M., Bagheri, E., Lu, W., & Ghorbani, A. (2009).  
*A Detailed Analysis of the KDD CUP 99 Data Set.*  
IEEE Symposium on Computational Intelligence for Security and Defense Applications.

McHugh, J. (2000).  
*Testing intrusion detection systems: a critique of the 1998 and 1999 DARPA intrusion detection evaluations.*  
ACM Transactions on Information and System Security.
