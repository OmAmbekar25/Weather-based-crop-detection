




# **INDEX**


|**Sr. No**|**Topics**|**Page No**|
| :- | :-: | :-: |
|**1.**|**Abstract**|**6**|
|2\.|**Keywords**|**6**|
|3\.|**Introduction**|**7**|
|4\.|**Literature survey/study of existing solutions/products**|**9**|
|5\.|**Existing system**|**11**|
|6\.|**Proposed methodology/ system architecture hardware / software specification**|**12**|
|7\.|**Implementation**|**15**|
|8\.|**Result and Conclusion**|**20**|
|9\.|**Reference**|**21**|





**ABSTRACT**

Weather based crop Prediction is essential for precision agriculture, and machine learning (ML) models have become popular tools for accurate Prediction. This paper examines different types of machine learning used in product prediction, such as stepwise multiple linear regression, random forests, neural networks, and others. Monitoring studies using recorded data have predictive capabilities. Artificial Neural Networks, Random Forests and Support Vector Machines have been successfully implemented. Regression method was used to estimate crop production losses based on the previous year's statistics.

Weather data is important for machine learning models to predict crop yields and use this to improve weather and management systems. Use the training model to predict performance by building out a week's worth of events throughout the growing season. The final estimate is the mean scenario return function. Weather data is collected regularly and fed into ML models for crop Prediction.

**Keywords**: Weather Condition, Machine Learning, Random Forest, Soil

![ref1]


# **INTRODUCTION**


Weather based crop Prediction is an important part of precision agriculture. The ability to accurately predict crop yield can help farmers make informed decisions about crop management and resource allocation. Machine learning (ML) models have become popular tools in crop Prediction due to their ability to analyze large data sets and identify complex patterns. In this article, we explore the different machine learning models used in weather Prediction and how to use weather data to provide input to these models. We also discuss the importance of performance in assessing the accuracy of crop Prediction models.

Predicting climate-based crops is an important task for farmers and machine learning has emerged as an effective tool in this context. Many machine learning algorithms have been used for weather-based crop Prediction with reasonable accuracy and scalability for large datasets Machine learning models used in weather-based crop Prediction include multi horizontal models, random forests, neural networks, convolutional neural networks, recurrent neural networks, weighted histogram regression, interaction-based models, and association rule mining and decision tree.

Monitoring studies using recorded data, such as air quality and ground quality data, can be used to improve the ability to perform various types of behavior. Artificial neural networks (ANN), random forest, and support vector machines have been successfully used for weather-based crop Prediction. Linear regression method is used to estimate yield loss based on data analyzed in previous years. A web-based crop Prediction application was developed for farmers' use. The application recommends various crops for future planting and provides weather data and information. Recent studies have used a hybrid simulation crop model-ML model for yield prediction. For example, Everingham et al.

A random forest regression algorithm was used to estimate annual changes in sugarcane yields in northern Australia. Feng et al. suggested that combining machine learning with biophysical models could improve analysis of the effects of extreme weather conditions on crop yields in eastern Australia. While machine learning models produce good results in crop prediction, it can be difficult to explain why predictions are right or wrong due to the black box of these models .To predict crop yields, weather data is an important input for machine learning models.

Climate data creates a complete climate and control profile by collecting and predicting climate data and control in advance. Ideally, uncertainty in crop yield predictions will decrease as weather forecasts and data management are replaced by actual observations. Use the training model to predict performance by building out a week's worth of events throughout the growing season. These events contain unknown information that has been modified from information



found in previous years. The final weekly forecast is the average event of performance.

Weather data is constantly updated and fed into machine learning models to predict crop yields throughout the growing season. Machine learning models use weather data as input to predict crop yields and can be analyzed using a variety of techniques such as water distribution and other machine learning algorithms. Integrating climate data into crop forecast models is crucial for making informed decisions and developing strategies for resource allocation, food distribution and pricing security. Climate information is one of the factors affecting crop yield prediction models

.

Development of crop Prediction application on the web is an important factor in agriculture because farmers can use it to make decisions. However, this study has some limitations, such as relying on weather data, which is the only access to machine learning models.

“Weather based crop Prediction system using machine learning” provides insight into crop Prediction using multiple ML models based on weather data. This study demonstrates the effectiveness of multilinear, random forest, neural networks, and other models in accurately predicting crop yield with a relative root mean error of less than 8%. Successful applications of neural networks, random forests, and support vector machines in weather-based crop Prediction are also discussed.

# **LITERATURE SURVEY/STUDY OF EXISTING SOLUTIONS**

