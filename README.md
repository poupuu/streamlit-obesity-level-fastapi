# Obesity Prediction with Streamlit & FastAPI

## Summary:
Predicts obesity categories based several related data for classification model that exported into pkl to deploy into streamlit with FastAPI as backend

## Problem:
Obesity is a major health issue, early identification for risk prevention is a key, the goal is to create an accessible tool that can:
1. Classify an individua's weight category based on lifestyle factors
2. Provide a simple interface for users to get immediate, data-driven feedback to their risk level

## Methodology:
1. EDA & Preprocessing 
2. Modeling
3. Evaluation
4. Export into Pkl format
5. Setup Streamlit - open fast_api.py - new terminal type: uvicorn fast_api:app --reload
6. Deploy Streamlit - open streamlit_app.py - new terminal type: streamlit run streamlit_app.py

## Skills:
1. Python: EDA, cleans, preprocess data, modeling, evaluation, and exporting data into pickle
2. API & Backend: building REST API with FastAPI
3. Web App & Frontend: creating interactive app with streamlit for user input

## Results:
1. Real-time classification user's obesity with adjustment from streamlit

## Next Steps
1. Add Model Explainability (XAI): why the model giving that prediction
2. Provide actionable advice based on classification results
