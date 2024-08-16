# BurmeseCorpus
Burmese Language Corpus

## Directory structure

Each file contain atleast 150,000 sentences.

```bash
corpus
    |--- bm_corpus_1.txt
    |--- bm_corpus_2.txt
    ...
```

## Data Source

CC100 -> burmese -> [https://huggingface.co/datasets/cc100](https://huggingface.co/datasets/cc100)

### Dataset Description

This corpus is an effort to recreate the dataset used for training XLM-R, a multilingual model. It includes monolingual data for over 100 languages, along with data for romanized versions of certain languages (denoted by `*_rom`). The corpus was constructed using URLs and paragraph indices from the CC-Net repository, based on CommonCrawl snapshots from January to December 2018.

#### Key Features:

- **Languages Covered:** 100+ languages, including romanized versions.
- **Structure:** 
  - **Documents:** Separated by double newlines (`\n\n`).
  - **Paragraphs:** Within a document, paragraphs are separated by a single newline (`\n`).
- **Data Source:** Generated using the open-source CC-Net repository.
- **No Intellectual Property Claims:** No claims are made regarding the intellectual property of the corpus preparation process.

This corpus serves as a valuable resource for training and evaluating multilingual models, ensuring broad linguistic coverage and consistent formatting across different languages.

