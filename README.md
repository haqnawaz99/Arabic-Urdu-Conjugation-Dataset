# Arabic-Urdu Conjugation Dataset

## Overview
This repository contains the **Arabic-Urdu Conjugation Dataset**, a first-of-its-kind linguistic resource for cross-lingual natural language processing (NLP) and educational applications. The dataset features over **14,400 entries**, comprising Arabic verb conjugations generated from triliteral, non-weak roots and their Urdu translations, aligned with detailed grammatical annotations.

## Features
- **Arabic Verb Conjugations:** Generated for 200 triliteral, non-weak Arabic roots.
- **Urdu Translations:** Grammatically aligned translations for each conjugation.
- **Grammatical Details:** Includes annotations for:
  - Gender (Masculine/Feminine)
  - Number (Singular/Dual/Plural)
  - Tense (Past Simple, Past Simple Negative, Present Simple, Present Simple Negative)
  - Person (First/Second/Third)
- **Validation:** Expert-reviewed by scholars of **Jamia Ashrafia Lahore**, ensuring linguistic and contextual accuracy.

## Dataset Structure
The dataset is provided in CSV format with the following columns:
- **Root:** The Arabic root of the verb.
- **Conjugation:** The generated Arabic verb conjugation.
- **Translation:** The corresponding Urdu translation.
- **Gender:** Gender of the subject (e.g., Masculine/Feminine).
- **Number:** Number of the subject (e.g., Singular/Dual/Plural).
- **Tense:** Verb tense (e.g., Past Simple, Present Simple).
- **Person:** Verb subject person (e.g., First/Second/Third).

## Applications
This dataset can be used in:
1. **NLP Research:** Develop and evaluate cross-lingual NLP models for Arabic and Urdu.
2. **Educational Tools:** Create tools for teaching Arabic and Urdu grammar.
3. **Machine Translation:** Support for low-resource language pairs like Arabic-Urdu.
4. **Linguistic Research:** Study morphological and grammatical similarities between Arabic and Urdu.


## How to Use
To download and use the dataset:
1. Clone the repository:
   ```bash
   git clone https://github.com/haqnawaz99/Arabic-Urdu-Conjugation-Dataset.git

## Citation
If you use this dataset in your research or applications, please cite the following paper:

> Haq Nawaz, Manal Elobaid, Ali Al-Laith, and Saif Ullah,  
> "Automated Generation of Arabic Verb Conjugations with Multilingual Urdu Translation: An NLP Approach,"  
> COLING 2025.  

You can use the following BibTeX entry for academic citations:

```bibtex
@inproceedings{nawaz2025arabic,
  title={Automated Generation of Arabic Verb Conjugations with Multilingual Urdu Translation: An NLP Approach},
  author={Nawaz, Haq and Elobaid, Manal and Al-Laith, Ali and Ullah, Saif},
  booktitle={Proceedings of the 1st Workshop on NLP for Languages Using Arabic Script (AbjadNLP 2025), COLING 2025},
  year={2025}
}

