# ML_ParaphraseDetection_Classifier

## Description
Utilizing DeBERTa and Microsoft Research Paraphrase Corpus for text similarity analysis and paraphrase classification, integrating cosine similarity metrics.
This project uses DeBERTa embeddings to detect paraphrases by calculating cosine similarity between sentence pairs. It includes data balancing, feature extraction, model training, and performance evaluation. For training, the model uses the Microsoft Research Paraphrase Corpus dataset that contains pairs of sentences and similarity classification. Two csv files in this corpus are implemented, `MSR_Paraphrase_test.csv` and `MSR_Paraphrase_train.csv`.

## Dataset

### Name
[Microsoft Research Paraphrase Corpus](https://www.microsoft.com/en-us/download/details.aspx?id=52398)

### Description
The Microsoft Research Paraphrase Corpus (MSRP) is a dataset created by Microsoft Research aimed at evaluating the performance of paraphrase identification systems. It contains pairs of sentences extracted from news sources on the web, which are manually annotated to determine whether the sentences in each pair are semantically equivalent.

### Instructions
To use the dataset with this project, follow these steps:

1. Download the dataset from [Microsoft Research Paraphrase Corpus](https://www.microsoft.com/en-us/download/details.aspx?id=52398).
2. Unzip the downloaded file to extract `MSR_Paraphrase_test.csv` and `MSR_Paraphrase_train.csv`.
3. Save the two files in format UTF-8 (Comma delimited)(*.csv).
3. Move the `MSR_Paraphrase_test.csv` and `MSR_Paraphrase_train.csv` files to the root directory of this project.