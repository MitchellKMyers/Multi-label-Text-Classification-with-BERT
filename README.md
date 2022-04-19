# Multi-label Text Classification with BERT
This project is based on the following paper:
- Tran, H. T., Vo, H. H. P., & Luu, S. T. (2021). Predicting Job Titles from Job Descriptions with Multi-label Text Classification. arXiv preprint arXiv:2112.11052.

## Steps to Reproduce Implementation
Please note that this project was implemented on Google Colab and Google Drive, both of which are required for simple reproduction.
1. First step is to download the required data files (two options):
   - To download untranslated Vietnamese data, you can access through this link: https://github.com/sonlam1102/job-prediction-multilabel-vietnamese/blob/main/dataset/full_dataset.zip
      - This option also requires translation of the dataset which can be done by using  `Translation_API_utility_notebook.ipynb` in `src`
      - In order for the experiments to run, the translated files must be named as: `en_labels.csv`, `en_test.csv`, `en_train.csv`
   - To download already translated data, you access through this google drive link: https://drive.google.com/drive/folders/1yaVh9Eb60TVZllV6I3WCZmWdWxjaczlB?usp=sharing

2. Create a new folder in Google Drive titled `MLC` and add `Multi_Label_Classification_BERT.ipynb` and `src` to it
4. To run code, ensure that all three `.csv` files are uploaded directly to `Multi_Label_Classification_BERT.ipynb`. This can be done by clicking on the file icon on the left side of the colab page and simply dragging the files from your local system to the sidebar.
5. Once steps 1 to 4 are complete, you will be free to run the remaining code and experiment with our model.

## Notes
- Please note that training time is several hours due to model complexity and training size.
- If you prefer not to train your own network, you can download our models weights from this link: 
https://drive.google.com/file/d/1fgj6oCSNfYisZvnlRTjjXjdxouD7WuSH/view?usp=sharing


