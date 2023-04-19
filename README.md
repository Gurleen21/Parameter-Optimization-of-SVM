# Parameter-Optimization-of-SVM
#### UCS654 Assignment

### Tasks Performed
1. Downloading Dataset
2. Data Preprocessing 
3. Creating 10 Samples with 70-30 ratio of training and testing Set
4. Creating Fitness Function
5. Calling Fitness Function for each sample to obtain optimized SVM parameters
6. Plotting Convergence Curve for the best sample

### Dataset Description
The dataset for the project has been downloaded from the UCI Machine Learning Repository.
Link for the Dataset: https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset

Dry Beans Dataset is used to classify the most well-known 7 types of beans in Turkey: Barbunya, Bombay, Cali, Dermason, Horoz, Seker and Sira, depending ONLY on dimension and shape features of bean varieties with no external discriminatory features.

Number of Instances: 13611

Number of Attributes: 17

### Final Result Table
#### Comparative Performance of optimized SVM with different samples:
<img width="446" alt="image" src="https://user-images.githubusercontent.com/79686365/233195428-d5bb3f25-38ba-4fcb-9e21-9d4cc0e06328.png">


### Convergence Graph
![image](https://user-images.githubusercontent.com/79686365/233195502-1f202b7b-8d52-43fa-8246-3a25d7329d77.png)

### Conclusion
The above graph is made for the sample which has best accuracy. Sample with id 5 has the best accuracy of 0.93 having kernel = Linear, Nu =0.05 and Epsilon = 2.19.
From the above graph, we can conclude that the SVM model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

### License
© 2023 Gurleen Kaur

This repository is licensed under the MIT license. See LICENSE for details.
[MIT](https://choosealicense.com/licenses/mit/)