The potential of weather-based crop prediction systems to increase agricultural production and reduce hazards related to climate variability has attracted a lot of interest. Many studies have looked into different methods and strategies for creating precise models that predict crop yield based on meteorological	data.

Utilizing machine learning methods, such as support vector machines (SVM), random forests, and artificial neural networks (ANN), to assess historical weather data and its link with crop yields is one prevalent strategy in these systems. For example, studies by Xie et al. (2017) showed how well SVM predicted maize yields depending on meteorological factors like temperature and precipitation.

The creation and application of weather-based crop prediction systems still face difficulties, nevertheless. These include the quality and accessibility of meteorological data, the requirement for precise ground-truth crop yield data for model validation and calibration, and the inclusion of socioeconomic variables that affect agricultural results.

### **Benefits: -**
These are the main benefits that farmers can get from using machinery. Acquiring knowledge on their farms:

**More effectiveness:** This method detects patterns with more accuracy and efficacy. and conserving farmers' time and money because machine learning can assess a greater volume of data faster than other techniques.

**Higher agricultural yields:** Farmers may make better decisions that result in higher crop yields by utilizing a variety of data sources for analysis, such as weather patterns, soil quality, and historical machine learning algorithms.

**Lower costs:** By providing insights into crop development and health, machine learning may help farmers maximize the use of resources, such as water, fertilizer, and pesticides. This can reduce costs while lessening the environmental impact of agriculture.

**Early disease detection:** By using machine learning to detect early signs of agricultural illnesses, farmers may take proactive steps to halt the spread of illness and minimize crop loss. When the model is well trained, it can identify abnormalities much faster than people might, such as discoloration on growth size in the early stages of disease.

**Improved crop management:** By offering insights into variables such as soil moisture, temperature, and nutrient levels, ML algorithms can assist farmers in improving their crop

management tactics. This can assist farmers in making data-driven decisions

regarding the best time to water, fertilize, and sow their crops. Overall, using ML in crop

analysis and prediction can help farmers optimize their crop yields, reduce waste, and increase profitability while promoting sustainable farming practices.
### **Challenges: -**

While  machine  learning  can  greatly  aid  in  crop  analysis  and  forecast, There are other issues to take into account. The following are the primary challenges:

**Data quality:** The standard of the training data affects the precision and dependability of machine learning models. Agriculture can face difficulties in obtaining high-quality data because to variations in the soil, climate, topography, and other environmental factors. Thus, collecting and preparing data may be challenging. explains the primary difficulties in deep learning-based fruit identification and recognition.

**Data volume:** To train machine learning models effectively, a lot of data is usually required. Agriculture can involve complicated large-scale data administration and collection, particularly for smaller farms.

**Model complexity:** It can be difficult to create machine learning models that fully take into account all the significant variables influencing crop development and output due to the complexity of agricultural systems. Deciding which model architecture is optimal for a particular crop analysis or Prediction task can be challenging and need in-depth knowledge.

**Interpretability:** Analyzing the outcomes of ML models, particularly those that use deep learning techniques, which are quite complex, can be challenging. Because of this, it may be difficult for farmers to comprehend the elements that go into making a particular crop prediction or suggestion.

**Accessibility:** It might be difficult to gain access to the hardware and software infrastructure needed for creating and implementing ML models in settings with low resources.

**Security and privacy:** These issues are related to the gathering, keeping, and application of private agricultural data. Maintaining security and privacy while permitting access to the data for machine learning research can be difficult.

**Human factors:** Farmers and other interested parties could require additional time to prepare for the adoption of novel techniques and technological advancements, like machine learning- based systems. Technology needs to be made more easily available, user-friendly, and ability to offer substantial advantages. To ensure that ML algorithms are efficient, practical, and morally sound, data scientists, farmers, and other stakeholders must work together to address these issues.

# **STUDY OF EXISTING SOLUTIONS**

The crop prediction systems that are now in use, as mentioned in the sources supplied, use machine learning algorithms and data analytics to anticipate crop yields, improve farming techniques, and help farmers make better decisions. To generate precise forecasts and suggestions, these systems combine a variety of technologies and data sources. The following are some salient features of the current crop forecast systems, as cited in the sources: Machine Learning techniques: The systems analyze data and make accurate crop yield predictions by using machine learning techniques including k-nearest neighbor, decision trees, SVMs, random forests, Hoeffding Tree, Bayes Net, Naïve Bayes Classifier, and more. Integration of Data to provide a complete picture of farming, they combine data from several sources, including weather patterns, soil condition, past crop yield statistics.
### **Benefits of the systems: -**
- Include better crop management.
- Early disease diagnosis, cheaper costs, higher crop yields, and more efficient decision-making for farmers.
- Particularized Suggestion To maximize yields and reduce risks, farmers receive tailored recommendations on crop selection, pest management, fertilizer use, and irrigation scheduling.
- Cut costs, enhance profits, make better crop management decisions, and create new goods and services.

