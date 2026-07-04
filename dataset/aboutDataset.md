---
annotations_creators:
- other
language:
- ne
language_creators:
- machine-generated
license:
- apache-2.0
multilinguality:
- monolingual
pretty_name: np20ng
size_categories:
- 100K<n<1M
source_datasets:
- original
tags:
- nepali-newsgroups
- nepali-20-newsgroups
- np20ng
- nepali text classification
- natural language processing
- news
- headline
task_categories:
- text-classification
task_ids:
- multi-class-classification
---

# Dataset Card for [np20ng]

## Table of Contents
- [Dataset Card for [np20ng]](#dataset-card-for-dataset-name)
  - [Table of Contents](#table-of-contents)
  - [Dataset Description](#dataset-description)
    - [Dataset Summary](#dataset-summary)
    - [Supported Tasks and Leaderboards](#supported-tasks-and-leaderboards)
    - [Languages](#languages)
  - [Dataset Structure](#dataset-structure)
    - [Data Instances](#data-instances)
    - [Data Fields](#data-fields)
    - [Data Splits](#data-splits)
  - [Dataset Creation](#dataset-creation)
    - [Curation Rationale](#curation-rationale)
    - [Source Data](#source-data)
      - [Initial Data Collection and Normalization](#initial-data-collection-and-normalization)
      - [Who are the source language producers?](#who-are-the-source-language-producers)
    - [Annotations](#annotations)
      - [Annotation process](#annotation-process)
      - [Who are the annotators?](#who-are-the-annotators)
    - [Personal and Sensitive Information](#personal-and-sensitive-information)
  - [Considerations for Using the Data](#considerations-for-using-the-data)
    - [Social Impact of Dataset](#social-impact-of-dataset)
    - [Discussion of Biases](#discussion-of-biases)
    - [Other Known Limitations](#other-known-limitations)
  - [Additional Information](#additional-information)
    - [Dataset Curators](#dataset-curators)
    - [Licensing Information](#licensing-information)
    - [Citation Information](#citation-information)
    - [Contributions](#contributions)

## Dataset Description

- **Homepage:** To be updated
- **Repository:** To be updated
- **Paper:** Submitted for review
- **Leaderboard:** To be updated
- **Point of Contact:** To be updated

### Dataset Summary

This is a multi-class Nepali text classification dataset. Text are the news documents and labels are the news categories. It consists over 200,000 documents categorized into 20 different Nepali news groups. News documents from 10 different news sources are compiled into this dataset. Labeling is done using the category-specific news from the respective news portals.

### Supported Tasks and Leaderboards

- Multi-class text classification from news document
- Multi-class text classification from news headings
- News heading generation from news document

### Languages

- Nepali

## Dataset Structure

### Data Instances

The dataset consists over 200,000 Nepali news documents categorized into 20 different news categories.

### Data Fields

- **category:** News category
- **content:** News document (main text)
- **headline:** News headline
- **source:** News source from where the news is taken from

### Data Splits

The dataset is a whole dataset and is not splitted.

## Dataset Creation

### Curation Rationale

To develop and create a large-scale Nepali text classification dataset and releasing it to the public for further research and developments

### Source Data

#### Initial Data Collection and Normalization

Data are scraped from popular Nepali news portals such as Onlinekhabar, Nepalkhabar, Ekantipur, Ratopati, Gorkhapatra, Nepalipatra, Educationpati, Crimenews, etc.

#### Who are the source language producers?

News portals

### Annotations

#### Annotation process

Category labeling of news documents are automatically done as the documents are scraped from category-specific URLs of particular news source

#### Who are the annotators?

News portals

### Personal and Sensitive Information

This dataset does not possess any personal and sensitive information. However, the news content can possess some biasness and irregular information which might be sensitive and not quite related with the original author of the dataset

## Considerations for Using the Data

### Social Impact of Dataset

No issues.

### Discussion of Biases

Categories can be depended on how news portals have categorized them. Otherwise could cause some bias between them.

### Other Known Limitations

News summary are not included

## Additional Information

### Dataset Curators

Me myself.

### Licensing Information

Apache-2.0

### Citation Information

To be updated later (Paper submission in process)

### Contributions

Thanks to [@Suyogyart](https://github.com/Suyogyart) for adding this dataset.
