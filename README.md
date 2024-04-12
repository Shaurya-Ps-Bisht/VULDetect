# VULDetect
A lightweight NLP based ensemble framework for source code vulnerability detection

## Problem Statement
Classification of C source code files as vulnerable or non-vulnerable using Deep learning and Word Embedddings.

## Data Source

- Custom dataset  [here!](https://www.kaggle.com/datasets/shauryapsbisht/vulnerable-c-source-code)
- Diversevul dataset [here!](https://drive.google.com/file/d/12IWKhmLhq7qn5B_iXgn5YerOQtkH-6RG/view)
- Draper dataset (link TBA)


## Directory Structure

F:.
│   README.md
│   requirements.txt
│
└───Notebooks
    ├───Embedding Models
    │   │   copy.ipynb
    │   │   embedding2.ipynb
    │   │   EmbeddingModels.ipynb
    │   │   ensemble1.ipynb
    │   │   fcnn.ipynb
    │   │   final Embedding.ipynb
    │   │   Stacked Generation Ensemble.ipynb
    │   │   Untitled.ipynb
    │   │
    │   └───.ipynb_checkpoints
    │           copy-checkpoint.ipynb
    │           embedding2-checkpoint.ipynb
    │           EmbeddingModels-checkpoint.ipynb
    │           ensemble1-checkpoint.ipynb
    │           fcnn-checkpoint.ipynb
    │           final Embedding-checkpoint.ipynb
    │           Stacked Generation Ensemble-checkpoint.ipynb
    │           Untitled-checkpoint.ipynb
    │
    ├───Main Models
    │   ├───.ipynb_checkpoints
    │   │       BiLSTM-checkpoint.ipynb
    │   │       BiLSTM_noCrossValidation-checkpoint.ipynb
    │   │       GRU-checkpoint.ipynb
    │   │       GRU-Copy1-checkpoint.ipynb
    │   │       GRU_noCrossValidation-checkpoint.ipynb
    │   │       LSTM-checkpoint.ipynb
    │   │       LSTM-Copy1-checkpoint.ipynb
    │   │       LSTM_noCrossValidation-checkpoint.ipynb
    │   │
    │   ├───30k
    │   │   │   bilstm_23.ipynb
    │   │   │   ensemble.ipynb
    │   │   │   gru_23.ipynb
    │   │   │   lstm_23.ipynb
    │   │   │
    │   │   └───.ipynb_checkpoints
    │   │           bilstm_23-checkpoint.ipynb
    │   │           gru_23-checkpoint.ipynb
    │   │           lstm_23-checkpoint.ipynb
    │   │
    │   ├───Custom Dataset
    │   │   │   BiLSTM.ipynb
    │   │   │   BiLSTM_noCrossValidation.ipynb
    │   │   │   GRU-Copy1.ipynb
    │   │   │   GRU.ipynb
    │   │   │   GRU_noCrossValidation.ipynb
    │   │   │   GRU_toSend.ipynb
    │   │   │   LSTM-Copy1.ipynb
    │   │   │   LSTM.ipynb
    │   │   │   LSTM_noCrossValidation.ipynb
    │   │   │   myImagePDF.pdf
    │   │   │   myImagePDF2.pdf
    │   │   │
    │   │   └───.ipynb_checkpoints
    │   │           BiLSTM-checkpoint.ipynb
    │   │           BiLSTM_noCrossValidation-checkpoint.ipynb
    │   │           GRU_noCrossValidation-checkpoint.ipynb
    │   │           GRU_toSend-checkpoint.ipynb
    │   │           LSTM-checkpoint.ipynb
    │   │           LSTM-Copy1-checkpoint.ipynb
    │   │           LSTM_noCrossValidation-checkpoint.ipynb
    │   │           myImagePDF-checkpoint.pdf
    │   │           myImagePDF2-checkpoint.pdf
    │   │
    │   └───Diversevul
    │       │   bilstm_2-Copy1.ipynb
    │       │   bilstm_2.ipynb
    │       │   customTokenzier.ipynb
    │       │   ensemble.ipynb
    │       │   fcnn_2.ipynb
    │       │   gru_2-Copy1.ipynb
    │       │   gru_2.ipynb
    │       │   lstm_2.ipynb
    │       │
    │       ├───.ipynb_checkpoints
    │       │       bilstm_2-checkpoint.ipynb
    │       │       bilstm_2-Copy1-checkpoint.ipynb
    │       │       customTokenzier-checkpoint.ipynb
    │       │       ensemble-checkpoint.ipynb
    │       │       fcnn_2-checkpoint.ipynb
    │       │       gru_2-checkpoint.ipynb
    │       │       gru_2-Copy1-checkpoint.ipynb
    │       │       lstm_2-checkpoint.ipynb
    │       │
    │       ├───.jupyter
    │       │   └───desktop-workspaces
    │       │           default-37a8.jupyterlab-workspace
    │       │
    │       └───without l1 l2
    │           │   bilstm_23.ipynb
    │           │   bilstm_diversevul.ipynb
    │           │   bilstm_div_w2v.pdf
    │           │   ensemble.ipynb
    │           │   gru_23.ipynb
    │           │   gru_diversevul.ipynb
    │           │   gru_div_w2v.pdf
    │           │   lstm_23.ipynb
    │           │   lstm_diversevul.ipynb
    │           │   lstm_div_w2v.pdf
    │           │
    │           └───.ipynb_checkpoints
    │                   bilstm_23-checkpoint.ipynb
    │                   bilstm_diversevul-checkpoint.ipynb
    │                   bilstm_div_w2v-checkpoint.pdf
    │                   ensemble-checkpoint.ipynb
    │                   gru_23-checkpoint.ipynb
    │                   gru_diversevul-checkpoint.ipynb
    │                   lstm_23-checkpoint.ipynb
    │                   lstm_diversevul-checkpoint.ipynb
    │                   lstm_div_w2v-checkpoint.pdf
    │
    └───Utilities
        │   json_to_df.ipynb
        │
        └───.ipynb_checkpoints
                json_to_df-checkpoint.ipynb