The Best Crop to Choose Certain systems concentrate on providing farmers with advice on the best crops to grow on their land by using cross-classification techniques, weather data, and soil factors. These current crop prediction systems, which offer data-driven insights, show how technology may revolutionize agriculture.

# **PROPOSED METHODOLOGY/ SYSTEM ARCHITECTURE**

- ### **Collecting data: -**
Since data is the foundation of all research projects, it is essential to research writing. Data offers proof in favor of the theory, research question, and goals of the investigation. Developers can practice machine learning with datasets provided by Kaggle, a platform that runs competitions in machine learning. It contains a number of agricultural datasets, such as crop recommendation and forecast. The file has been downloaded for this investigation from the Kaggle dataset. This dataset contains Data for four distinct crops—rice, wheat, maize, and chickpea are included in the dataset.

With 550 cases for each crop, the dataset contains a total of 2200 occurrences. There are following parameters in the given dataset: -

**N**:   The   kg/ha   of   nitrogen   that   is   present   in   the   soil. **P**:   The   phosphorus   content   of   the   soil,   expressed   in   kg/ha. **K**:   The   kilograms   per   hectare   of   potassium   in   the   soil. **temperature**: The temperature during agricultural cultivation, expressed in degrees Celsius (°C).

**humidity**: The percentage (%) of relative humidity during the time of crop cultivation. **Ph**:	The	soil's	pH	level. **rainfall**: The total quantity of millimeters of rain that fell during the crop-cultivation season. **label**: The target variable that shows the crop variety that is advised in light of the specified environmental conditions.

In conclusion, the dataset contains a variety of environmental parameters, including rainfall, temperature, humidity, pH, and soil nutrient levels, that have an impact on crop growth. The crop type that is suggested in light of these environmental variables is the target variable.
- ### **Data Set Used: -**
###


- **Data Preprocessing: -**

After collecting datasets from various resources. Dataset must be preprocessing before training the model. The Data preprocessing can be done by various stages, beginning with reading the collected dataset the process continues to data cleaning. Certain redundant attributes found in the datasets during data cleaning are not taken into account for predicting crops. Therefore, in order to improve accuracy, we must remove undesirable attributes and datasets that contain missing values. These missing values must be removed or filled up with unwanted nan values. Next, specify the model's goal. Using the sklearn library, the dataset will be divided into training and test sets after data cleaning.

The data is not normalized, meaning that the values for each of the features are not on the same scale. This can create problems when working with certain machine learning algorithms that require all the features to be on the same scale. The dataset may contain missing or invalid data, which may need to be addressed before using it for machine learning. The dataset may require further feature engineering, such as creating new features, to improve the overall performance of machine learning models.
- ### **Crop Prediction: -**
The loading of external crop datasets is the initial step. We then read the dataset after that. After the data has been pre-processed, we use a decision tree classifier to train the models on the training set. To predict the crop, we consider several parameters such as pH of the soil, temperature, humidity,	and	expected	rainfall. These are the system input parameters that can be collected from the sensors or manually entered. There will be an additional list with the expected rainfall and input parameter values. The decision tree algorithm will    forecast    the    crop    based    on    list    data.


- ### **Crop Recommendation:** -
Based on the anticipated quantity of rainfall, the makeup of the soil, and the weather, the system will recommend the best crop to grow. This method also provides information on required fertilizers, such as nitrogen (N), phosphorous (P), and potassium (K), in grams per hectare, as well as the number of seeds required for a cultivation in kilograms per acre for a specified crop.




# **IMPLEMENTATION**
## **Workflow of system: -**
##


From the above figure we have summarized the decision-making process for the crop prediction system. This process begins with farmers providing the necessary conditions for crop production. These conditions may include information such as soil quality, weather conditions, water availability, etc. The information provided by the farmer is then entered into the system.

The system may be a computer program or database designed to process agricultural information. Data is entered into the data set. This step involves organizing the data into a structured format that can be used for analysis. Once the data is ready, a predictive model is created using an appropriate algorithm.

These algorithms analyze data to predict crop production potential under specific conditions. Then take a look at the output of your prediction model. These results indicate whether conditions are suitable for growing the crop. A decision that compares observed results to expected predictions. If the results match expectations, it means that landing conditions are good. If the conditions are good, the process will be completed and you will get good results when applying.

