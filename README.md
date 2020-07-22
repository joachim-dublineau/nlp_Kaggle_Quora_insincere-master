# nlp_Kaggle_Quora_insincere
Proposition for Kaggle's Quora Insincere question classification challenge. 

In this Notebook, the whole process is described, from data processing to model creation, training and testing.

We have used RNN and BERT.

REQUIREMENTS:
- PyTorch,
- Numpy,
- transformers (from Hugging Face)
- sklearn,
- Google Drive access.

Works fine on Google Colaboratory.

Remarks: 
- For now, the embedding dictionnaries are saved on our google drive the link being written in the notebook. In case the file isn't there anymore when reading this repository, you can download the embeddings yourself on https://www.kaggle.com/c/quora-insincere-questions-classification, and used the functions: create_dict_glove, create_dict_wiki and the commented code for word2vec to generate the .npy files, load these files in your Googe Drive, generate and replace the links and it wil work.
- On this link, you will find 2 pretrained models to avoid the training time. You just have to load them in your working environment:
https://drive.google.com/open?id=10P7VGXzScqMBN-H2MVJ3-fEP_tENhsYR.

This notebook is the result of the work of:

Joachim DUBLINEAU & Samuel MONTINI
