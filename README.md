# BanglaMedNER: A Gold Standard Medical Named Entity Recognition Corpus for Bangla Text

## Overview

BanglaMedNER is an annotated corpus designed for Medical Named Entity Recognition (MNER) in the Bangla language. This dataset supports the identification of medical entities such as Chemicals and Drugs, Diseases and Symptoms, and Anatomical structures. It aims to fill the resource gap for MNER in Bangla, promoting research and development in the field of Bangla Natural Language Processing (NLP).

## Corpus Details

The dataset consists of more than **117,000 tokens** with annotations in the standard **IOB2 format**, categorized into three main entity classes:

- **Chemicals and Drugs (CD)**: Includes names of drugs, proteins, enzymes, and pharmacological substances.
- **Diseases and Symptoms (DS)**: Comprises various diseases, syndromes, and medical conditions.
- **Anatomy (ANAT)**: Encompasses body parts, organs, tissues, and cells.

### Statistics

- **Total Tokens**: 117,152
- **Number of Sentences**: 9,000
- **Annotated Words with Medical Entities**: 27,353
- **Non-entity Words**: 89,494
- **Average Sentence Length**: 18.9 words

## Annotation Format

The corpus is annotated using the **IOB2 format**:

- `B-` prefix indicates the beginning of a medical named entity.
- `I-` prefix indicates the inside of a named entity.
- `O` tag indicates outside of any named entity.

## Citation

If you use this dataset in your research, please cite the paper:

Muntakim, A., Sadaf, F. and Hasan, K.A., 2023, December. BanglaMedNER: A Gold Standard Medical Named Entity Recognition Corpus for Bangla Text. In 2023 6th International Conference on Electrical Information and Communication Technology (EICT) (pp. 1-6). IEEE.

For more details, read the full paper [here](https://ieeexplore.ieee.org/document/10427966).
