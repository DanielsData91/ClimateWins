# ClimateWins: Machine Learning for Climate Prediction - Part 1

![ClimateWins](https://github.com/DanielsData91/ClimateWins/blob/main/Master%20Folder%20-%20Project%20ClimateWins/ClimateWins%20-%20Presentation.jpg)

## 📌 Objectives
ClimateWins aims to leverage machine learning to predict the consequences of climate change across Europe and potentially worldwide. This project analyzes data such as:
- Hurricane predictions from the National Oceanic and Atmospheric Administration (NOAA) in the U.S.
- Typhoon data from the Japan Meteorological Agency (JMA)
- Global temperature trends
- Various other climate-related datasets

## ❓ Key Questions
1. **How is machine learning used, and is it applicable to weather data?**
2. **Are there any ethical concerns specific to this project?**
3. **What have been the historical maximum and minimum temperatures?**
4. **Can machine learning predict favorable or dangerous weather conditions?**

## 🔬 Hypotheses
We tested our hypotheses using **Regression Analysis** and **Clustering Analysis**:
- **H1: Model Suitability** – Which ML models are best for accurately forecasting extreme weather conditions?
- **H2: Temperature Trends** – Can ML predict significant temperature increases in Europe over the next decade?
- **H3: Correlation Analysis** – What correlations exist between temperature and factors such as the economy, urban landscapes, and air quality?

---

## 📝 Project Description
As a **data analyst**, I evaluated whether machine learning models can predict future weather conditions. I tested supervised learning algorithms including **K-Nearest Neighbors (KNN), Decision Trees, and Artificial Neural Networks (ANNs)** to determine which model achieved the highest accuracy.

---

## 📂 Project Documentation
### 📁 1. Project Management Folder
- Contains the project brief, guidelines, and other supporting documents.

### 📁 2. Script Folder
- Jupyter Notebooks used for the analysis.
- **Note:** Due to file size limitations, maps exceeding 25MB are uploaded as a ZIP file on GitHub.

### 📁 3. Data Folder
#### 🔗 Data Access
- Available on Google Drive: [Original & Processed Datasets](https://drive.google.com/drive/folders/1zOnI7DctjCQZeQfCWsRGb0Nm7jzpzd6I?usp=drive_link)

---

## 🔍 Key Insights and Findings
📂 Available on Google Drive: [Final Presentation](https://drive.google.com/file/d/1xygIfhYYK9Hj4X_KvrVIFtoOIz6Vtbru/view?usp=drive_link)

### 🔹 1. How is machine learning used in weather data analysis?
Machine learning identifies patterns and rules from data to solve problems:
- **K-Nearest Neighbors (KNN):** Classifies and predicts outcomes based on proximity between data points.
- **Decision Tree Algorithm:** Uses a hierarchical structure to guide decisions based on input data.
- **Artificial Neural Network (ANN):** A network of interconnected nodes that recognize complex patterns through layered activation.

### 🔹 2. Ethical concerns in machine learning and AI
Machine learning can introduce various ethical issues:
- **Data Privacy:** Weather data should not contain personally identifiable information, such as GPS coordinates (not applicable in this project).
- **Environmental Impact:** Misrepresenting data can lead to decisions that harm ecosystems or biodiversity.
- **Data Accessibility:** Open access to weather data is crucial for preparing for extreme weather events.

### 🔹 3. Historical Temperature Extremes
Based on data from the European Climate Assessment:
- **Lowest Recorded Temperature:** –34.3°C at Sonnblick, Austria (Jan 13, 1968)
- **Highest Recorded Temperature:** 43.6°C in Belgrade, Serbia (July 24, 2007)

### 🔹 4. Can machine learning predict favorable or dangerous weather conditions?
- The **KNN model** achieved an **88% accuracy rate** in predicting whether the weather was pleasant on a given day.

---

## ✅ Conclusion & Next Steps
### 📌 Conclusion
- The **KNN model** demonstrated **88% accuracy**, making it a strong candidate for weather prediction.
- However, **accuracy varies by location**, indicating a need for further refinement.

### 🚀 Next Steps
- Further **optimization** of machine learning algorithms to improve accuracy.
- Exploring a **combination of supervised and unsupervised learning** for better performance.
- **Expanding the dataset** by incorporating data from additional weather stations to enhance model reliability.

--------------------------------------------------------------------------------------------------------------------

# ClimateWins: Machine Learning for Climate Prediction - Part 2

![ClimateWins](https://github.com/DanielsData91/ClimateWins/blob/main/Master%20Folder%20-%20Project%20ClimateWins/Project%20Climate%20Wins%20Part%202.jpg)

## 📌 Objectives
ClimateWins aims to leverage machine learning to predict the consequences of climate change across Europe and potentially worldwide. This project analyzes data such as:
- Identify weather patterns that deviate from regional norms in Europe.
- Determine whether the frequency of unusual weather patterns is increasing.
- Generate forecasts for future weather conditions over the next 25 to 50 years based on current trends, and identify the safest regions for people to live in across Europe.

## 🔬 Hypotheses
We tested our hypotheses using **Regression Analysis** and **Clustering Analysis**:
- **H1: Random Forest Model** – By optimizing a Random Forest model, we identified the most critical weather features for assessing safe living regions.
- **H2: Hierarchical Clustering** – Hierarchical clustering helps go beyond binary classification (typical vs. atypical) to uncover actionable weather pattern groupings
- **H3-1: CNN & GAN** – CNNs are effective for interpreting radar and satellite imagery, allowing for better classification of weather conditions and improved trend prediction.
- **H3-2: CNN & GAN** – GANs were used to generate synthetic weather data for training CNN models to predict conditions over the next 50 years

---

## 📝 Project Description
As a **data analyst**, I explored how machine learning models can be applied to predict **long-term weather conditions in Europe**. I tested algorithms such as **Random Forest**, **CNNs**, and **GANs** to identify which approach delivered the most accurate and actionable climate forecasts.

---

## 📂 Project Documentation
### 📁 1. Project Management Folder
- Contains the project brief, guidelines, and other supporting documents.

### 📁 2. Script Folder
- Jupyter Notebooks used for the analysis.
- **Note:** Due to file size limitations, maps exceeding 25MB are uploaded as a ZIP file on GitHub.

### 📁 3. Data Folder
#### 🔗 Data Access
- Available on Google Drive: [Original & Processed Datasets](https://drive.google.com/drive/folders/1zOnI7DctjCQZeQfCWsRGb0Nm7jzpzd6I?usp=drive_link)

---

## 🔍 Thought Experiments
📂 Available on Google Drive: [Final Presentation](https://drive.google.com/file/d/1EEPBS99ALh1waMl8N461SW0o99RxMq1c/view?usp=drive_link)

## 🔬 Thought Experiment #1: Assess Regions UsinG a random forest model
We tested our hypotheses using **Random Forest Model**:
- **Hypothesis**: By optimizing a Random Forest model, we identified the most critical weather features for assessing safe living regions.
- **Objective**: This helped determine the safest areas in Europe for the next 25 to 50 years.
- **Approach**: Hyperparameters were refined using grid search and random search techniques.
We compared unoptimized and optimized model results to assess improvements.
- **Result**: Optimization increased model accuracy from 58% to 65% across all weather stations but altered feature importance rankings. When analyzing a single station, optimization did not change accuracy.
Comparing both models allowed for deeper insights into feature importance in climate risk assessment.

## 🔬 Thought Experiment #2: Classifying Weather using Hierarchical Clustering
We tested our hypotheses using **Hierarchical Clustering**:
- **Hypothesis**: Hierarchical clustering helps go beyond binary classification (typical vs. atypical) to uncover actionable weather pattern groupings.
- **Objective**: We assessed whether unusual weather patterns are occurring more frequently.
- **Approach**: A dendrogram was created using weather station data, with Principal Component Analysis (PCA) applied to reduce dimensionality and optimize resource use.
- **Result**: The model consistently produced two clusters, suggesting a potential binary or tiered (low-mid-high) pattern segmentation.

## 🔬 Thought Experiment #3 - Part 1: Synthesizing Data to Improve Predictions
We tested our hypotheses using **CNN & GAN**:
- **Hypothesis**: CNNs are effective for interpreting radar and satellite imagery, allowing for better classification of weather conditions and improved trend prediction.
- **Objective**: Identify the safest places in Europe to live over the next 25 to 50 years.
- **Approach**: Developed a CNN model to classify radar images into categories (e.g., cloudy, rainy, sunny).
Applied Bayesian optimization to refine hyperparameters such as neuron count, batch size, and learning rate.
- **Result**: Initial (unoptimized) accuracy: ~11.54%. Optimized model accuracy: Increased to 93% after Bayesian tuning.

## 🔬 Thought Experiment #3 - Part 2: Synthesizing Data to Improve Predictions
We tested our hypotheses using **CNN & GAN**:
- **Hypothesis**: GANs were used to generate synthetic weather data for training CNN models to predict conditions over the next 50 years.
- **Objective**: This supports long-term forecasting based on current climate trends.
- **Approach**: GANs were trained to create realistic weather data. CNNs were then trained using this synthetic data for improved forecasting.
- **Result**: GAN-generated data achieved 100% realism with only 0.078% loss. Confusion matrix revealed some misclassifications, particularly between "cloudy" and "rain" or "shine"..

---

## ✅ Recommendations & Next Steps
### 📌 Recommendations
Data indicates that ClimateWins will gain the most value from investing in **GAN** and **CNN** optimization to improve weather pattern prediction.
**Why?**
- These models delivered the highest accuracy improvements
- They show strong potential to meet core project goals efficiently.

### 📌 Data and Algorithms Required
Data suggests that ClimateWins will derive the most value from investing resources in GAN and CNN optimization to predict weather patterns:
- This experiment showed the **highest jumps** in accuracy
- The project showed **immediate potential** for achieving key goals

### 🚀 Next Steps
- Further refine CNNs **using Bayesian optimization**.
- Train CNNs **with high-quality**, GAN-generated datasets.
- Gather and prepare **additional weather and radar data** for future model development.

---

## 📩 Contact & Contributions
- **Author:** Daniel Mueller
- **GitHub:** [DanielsData91](https://github.com/DanielsData91)
- **LinkedIn:** [Daniel Müller](http://www.linkedin.com/in/daniel-m%C3%BCller-profile)
- **Tableau Public:** [Daniel's Visualizations](https://public.tableau.com/app/profile/daniel.m.ller6696/vizzes)

🛠 Contributions, feedback, and collaboration are welcome!


or check out my other projects on <a href="https://danielsdata91.github.io/">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/> 