The product cannot be produced under the given conditions, if the conditions are bad the process ends with the conclusion that the product cannot be produced under the given conditions. This report provides examples of steps a farmer or agricultural analyst can take to use forecast information to make crop management decisions. This involves data entry, analysis, and decision-making based on the results of predictive models.






**Algorithms used: -**

We employed supervised machine learning with regression and classification as subcategories in our system.

Such as, Random Forest, Decision Tree, Naïve Bayes, K-Nearest Neighbour Among them the highest accuracy was of random forest classifier. Thus, we have use the random forest classifier.

It determines the proportion of correctly identified samples to all samples. Number of crops that are accurately labeled Correctness = Total Count of Crops. With high accuracy rates of 99%, 98%, 95%, and 97%, respectively, the Random Forest, Decision Tree, Naïve Bayes, and K-nearest Neighbor algorithms have performed fairly well, according to the data.

On the one hand, the accuracy rate of the Logistic Regression technique was just 92%. It's crucial to remember that criteria other than accuracy may be pertinent when evaluating a model's performance. Metrics such as recall, F1 score, and precision may provide more insight into the model's performance. It could be helpful to test and evaluate these models more carefully before making a decision.

#**CODE IMPLEMENTATION: -**

- **Importing dataset: -**















- **Different models used: -**

-**Accuracy of different models: -**














- **Model with highest accuracy: -**



- **Prediction Model: -**




# **CONCLUSION**
The suggested system will forecast the best crop to plant on a given plot of land based on soil composition and meteorological factors including temperature, humidity, soil pH, and rainfall. Through minimizing environmental impact, boosting resilience against climate change-related difficulties, and encouraging optimal resource utilization, a weather-based crop prediction system supports sustainable agriculture practices. For farming communities around the world, this system is essential to maintaining food security and economic stability since it encourages innovation and adaptation in agricultural operations.

All things considered, the application of a weather-based crop prediction system is a noteworthy development in agricultural technology that yields observable advantages in terms of increased resilience, productivity, and sustainability. In order to solve the intricate problems that face contemporary agriculture and ensure a bright future for global food supply, it is imperative that we embrace such technology solutions.


**Future Scope: -** In the future, this might be combined with other factors like water usage and soil quality to increase the precision of crop prediction models. Weather-based crop prediction systems have enormous potential to transform agriculture and support environmentally conscious practices, sustainable food production, and rural development in the future. These systems have the potential to enable farmers to make well-informed decisions, maximize resource allocation, and manage risks related to weather unpredictability and climate change by utilizing state-of-the-art technologies and scientific developments.




**REFERENCES**


1. Kusum Lata and Bhushan Chaudhari, "Data Mining Techniques and Machine Learning Models for Decision Support: Crop Yield Prediction" JETIR April 2019: "System."
1. Mishra Shruti "Use of Data Mining in Crop Yield Prediction," by Priyanka Paygude, ICISC 2018.
1. "A Review on Data Mining Techniques for Fertilizer Recommendation," Jignasha M. Jethva, Nikhil Gondaliya, and Vinita Shah, IJSRCSEIT 2018.
1. Crop Selection Method Based on Various Environmental Factors Using Machine Learning, Amit Kumar, Nishit Jain, Prajakta Kulkarni, and Vishal Pradhan, IRJET 2017. Avinash Devare, Mitalee Pendke, Ankit Pawar, Rohit Kumar Rajak, and "Crop Recommendation System to Maximize Crop Yield using Machine Learning Technique," IRJET 2017.
1. "Prediction of Rainfall Using Support Vector Machine and Relevance Vector Machine" by Pijush Samui, Venkata Ravibabu Mandla, Arun Krishna, and Tarun Teja.
1. "A Survey on Decision Tree Algorithms of Classification in Data Mining," Himani Sharma and Sunil Kumar.
1. "Crop Prediction System using Machine Learning Algorithms" by Pavan Patil, Virendra Panpatil, and Prof. Shrikant Kokate.
1. Wang, A., Desai, N., Lobell, D., Tran, C., n.d. Using remote sensing data, deep transfer learning is utilized to predict agricultural productivity.
1. In 2018, Shah, A., Kalbande, D.R., Gala, D., Hemnani, V., and Dubey, A. Crop yield prediction using regression techniques in an intelligent farming system. Singapore's Springer
1. Crop Yield Forecasting in the Canadian Prairies by Satellite Data and Machine Learning Techniques, Johnson, M.D. (2013). Thesis for master's program in atmospheric science, University of British Columbia.


