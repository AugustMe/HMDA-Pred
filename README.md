# Inferring Disease-Associated Microbes Based on Multi-Data Integration and Network Consistency Projection

# Inferring disease-related microbes via HMDA-Pred

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

## Citation：

If you use the code of this project, please cite our paper.  

@article{2020Inferring,  
  title={Inferring Disease-Associated Microbes Based on Multi-Data Integration and Network Consistency Projection},  
  author={Yongxian Fan, Qingqi Zhu, Meijun Chen and Wanru Wang},  
  journal={Frontiers in Bioengineering and Biotechnology},  
  volume={8},  
  year={2020},  
}  


## Contacts：

If you have any questions or comments, please feel free to email augustqq@163.com

