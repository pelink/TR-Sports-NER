
# TR-Sports-NER Dataset

The **TR-Sports-NER Dataset** is a domain-specific dataset designed for Named Entity Recognition (NER) tasks in the Turkish sports domain. It provides annotated data to enable the identification and classification of sports-related entities, supporting research in low-resource languages.

---

## Key Features

- **Domain-Specific Focus**: Tailored for the Turkish sports domain, covering entities such as players, teams, events, and more.
- **Multi-Level Annotation**: Includes both parent and child entity annotations for fine-grained entity recognition.
- **Multiple Formats**: Supports BIO and Non-BIO annotation schemes for flexibility in training and evaluation.
- **Entity Types**: Covers a diverse range of entities, including:
  - Person-related (e.g., players, coaches, referees)
  - Sports-specific terms (e.g., football, basketball)
  - Locations, organizations, and roles
  - Supporters, sponsors, and agreements

---

## Dataset Details

### Dataset Variations
Four versions are provided to suit diverse experimental needs:
  - **Parent Entity – Non-BIO**: Parent entities without BIO tagging (18 unique labels).
  - **Parent Entity – BIO**: Parent entities with BIO tagging (35 unique labels).
  - **Child Entity – Non-BIO**: Child entities without BIO tagging (28 unique labels).
  - **Child Entity – BIO**: Child entities with BIO tagging (55 unique labels).

---

## Usage

The dataset can be used to train and evaluate NER models, test annotation schemes, or explore explainability in NLP models for sports-related Turkish text.

### Access
The dataset is hosted on GitHub: [TR-Sports-NER](https://github.com/pelink/TR-Sports-NER).
