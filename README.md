# 📘 Research Pre-Reading & Literature Review Guide
## Brain-Computer Interface (BCI) & Genome Sequencing Projects

**Author:** Anand Kumar - Student Research Lead

---

## 📌 Overview

This repository provides a **structured pre-reading and literature review framework** for research teams working on:

- Brain-Computer Interface (BCI)
- Genome Sequencing / Computational Genomics

It ensures all participants reach a **minimum research-ready level** before implementation.

---

## 🎯 Objectives

Each team must be able to:

- Explain the problem statement clearly
- Understand dataset structure (input/output)
- Build a baseline model or pipeline
- Evaluate results using proper metrics
- Identify **2–3 research gaps**

---

## 🧠 BCI / EEG Teams (Group 1 & 2)

### 📖 Fundamentals

- EEG signals (brain electrical activity)
- Channels & electrode placement
- Sampling frequency (Hz)
- Brain waves:
  - Alpha (8–13 Hz)
  - Beta (13–30 Hz)
  - Theta (4–8 Hz)

- Noise sources:
  - Eye blink (EOG)
  - Muscle activity (EMG)

---

### 📚 Tutorials

#### MNE EEG Library
https://mne.tools/stable/auto_tutorials/intro/10_overview.html

#### EEG Preprocessing
https://mne.tools/stable/auto_tutorials/preprocessing/30_filtering_resampling.html

#### PyTorch Basics
https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html

---

### 📄 Papers

#### 1. Advances in EEG-based BCI
https://arxiv.org/abs/2007.16133

#### 2. EEGNet
https://arxiv.org/abs/1611.08024

#### 3. Cross-Subject EEG Generalization
https://arxiv.org/abs/2104.01233

#### 4. Inner Speech Decoding
https://arxiv.org/abs/2008.01786

---

### ✅ Expected Outcome

- Load and preprocess EEG data  
- Train CNN/LSTM model  
- Understand generalization issue  

---

## 🧬 Genome Teams (Group 3 & 4)

### 📖 Fundamentals

- DNA structure (A, T, G, C)  
- Genes and genome  
- Variants (mutations)  

#### Group 3 (Variant Focus)
- SNP  
- Insertions / deletions  
- Pathogenic vs benign  

#### Group 4 (Assembly Focus)
- Sequencing reads  
- Short vs long reads  
- Genome assembly  

---

### 📚 Tutorials

#### NCBI Genome Guide
https://www.ncbi.nlm.nih.gov/books/NBK20263/

#### Variant Basics
https://www.genome.gov/genetics-glossary/Variant

#### Scikit-learn
https://scikit-learn.org/stable/tutorial/basic/tutorial.html

---

### 📄 Papers

#### 1. Deep Learning in Genomics
https://www.nature.com/articles/s41576-019-0122-6

#### 2. DeepVariant
https://www.nature.com/articles/nbt.4235

#### 3. SPAdes Genome Assembly
https://genome.cshlp.org/content/22/5/824

#### 4. AI in Genome Sequencing
https://www.nature.com/articles/s41587-021-01139-4

---

### 📂 Data Formats

- FASTQ → Raw reads  
- VCF → Variant data  
- SAM/BAM → Alignment  

---

### ✅ Expected Outcome

- Understand sequencing workflow  
- Build ML model (Group 3)  
- Understand assembly pipeline (Group 4)  

---

## ⚙️ Common Requirements

### 🧑‍💻 Programming
https://docs.python.org/3/tutorial/  
https://pandas.pydata.org/docs/getting_started/index.html  

### 🛠 Tools
- GitHub  
- Matplotlib  

---

## 📅 Timeline (15 Days)

### Days 1–5
- Tutorials + basics  

### Days 6–10
- Read 4–6 papers  

### Days 11–15
- Prepare outputs  

---

## 📄 Deliverables

### Literature Review Table

| Paper | Method | Dataset | Result | Limitation |
|------|--------|--------|--------|------------|

### Research Gaps
- Identify 2–3 limitations  

### Proposed Approach
- Define solution (4–5 lines)  

---

## ⚠️ Important

- Do NOT start advanced models early  
- Focus on:
  - Dataset understanding  
  - Baseline implementation  

---

## 🚀 Final Note

This stage determines:
- Project quality  
- Research depth  
- Publication potential  

Skipping this will lead to weak outcomes.

---

## 📁 Suggested Repository Structure

```
project-root/
│
├── README.md
├── datasets/
├── notebooks/
├── src/
├── results/
└── papers/
```

---

## 📊 Evaluation Metrics

### BCI Tasks
- Accuracy  
- F1-score  
- Confusion Matrix  
- Cross-subject accuracy  

### Genome (Variant)
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

### Genome (Assembly)
- N50 score  
- Runtime  
- Memory usage  
- Error rate  

---

## 🧪 Minimum Implementation Requirement

Each team must:

- Run dataset successfully  
- Build baseline model/pipeline  
- Show at least one improvement  
- Generate 2–3 result graphs  

---

## 🚧 Common Mistakes

- Jumping to advanced models without basics  
- Ignoring preprocessing  
- Not evaluating properly  
- No baseline comparison  

---

## 🧭 Final Instruction

- Complete reading within **5 days**  
- Complete literature review within **15 days**  
- Only then start implementation  

---# neurogenomics-research-lab
