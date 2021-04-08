# PredHMDA
Inferring disease-related microbes via HMDA-Pred

## How to use the tool?

Just run 'predict_tool.m' to produce the result.

## Data set：

interaction.mat：microbe and disease associations  matrix

## Program：

predict_tool.m：main interface for running the program

GSD.m：calculate Gaussian interaction profile kernel similarity for disease

GSM.m：calculate Gaussian interaction profile kernel similarity for microbe

cosSim.m: calculate cosine similarity for microbe and disease

LKF.m：fusion of Gaussian similarity feature and cosine similarity feature

NCPLDA.m：calculate microbe and disease space projection socres

Rank.m：sorting disease-related microbe scores

Write_file.m：write results to excel

## Operating environment：

software：matlab 2016a or later

processor：Intel(R) Xeon(R) CPU E5-1630 v4 @3.70GHz

recommended memory：8G
