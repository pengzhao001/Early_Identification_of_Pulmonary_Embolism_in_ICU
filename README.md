# Project Title

Early Identification of Pulmonary Embolism in ICU

# Tools

SQL, Python, Tensorflow, Spark, a cloud computing platform hosted by the University of Missouri.

# Data

MIMIC III, a de-identified relational database of ICU stays at the Beth Israel Deaconess Medical Center. https://mimic.physionet.org/

# Goal

The goal was to predict the onset of Pulmonary Embolism (PE).

# Modelling

Clinical variables frequently associated with the diagnosis of Pulmonary Embolism (PE) were identified with contrast set mining. 
A supervised multivariate time series binary classification model (predict PE or no PE) was built based on Long Short-Term Memory (LSTM) recurrent neural network with the time series data of Q, R, S peaks, and complex durations.

# My role

Build the LSTM time series model. 
