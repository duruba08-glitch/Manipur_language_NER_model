# Manipuri Named Entity Recognition (NER)

This project focuses on **Named Entity Recognition (NER) for the Manipuri language**. It provides a **custom dataset with annotations** to identify entities such as **Persons (PER), Locations (LOC), and Organizations (ORG)** in Manipuri text.

The dataset follows the **BIO tagging scheme** and is suitable for training NLP models like **BiLSTM**. It is designed to handle **prefixes, suffixes, surnames**, and **multi-token entities** commonly found in Manipuri. Both **Roman script** and **Meitei Mayek script** are supported.

---

## Features
- Custom annotated dataset for Manipuri NER
- BIO tagging format for sequence labeling models
- Handles multi-token names, prefixes, and suffixes
- Supports both Roman and Meitei Mayek scripts
- Suitable for training models like BiLSTM

---

## Example

**Sentence:**  
`Oinam Bishwamitra Singh went to Imphal.`

**BIO Tagging:**
```
Oinam        B-PER
Bishwamitra  I-PER
Singh        I-PER
went         O
to           O
Imphal       B-LOC
.            O
```

---

## Dataset Information
- Dataset was **collected, cleaned, and annotated manually**
- Focused on real-world Manipuri text
- Designed for supervised learning approaches