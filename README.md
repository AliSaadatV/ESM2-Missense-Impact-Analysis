# Fine-tuning Protein Language Models to Understand the Functional Impact of Missense Variants

📄 **Published in:** *Computational and Structural Biotechnology Journal* (2025)  
🔗 [Read the paper here](https://doi.org/10.1016/j.csbj.2025.05.022) 

## 🧬 Overview

This repository contains the code and data for the paper  
**“Fine-tuning protein language models to understand the functional impact of missense variants”**  
(*Computational and Structural Biotechnology Journal*, 2025).

The study demonstrates how fine-tuned protein language models (PLMs), including **ESM2** and **ProtT5**, can predict protein features at amino acid resolution and provide **mechanistic interpretations** of missense variants.  

By comparing **fine-tuned** models with **frozen embedding classifiers**, we quantify the value of task-specific adaptation and use the resulting models to:
- Identify **protein features enriched** in pathogenic or benign variants  
- Provide **mechanistic insights** into how missense mutations alter protein structure and function  
- **Reclassify variants of uncertain significance (VUS)** under ACMG/AMP guidelines  

---

## 📘 Highlights

- Fine-tuned **ESM2** and **ProtT5** models using **Low-Rank Adaptation (LoRA)** for efficient training  
- Classified **20 amino acid-level protein features** including active/binding sites, domains, motifs, and secondary structure elements  
- Demonstrated **mechanistic variant interpretation** by comparing feature-level predictions for wild-type and mutant sequences  
- **Reclassified 6.5% of VUS** in *gnomAD* by integrating PLM-derived feature enrichments  
- Provided interpretable predictions supporting **functional and clinical variant interpretation**

## 💾 Data and Model Availability

- **Zenodo dataset and weights:** [zenodo.org/records/15441302](https://zenodo.org/records/15441302)

The Zenodo archive includes:
- Model checkpoints for fine-tuned and frozen embedding classifiers  
- Evaluation metrics and detailed feature-level results  
- Processed datasets used for training and analysis 

## Acknowledgment

Some notebooks were adapted or inspired by [this repository](https://github.com/RSchmirler/data-repo_plm-finetune-eval).
