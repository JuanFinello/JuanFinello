# Juan Finello


`Python` `SQL` `Bash` `R` `pandas` `SQLite / PostgreSQL` `Nextflow` `Docker` `Metabase` `scikit-learn` `Bioconductor`

---

## Current work · genomic surveillance

Most of it lives in private repositories (employer code). What is in them:

| | |
|---|---|
| **[Preprint classification system](https://github.com/JuanFinello/preprints-classification-system)** · public<br><br>LLM scoring of preprints against a five-criterion editorial rubric, grounded in ROR, OpenAlex, Semantic Scholar and Crossref rather than left to the model's word. Runs before the curation decision, not after.<br><br>`Python` `OpenAI` `Anthropic` `pdfminer` | **Publication ↔ sequence linking pipeline** · private<br><br>Replaces a manual daily process: ingests newly published articles, extracts the genomic accession identifiers they report and links them to sequences across 12 pathogen databases. 100,000+ articles processed, extraction validated against a curated ground truth (F1 ≈ 97%).<br><br>`Python` `SQLite` `Nextflow` `Crossref` `PubMed` |
| **Arbovirus genomics dashboard** · private<br><br>SQL data model consolidating publications, accessions, institutions and journals, plus a self-service BI layer for tracking which institutions publish using shared sequence data, where samples originate and how open-data adoption evolves.<br><br>`SQLite` `Metabase` `Docker` | **Accession ID extractor** · private<br><br>Nextflow pipeline that downloads PDFs by DOI and extracts genomic database accession identifiers from them, feeding the linking pipeline above.<br><br>`Python` `Nextflow` |

## Bioinformatics

| | |
|---|---|
| **[SARS-CoV-2 genome assembly](https://github.com/JuanFinello/Reference_guided_mapping_SARS-CoV-2_Genome)**<br>Reference-guided assembly from FASTQ reads.<br>`Bash` `bwa` `samtools` | **[Mpox NCBI data processing](https://github.com/JuanFinello/Mpox_NCBI_data_processing)**<br>Genomic data and metadata processing for surveillance.<br>`Python` `pandas` |
| **[RNA-seq differential expression](https://github.com/JuanFinello/Rnaseq_Analysis_For_Candida_Parapsilosis)**<br>*Candida parapsilosis* expression analysis.<br>`Shell` `DESeq2` | **[Gene Ontology enrichment](https://github.com/JuanFinello/Gene_ontology_analysis)**<br>GO enrichment in *Physcomitrella patens* mutants.<br>`R` `Bioconductor` |

## Applied data science

| | |
|---|---|
| **[Crop classification from satellite imagery](https://github.com/JuanFinello/Clasificacion-de-cultivos-utilizando-imagenes-satelitales)**<br>Supervised learning on multispectral bands.<br>`Python` `scikit-learn` | **[Image classification](https://github.com/JuanFinello/COMPUTER_VISION_clasificacion_de_imagen)**<br>Several neural network architectures compared.<br>`Python` `Keras` |
| **[Sentiment analysis](https://github.com/JuanFinello/Analisis_de_sentimientos-NLP)**<br>NLP classification of Yelp reviews.<br>`Python` `NLTK` | **[Customer segmentation](https://github.com/JuanFinello/Clusterizacion_de_clientes_KMEANS)**<br>K-Means clustering.<br>`Python` `scikit-learn` |
| **[Logistic regression model](https://github.com/JuanFinello/Modelo_de_regresion_logistica)**<br>Categorical outcome prediction.<br>`Python` `statsmodels` | **[Data visualization](https://github.com/JuanFinello/data_vis_ggplo2)**<br>Figures from my biology thesis.<br>`R` `ggplot2` |

---

[LinkedIn](https://www.linkedin.com/in/juan-finello-45b66a163/)
