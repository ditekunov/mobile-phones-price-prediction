## Mobile-phones-price-prediction

Used dataset: https://www.kaggle.com/iabhishekofficial/mobile-price-classification

### Short description of the dataset:

| Feature name  |  Feature description                                  |  Type   |
|---------------|-------------------------------------------------------|---------|
| id            | ID                                                    | Numeric |
| battery_power | Total energy a battery can store in mAh               | Numeric |
| blue          | Has bluetooth or not                                  | Boolean |
| clock_speed   | Speed at which microprocessor executes instructions   | Numeric |
| dual_sim      | Has dual sim support or not                           | Boolean |
| fc            | Front Camera mega pixels                              | Numeric |
| four_g        | Has 4G or not                                         | Boolean |
| int_memory    | Internal Memory in Gigabytes                          | Numeric |
| m_dep         | Mobile Depth in cm                                    | Numeric |
| mobile_wt     | Weight of mobile phone                                | Numeric |
| n_cores       | Number of cores of processor                          | Numeric |
| pc            | Primary Camera mega pixels                            | Numeric |
| px_height     | Pixel Resolution Height                               | Numeric |
| px_width      | Pixel Resolution Width                                | Numeric |
| ram           | Random Access Memory in Megabytes                     | Numeric |
| sc_h          | Screen Height of mobile in cm                         | Numeric |
| sc_w          | Screen Width of mobile in cm                          | Numeric |
| talk_time     | Longest time that battery will last by a call         | Numeric |
| three_g       | Has 3G or not                                         | Boolean |
| touch_screen  | Has touch screen or not                               | Boolean |
| wifi          | Has wifi or not                                       | Numeric |



### Outcome binary metrics:

| Model name                  | Accuracy real | AUC-ROC real | Average |
|-----------------------------|---------------|--------------|---------|
| Logistic regression         | 98.83 %       | 98.85 %      | 98.84 % |
| Random forest with 80 trees | 95.83 %       | 99.49        | 97.66 % |
| Bootstrapped decision tree  | 95.67 %       | 99.49 %      | 97.58 % |
| Bagging cllassifier         | 95.00 %       | 99.43 %      | 97.22 % |
| KNN classifier with 98 NN   | 94.33 %       | -            | 94.33 % |
| Decision tree               | 93.50 %       | 93.53 %      | 93.52 % |
| Linear regression           | 71.69 %       | -            | 71.69 % |


### Outcome multi-class metrics:

| Model name                   | Accuracy real |
|------------------------------|---------------|
| Linear regression            | 91.66 %       | 
| Random forest with 250 trees | 88.50 %       |
| Decision tree                | 85.17 %       | 
| Logistic regression          | 79.50 %       |
| KNN classifier with 74 NN    | 65.00 %       | 
| Bootstrapped decision tree   | 43.67 %       |
| Bagging cllassifier          | 43.33 %       |


  
