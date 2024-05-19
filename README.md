# Azerbaijani TextAnalytics in R
In this notebook, we explore the text corpus containing 50 documents with R language. 

## Dataset

The documents contain Azerbaijani blogs and are scratched from website kayzen.az by aznlp.

The dataset can be found at  [https://huggingface.co/datasets/aznlp/azerbaijani-blogs?library=true]

## What is in it

This compact project includes the necessary steps to analyze and clean text-based information with the help of various R packages. Examples of these tasks include stopword handling and punctuation removal. We were able to obtain a deep understanding of the intricate patterns and structures present in textual datasets by exploring tasks such as determining the longest words and sentences and examining word frequencies. Also, the use of a wide range of R packages, including as stringi, quanteda,  and zipfR, allowed for a more comprehensive approach to text analysis. 
When it comes to the dataset, the idea of analyzing the articles having various content sounded as a good idea. However, as soon as we started to analyze the text, we understood some of the challenges in text analytics. The dataset had high sparsity with 97%. We managed to filter and clean the stopwords and numbers which decreased the sparsity to 86.3% and continued with the analysis. We have also discovered unexpected things during data cleaning, such as:

1) Extensive problems with spelling
2) Words that are stuck together (no space)
3) Non-Azerbaijani words
These cases can be considered as huge bottlenecks since it is challenging to identify and clean them.
The lack of language support in almost all packages was also a huge problem and also an opportunity. 
