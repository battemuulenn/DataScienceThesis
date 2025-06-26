# Fairness Metric Design Exploration in Multi-Domain Moral Sentiment Classification using Transformer-Based Models


## 📊 Datasets

### MFRC – Moral Foundations Reddit Corpus
- **Source**: [https://huggingface.co/datasets/USC-MOLA-Lab/MFRC](https://huggingface.co/datasets/USC-MOLA-Lab/MFRC)
- **Paper**: Trager et al., 2022 – *The Moral Foundations Reddit Corpus*  
  [https://arxiv.org/abs/2208.05545](https://arxiv.org/abs/2208.05545)

### MFTC – Moral Foundations Twitter Corpus
- **Source**: [https://osf.io/k5n7y/](https://osf.io/k5n7y/)
- **Paper**: Hoover et al., 2020 – *Moral Foundations Twitter Corpus: A Collection of 35k Tweets Annotated for Moral Sentiment*  
  [https://psyarxiv.com/w4f72](https://psyarxiv.com/w4f72)

  ### `Dataset/`
Contains the raw and unprocessed datasets used for model training, evaluation and novel fairness metric design exploration. Only the MFTC dataset is available in this folder, because the MFRC data can be pulled from the HuggingFace.

  ### `clean_data_for_experiments/`
Contains the final data that was used to fine-tune DistilBERT and BERT models for multi-label classification task. In total 5 moral labels, with approximately the same distributions of morality labels for both of the datasets.
  
  ### `data_cleaning/`
  Contains the data cleaning steps of the unproccessed raw data.

  
  ### `experiments/`
  Contains 2 notebooks with in-domain and cross-domain expreriments of DistilBERT and BERT models. Hyperparameter and other configurations are available inside. 


  ### `exploratory_data_analysis/`
  Contains in depth analysis of the initial raw datasets.

  
  ### `novel_fairness_metric_exploration_validation/`
  Contains the construction of the novel Moral Foundation Consistency metric, with relevant visualisations and Spearmans correlation analysis results.

  ### `results/`
  Contains the results of the in-domain and cross-domain classification results, as well as computed metrics.
