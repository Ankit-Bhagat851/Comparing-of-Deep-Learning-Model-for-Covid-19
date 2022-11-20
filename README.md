# Comparing-of-Deep-Learning-Model-for-Covid-19
Pandemic, COVID-19 created tremendous suffering for masses across the world. It forced the countries to stop the economic activities, stay locked in houses, taking human lives at large scale, increasing the tremendous burden of social and economic infrastructure, poaching challenging governance processes and services especially health services, migration etc. The COVID-19 forced countries after countries iterative in many waves forcing them to adopt measures of lockdown, social distancing, mandatory mask-wearing, vaccination etc. Under such scenarios, to prepare the countries for future pandemics a detailed studies and in-depth analysis of COVID-19 waves and associated critical analysis is needed. The proposed work developed a deep learning based prediction model for infection rate prediction, fatality rate prediction etc. Additionally it also analyses the vaccination trends and gets deep insights about the COVID-19 spreading trends and vaccination trends and coverage. More specifically, the research work compares the deep learning models such as Recurrent Neural Network (RNN), Long short-term memory (LSTM), Bidirectional LSTM (Bi-LSTM), and Gated recurrent units (GRUs) for two COVID-19 waves and put forward the in-depth comparison and analysis. The proposed deep learning models give better accuracy and efficiency as compared to others with recent work in this domain.

Table 1 : Summary of the Data

||Daily Cases| Daily Death | Daily Vaccination |
|---|---|---|---|
|Min      |0                             | 0           |0                 
|Max      |414188                        |7374       | 12666050          
|STD      | 80328                        | 906         | 1965244           
|25\%     | 6400                         | 125         | 672294            
|50\%     | 18171                         | 354         | 1777637           
|75\%     | 46098                         | 689         | 3031644           
|count    | 830                           | 830         | 455               
|mean     | 45742.34                      | 631.13      | 2204752           
|median   | 24292.5                       | 354         | 1777637           
|Skew     | 2.65                          | 2.92        | 1.6               
|Kurtosis | 6.82                          | 9.56        | 3.55                        


Table 2: Parameter settings

||              RNN   | LSTM  | Bi-LSTM | GRU  |
|---|---|---|---|---|
Learning Rate   | 0.001 | 0.001 | 0.001   | 0.001 
TimeSteps       | 30    | 30    | 30      | 30    
Features        | 1     | 1     | 1       | 1     
Hidden units    | 1     | 1     | 1       | 1     
Training Epochs | 100   | 100   | 100     | 100   
Neurons         | 64    | 64    | 64      | 64    
Dropout         | 0.2   | 0.2   | 0.2     | 0.2   


Table 3: Evaluation Metrics

 |               |RNN   | LSTM  | Bi-LSTM | GRU|   
 |---|---|---|---|---|
MAE   | 14769.17 | 23723.92 | 19186.08   | 22599.50
MSE       | 3.77e+08    | 1.67e+09    | 9.98e+08      | 7.29e+08 
RMSE       | 19422.11     | 40924.28     | 31597.68       | 27006.51  
MDA    | 0.63     | 0.69     | 0.67       | 0.65    
EV | 0.96   | 0.82   | 0.89     | 0.93 


Table 4: Forecasted value of Daily Cases

 |       |1 day     | 3 day     | 7 day     | 15 day    | 30 day 
 |---|---|---|---|---|---|
RNN	    | 14372	    | 13451	    | 13916	    | 15695	    | 244665  
LSTM	| 10513	    | 10375	    | 10291	    | 10343	    | 156849  
BiLSTM	| 13398	    | 11900	    | 12091	    | 12373	    | 201576
GRU	    | 21497	    | 20397	    | 21531	    | 22918	    | 227323

