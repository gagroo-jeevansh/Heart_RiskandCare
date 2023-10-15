# Heart_RiskandCare

## Problem Statement

Studies have concluded that per year from 2010-2015, well over $30 billion was spent on unnecessary hospital admissions on Cardiovascular diseases in India. There is a need to identify those most at risk earlier and ensure they get the treatment they need. The target is to predict and prevent unnecessary hospitalizations in cases of heart diseases and assist hospitals in managing their resources to best render service at unprecedented times.

## About

The entire idea can be broadly divided into three stages:

1. **Model-1: Admission Prediction and Urgency Score**
   - We have developed a machine learning model, Model-1, that predicts the need for patient admission.
   - Model-1 also provides an urgency score to new incoming patients, allowing the creation of a priority queue to identify higher-risk patients.

2. **Data Scraper**
   - To eliminate the need for manual data entry into our model, we have developed a Data Scraper that extracts required fields from any medical report and automatically fills the required inputs of the model.

3. **Model-2: Length of Stay (LOS) Prediction**
   - Based on supplementary medical input and tests, we have developed Model-2 to predict the Length of Stay (LOS) or Duration of Stay for every admitted patient.

4. **Bed Management Forecast Algorithm**
   - A mathematical algorithm provides hospitals with a forecast of estimated bed management and the number of days beds will sustain if the same rate of patient admission continues.

To ensure security and accessibility of data of all the admitted patients, the patient has been stored on ETH Blockchain (Ethereum). This has been done because LOS, primarily is a sensitive information.

An effort has been made to make the usage of the models user friendly, and hence, a minimalistic front-end using Streamlit has been designed.

## To Run the App<br>
```streamlit run Home.py``` (in the main directory)<br>
To view the patient database hosted on ethereum blockchain <br>
``` launch ganache ```<br>
``` signup/login a account in metamask ```<br>
``` npm run dev ``` (in the eth-patient-list directory)

