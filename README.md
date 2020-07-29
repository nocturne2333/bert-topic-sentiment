# sentisum-topic-sentiment - dev
Topic Based Sentiment Detection using BERT

### Requirements
- transformers
- torch
- streamlit
- fastapi
- sklearn

## Train
Run ``

## Prediction API
Using FastAPI

Run `uvicorn prediction_api:app`

###  API Documentation
Swagger Docs at `http://127.0.0.1:8000/docs`

## Streamlit Interface
Run `streamlit run st_app.py`

App at `http://localhost:8501/`

## Planned Improvements
- Selective topic merging
- Trainer CLI
- Add visual metrics to Trainer
- Add colab notebook for data exploration
- Docker image
