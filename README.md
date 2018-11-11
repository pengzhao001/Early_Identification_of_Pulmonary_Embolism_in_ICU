## Project Title

Early Identification of Pulmonary Embolism in ICU

## Tools

SQL, Python, Tensorflow, Spark, a cloud computing platform hosted by the University of Missouri.

## Data

MIMIC III, a de-identified database of ICU stays at the Beth Israel Deaconess Medical Center. https://mimic.physionet.org/

## Background

Pulmonary Embolism (PE) is a life-threatening condition, which leads to 200,000 - 300,000 hospitalizations every year in the US. The symptoms of PE is non-specific, making the diagnosis hard and there is no gold standard available yet. Therefore, it's very easy to overlook PE and miss the best timing of treatment. PE is known to be able to affect the electrocardiogram (ECG) waves by increasing the pulmonary arterial pressure in proportion with the level of anatomic pulmonary vascular obstruction and exposing right ventricle to strain. It's possible to predict the onset of PE by monitoring the change in ECG waves using a recurrent neural network model. 

## Goal

The goal was to predict the onset of PE with patient's clinical attributes and ECG waveform time series data.

## Modelling

Clinical variables frequently associated with the diagnosis of PE were identified with contrast set mining. 
A supervised multivariate time series binary classification model (PE or no PE) was built based on Long Short-Term Memory (LSTM) recurrent neural network with the time series data of Q, R, S peaks, and complex durations of the ECG wave.

## Contributors (in Alphabetical Order)

Timothy Green, Yuanyuan Shen, Peng Zhao, Yan Zhuang

## My Role

Build the LSTM time series classification model. 
