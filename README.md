# End_to_END_PDF_Q-A
## PROJECT DESCRIPTION
### This project is based on a web application by which we can chat (question answering) with a PDF file.
- The project is done by fine-tuning a pre-trained LLM model.
- I tried different types of LLM model such as BERT, roBERT, DistilBERT, ALBERT etc., and picked the one with highest accuracy.
- The dataset we used is the SQuAD json dataset. Their are two versions of the data.
- Version1: https://rajpurkar.github.io/SQuAD-explorer/
- Version2: https://www.kaggle.com/datasets/stanfordu/stanford-question-answering-dataset
## Tools Required
- Python, Pytorch(CUDA) https://pytorch.org/get-started/locally/
- Transformers for LLM models.
- MlFlow, DVC, GIT for model, data, pipeline tracking.
## Tracking URL
- MLFLOW_TRACKING_URI: https://dagshub.com/karmakaragradwip02/End_to_END_PDF_Q-A.mlflow
```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/karmakaragradwip02/End_to_END_PDF_Q-A.mlflow
export MLFLOW_TRACKING_USERNAME=karmakaragradwip02
export MLFLOW_TRACKING_PASSWORD=9ccb0f28354fcca6469017b32544fa0704b9c343
```
