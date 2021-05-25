# Neris_Thesis_FirstSubmission

Please find the datasets and the relevant code for the first submission of my thesis. 

Classification of documents: 

Youtube datasets were initially split into: 
1. cotrn.csv
2. hyptun.csv

Manipulation of posts from Reddit: 
1. pushshift20 + gbq19 data cleaning

Manipulation of comments from Reddit: 
1. comment_convert_to_csv_from_google_cloud_platform : sample notebook showing the process of obtaining csv versions of comments
2. comment concat and cleaning : brings all comment .csvs together and does basic data cleaning / pre-processing

Doc2Vec training: 
1. doc2vec_running_and_saving_models : notebook for running different doc2vec models, varying with embedding sizes
2. doc2vec_hyperparam_script : the script for preparing the corpus for doc2vec and training the specified model

Example of trained doc2vec model:
1. d2v_model_embdsize_256.model : the model where the vocabulary is reflected on a space of 256 dimensions

Scripts for benchmark / co-training models tuning and testing: 
1. co_training_script_benchmark_only
2. co_training_script_smaller_2_outcomes

Youtube dataset cleaning, benchmark / co-training models tuned, benchmark / co-training models tested in the notebooks: 
1. Youtube_dataset_prep_BENCHMARK_MODELS
2. Youtube_dataset_prep_co_training_scenario

Note: Due to memory constraints of the GitHub, the corpus collected from Reddit, most of the trained doc2vec models, cleaned corpus of Reddit have not been uploaded.  
