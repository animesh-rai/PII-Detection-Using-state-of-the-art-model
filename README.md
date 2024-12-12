# Safeguarding Sensitive Data - Detection in Unstructured Text Using Cutting-Edge Transformer Architectures
Data Load: Learning Agency Lab - PII Data Detection
The project relies on a dataset available on Kaggle 4 which comprising close to 22,000
essays created by students engaging in a massively open online course. User can easily
download the dataset from kaggle website.  https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data/data

1. Sensitive_Data_Detection - EDA.ipynb:      This ipynb file contain exploratory Data analysis
2. pii_detection_using_distilbert.ipynb:      This notebook contains multiple experimentation with distilBERT model on PII detection dataset.
3. pii_detection_with_Longformer.ipynb:       This notebook contains multiple experimentation with Longformer model on PII detection dataset.
4. pii_detection_with_RoBERTa.ipynb:          This notebook contains multiple experimentation with RoBERTa model on PII detection dataset.
5. pii_detection_with_longformer_b.ipynb:     This notebook contains experimentation on balanced dataset using longformer model. So the model is trained basically on more number of records for less(3) epochs.
6. pii_detector_using_deberta.ipynb:          This notebook contains multiple experimentation with DeBERTa model on PII detection dataset.
7. pii_detector_using_deberta_b.ipynb:        This notebook contains experimentation on balanced dataset using DeBERTa model. So the model is trained basically on more number of records for less(3) epochs.
8. sensitive_data_inference_using_all_models.ipynb:   This notebook is used to inference the detection of senstive data on user provided text data. First it loads the trained models from google drive and then inference over it.
