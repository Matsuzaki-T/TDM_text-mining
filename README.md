This repository contains the code and the dataset used for our manuscript. Module 3.0 enables automated extraction of titles and abstracts of indicated articles by PubMed ID.
Web-based application of module 3.0 is available [here](https://pubmed-exporter.herokuapp.com/).

## Software requirements
- Python >=3.9.12
- Numpy >=1.23.5
- Pandas >=1.5.2
- beautifulsoup4 >=4.12.0
- urllib3 >=1.26.15
- matplotlib >= 3.6.2
- matplotlib-venn >= 0.11.9
- pillow >=9.3.0
- wordcloud >=1.8.2.2
- spacy >=3.4.4
- scikit-learn >=1.0.2
- 
## Modules
-Module1.0 for producing Table1
-Module2.0 for producing Table2 from Table1. Table3 (corresponding to Supplemental Table2 and Figur2B) was prepared by data cleaning of Table2.
-Module2.1 for producing Table4 (corresponding to Figure2D) from Table3.
-Module2.2 for venn-diagram in Figure2C.
-Module3.0 for retrieving PubMed records of the indicated publications
-Module4.0 for word cloud analysis. WC1–4 (corresponding to periodI–IV in Figure3C) and WC5 (corresponding to Supplemental Figure) were prepared from Table11–14 and 16, respectively.
-Module5.0 for Latent Dirichlet Allocation (LDA). Table7–10 were used for LDA, producing Table23–45. Table32 (topic=19) was used for in Figure4. Table45 includes perplexity of each topic (Supplemental Figure2A).
-Module6.0 for word cloud analysis in Supplemental Figure2B.
-Module6.1 for word cloud analysis in Supplemental Figure3A–S.
-Module6.2 for word cloud analysis in Supplemental Figure3T.

## PubMed exporter
The ready to use web-based application for obtaining records comprising abstracts and titles of indicated publications.
![How to use](/Files/Figure 3A.pdf)
