# Dengue_Analysis
Dengue! It is a fever which is caused by dengue virus in the tropical area. This fever is the biggest problem across the world mostly in the warm places or in the tropical areas. It is a virus/serious illness which is caused by the bite of mosquitoes (and it is especially caused by the bite of AEDES AEGYPTI species), people may not fall sick soon after biting of mosquitoes it takes one or two days to show his effect and after two days people fall sick with symptoms like veryhigh fever, high pain headache and in joints and muscles also, and suddenly red colour rashes appearing on the skin. Sometimes this fever might be lifethreatening also. Doctors find it tricky to diagnose because the symptoms of dengue are similar to illness like flu and all. The doctors usually checking for this type of symptoms and do some test to be sure and it is still hard to know that exactly how many people are visiting to doctors for the right diagnosis. To get more knowledge on this fever our Indian medical scientists are doing research and study on this, they are collecting information of patients from several hospitals, talking with people in village or who was affected by dengue, and at last looking at the lab results to see that how many dengue cases has been registered and in which area they affected mostly. The aim of this study is to understand the reason behind why some people are affected more often than others and what type of cure should be given to the patient at that time which will be good for his health. By figuring this out, we hope to find a better and best ways to stop dengue from spreading to people to people and keep society healthier and happier.

#Related Work
To understand how wide dengue fever spread over in certain areas, for that me and my team started a survey by creating a survey using google forms. We had sent this form to survey to the people who are living in the places where we are studying. The survey main aim was to uncover the factors that might influence people and make them aware that how many people are getting affected by this life-threatening dengue fever. These factors could be including the things like people or child age, where do the people live, and where they recently travels, what type of environment around them. People who took the survey answered the questions about themselves, their home and about their any recent sufferings in their family or friend or in neighbourhood. 
We have designed the survey questions based on the existing research on dengue fever and how it spreads from people to people. In the form we had asked people about their age, gender, how many people affected in their home, how much cleanliness they maintain in their home, how neat and clean they keep things and some more relevant question related to the dengue fever. We also tried to know that before had someone suffered from this fever or not and they have experienced any dengue symptoms before. To make sure, that our survey gave us the accurate information or not the experts in the public health and diseased outbreaks reviewed the questions. We also tested the survey with some group of people to check if any questions were confusing. When everything was clear and ready, we sent this survey to the social-media platforms like Facebook, twitter, Instagram and in the community groups and also to the local health clinics also.
After people finished the survey, we collected all their responses and make spreadsheet where we could analyse the data and make sure that every data was clean and accurate and consistent and also making sure that all the answers were formatted in the same manner. 

This pre-processing stage involved several steps, including:
Data Cleaning: means the removal of entries which are duplicate, or any incomplete responses, or any irrelevant or erroneous data.
Data Transformation: means converting the raw data into the understandable format.
Data Integration: mean combining of data from the multiple sources, to create a unique dataset for any further analysis.
Outlier Detection: means the data which is inadequate from the given data or the data which lie far away from the actual data. The way for handling outliers are by using statistical methods to prevent their influence on the analysis results.
Data Validation: means the verification of data integrity through cross-checking with external sources.
Data Normalization: means normalization of variables to ensure comparability and facilitate meaningful comparisons across different data subsets or study populations.
Sensitive Analysis: means conducting sensitivity analyses to assess the robustness of the results to variations in data pre-processing techniques and analytical methods.
Quality Control Checks: means the implementation of quality control checks to identify and rectify data entry errors, inconsistencies, and outliers that could potentially skew the analysis results.
Addressing Bias: mean examine the potential sources of bias, such as selection bias or response, and implementing strategies to minimize their impact on the study populations.
Additionally! We didn’t just rely on the surveys for cross checking the responses and to get more details we randomly selected some people who took the survey and interviewed them about their problems. In the depth discussion of this problem, we got extra information which was not possible to collect through the survey forms which helped us to understand the social and cultural factors, the people behaviours which influence how dengue fever spreads from people to people.

By looking at the existing research, cleaning up the survey data and combining it with the results from the detailed-interview, our study got a complete picture of how common the dengue fever is in this area. We studied about the various factors which affect people more and the well-rounded approach not only makes our finding more trustworthy but also it highlights our team management across different fields. By using various evidences to make a decision when tackling complicated public health issues like dengue forever.
 

#PROPOSED METHODOLOGIES ARCHITECTURE
Datasets:
Dengue Epidemiological Data: the dataset comprises of information collected from the various sources, like healthcare, community surveys, and laboratory reports which includes variables such as demographic characteristics, environmental factors, dengue incidence rates, and potential risk factors for dengue transmission are known as epidemiological data.

Data Pre-processing:
Cleaning: means removing the entries which are duplicate, and handling the missing values through imputation or deletion techniques, and address any inconsistencies or errors in the data.
Transformation: means convert the raw data into understandable data.
Integration: means combination of data from the multiple sources to create a unique dataset for analysis.
Outlier Detection: means data which is inadequate from the given data or the data which lie far away from the actual data.
Validation: means to verify data integrity through cross-checking with external sources or validation against established criteria.

Splitting the Data:
Training-Validation-Testing Split: means dividing the dataset into training, and then for validation, and then for testing sets to assess the model performance 
effectively.
Stratified Sampling: means to ensure that each subset is maintaining the same class distribution as the original dataset, and it is particularly important for imbalanced datasets.
Cross-Validation: means to utilize the techniques like: k-fold cross-validation technique to assess the model generalization and mitigate overfitting.

