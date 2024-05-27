# End-to-End-Question-Answering or Open Domain Question Answering
Note: you're better reading section "3. Some type of reader for reference " for understanding about QA reader before reading section  1 and 2

1. There are two parts on End-to-End-Question-Answering project:
- Document Reader: Read document and raise the answer for question.
  + Dataset: squad_v2
  + Demo code: [Demo]Reader_DistilBERT_QA.ipynb
- Document retriever: Retrieve equivalent document with the question (use faiss library)
  + Dataset: squad_v2
  + Demo code: [Demo]_HF_Faiss_Search.ipynb
2. End to End Question Answering: combine of Document retriever and Document Reader.
  + Dataset: squad_v2
  + Demo code: [Demo]_E2E_QA.ipynb
  + trained model for reference: tienhuynh/distilbert-finetuned-squadv2

3. Some type of reader for reference (demo code):
- Classification Approach:
  + Demo code (LSTM-based): Question-Answering Classification Approach.ipynb
- Extractive Approach:
  + Demo code (LSTM-based): Question-Answering Extractive Approach-LSTM-based.ipynb
  + Demo code (Transformer-based): Question-Answering Extractive Approach-Transformer-based.ipynb
  + Demo code (LSTM-based) and dataset is SQuAD Dataset: Question-Answering Extractive Approach-LSTM-based - SQuAD Dataset.ipynb
      

