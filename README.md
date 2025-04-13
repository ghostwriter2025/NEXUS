# NEXUS

**Anonymized Sample Datasets and Demo Files**  
**Paper Title:** *NEXUS: Towards Accurate and Scalable Mapping between Vulnerabilities and Attack Techniques*

---

## 📂 Repository Overview

This repository provides anonymized sample datasets and demonstration files to support the review of our paper.  
No source code is included.

Each uploaded dataset contains **100 data samples**, covering different modules of the NEXUS pipeline.

---

## 🗂️ Dataset Structure

| File Name | Description |
|:---|:---|
| `1_ground_truth_builder.csv` | Outputs from the Ground Truth Builder module, mapping CVEs to initial TTP labels. |
| `2_attack_pattern_extraction_data_preprocessing.csv` | Preprocessed data used for attack pattern extraction, including cleaning and dependency parsing. |
| `3_attack_pattern_extraction_pattern_classification.csv` | Classification results for extracted attack patterns. |
| `4_dataset_enhancement_label_adjustment.csv` | Samples demonstrating label adjustment based on pattern and context refinements. |
| `5_dataset_enhancement_cve_sample_augmentation.csv` | Paraphrased and augmented CVE descriptions to address data imbalance and improve TTP coverage. |
| `6_model_adaptation_exact_match_signature_feedback_db.csv` | Feedback database entries capturing Exact-Match signatures for model adaptation. |
| `7_model_adaptation_behavioral_signature_feedback_db.csv` | Feedback database entries capturing Behavioral signatures to support broader generalization. |
| `8_apd_model_binary_dataset.csv` | Binary dataset for training the Attack Pattern Detection (APD) model. |

---

## 🎥 Demonstration Video

This demo illustrates the testing of four CVEs, feedback provision for a selected TTP, and the adaptation process in NEXUS. It highlights how initial predictions are made, feedback is integrated, and updates are reflected across related samples.

🔗 [View Demo Video](https://drive.google.com/file/d/1EQsQTYUn_l7e6bwuE5c_CJtr--y9KDXP/view?usp=drive_link)

---

## ⚖️ License Notice

© 2025.

The sample datasets and demonstration files in this repository are provided solely for the purpose of reviewing the paper  
*NEXUS: Towards Accurate and Scalable Mapping between Vulnerabilities and Attack Techniques.*

These materials are anonymized and intended exclusively for paper review.  
Reuse, redistribution, or modification outside the context of the review process is not permitted without explicit permission from the authors.

---