Machine Learning Models:
XG-Boost: it is also known as Extreme-Gradient Boost algorithm it is the very powerful algorithm which is used to optimize gradient boosting algorithm for its efficiency and effectiveness in handling large-scale datasets.

Model Training and Evaluation:
Train each ML-model on the training dengue dataset using techniques like grid search or random search to optimize model performance.Once the ML-model is fully trained then evaluate the model performance. We’ll 
keep a separate dataset to test the accuracy, precision, recall, and other skills and for the validation purpose we will be using the appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and area under the receiver operating characteristic curve (AUC-ROC).

Note- By following this approach, our aim is to develop a robust and powerful machine learning models that is capable to accurately predicting the dengue prevalence/outbreaks and should be able to identify or pinpoint the areas which has more risk factors for the virus transmission. This approach integrates data pre-processing, feature selection, model selection, and evaluation techniques to ensure the reliability and effectiveness of the predictive models in addressing the challenges posed by dengue fever.


#RESULTS AND DISCUSSION
The results of the proposed methodology for predicting dengue prevalence is that we will see the competition between the different ML models and from there we’ll analyse each model and their predicted accuracy using metrics we mentioned earlier. In this XG-Boost algorithms accuracy was high that is 91.5% in predicting the dengue virus outbreaks from the given survey data. There might be variations in the performance of the ML models, like in their overall accuracy predicting it can differ and this shows that each ML-models has potential to predict virus outbreaks.

Model Performance:
• The performance of each ML model (XG-Boost) is evaluated using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
• Results indicate that the XG-Boost model outperforms other models with an accuracy of 91.5% on the testing dataset, suggesting its efficacy in predicting dengue prevalence based on the selected features.
• Despite variations in performance metrics across models, all models demonstrate relatively high, accuracy levels, indicating their potential utility in dengue prediction tasks.The performance of the various ML-models was assessed using various metrics as mentioned in the above paragraph including accuracy, precision, recall, F1-score, and area under the ROC curve (AUC-ROC). 

#Model Accuracy Precision Recall F1-score, AUCROC
Random Forest 89.2% 0.87 0.91 0.89 0.92
KNN 86.5% 0.85 0.87 0.86 0.89
XG-Boost 91.5% 0.92 0.90 0.91 0.94
SVM 88.7% 0.88 0.86 0.87 0.9

The XG-Boost model achieved the highest accuracy of 91.5%, indicating its superior performance compared to other models.

Feature Importance: Illustrates the feature importance scores obtained from the XG-Boost model:


#DATA VISUALIZATION
Descriptive Statistics:
It is a subfield of statistics that deals with characterizing the features of known data and it is a branch of statistics focused on summarizing, organizing and preserving data in a clear and understandable way. Its primary aim is to define and analyse the fundamental characteristics of a dataset without making sweeping generalizations or assumptions about the entire data set.The main purpose of descriptive statistics is to provide a straightforward and concise overview of the data, enabling researchers or analysts to gain insights and understand patterns, trends, and distributions within the dataset.

Descriptive statistics typically involve measures of central tendency:
Mean: It is the sum of all components in a group or collection divided by the number of items in that group or collection.
For a series of observations: x̄ = Σx / n
were,
x̄ = Mean Value of Provided Dataset
Σx = Sum of All Terms
n = Number of Terms

Median: It is the value of the middle-most observations obtained after organizing the data in ascending order, which is one of the measures of central tendency. Median formula may be used to compute the median for many types of data, such as grouped and ungrouped data.
Ungrouped Data Median (n is odd): [(n + 1)/2]th term
Ungrouped Data Median (n is even): [(n / 2)th term + ((n / 2) + 1)th term]/2
were,
n = Number of Terms

Mode: It is one of the measures of central tendency, defined as the value that appears the most frequently in the provided data, i.e. the observation with the highest frequency is known as the mode of data. The mode formulae provided below can be used to compute the mode for ungrouped data.
Mode of Ungrouped Data: Most Repeated Observation in Dataset

Variance: Variance is calculated as average of squared departures from the mean. Variance measures the degree of dispersion in a data collection. The more scattered the data, the larger the variance in relation to the mean. To calculate the variance, square the standard deviation.
Symbol for variance is s2

Standard deviation: Standard deviation (s or SD) represents the average level of variability in your dataset. It represents the average deviation of each score from the mean. The higher the standard deviation, the more varied the dataset is.
Standard Deviation=n−1∑i=1n(xi−x)2
where:
xi=Value of the ith point in the data set
x=The mean value of the data set
n=The number of data points in the data set

Mean Deviation: It is used to find the average of the absolute value of the data about the mean, median, or mode. Mean Deviation is some-times also known as absolute deviation. The formula mean deviation is given as follows:
Mean Deviation = ∑n1 |X – μ|/n
were,
μ is Central Value

Co-variance: measures the direction of the linear relationship between two variables. It indicates how the variables tend to move together.
Range of Values: -∞ to +∞
Cor-relation: it evaluates the linear relationship between two continuous 
variables, but it goes a step further by standardizing the results.
Range of Values: -1 to + 1
Additionally, graphical representations like charts, graphs, and tables are commonly used to visualize and interpret the data
