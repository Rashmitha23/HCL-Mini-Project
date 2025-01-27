

# 🌾 Crop Yield Prediction  

Agriculture is a cornerstone of the Indian economy, and predicting crop yield is essential for maximizing productivity and assisting farmers in making informed decisions. This project aims to predict crop yield using machine learning algorithms, helping farmers determine which crops to grow and when, based on various factors such as season, rainfall, and area.

The goal of this project is to create an accurate crop yield prediction model, leveraging machine learning techniques to support decisions on crop selection and farming strategies. The model compares the predictions made by different algorithms, such as **Logistic Regression**, **Naive Bayes**, and **Random Forest**, to determine the best algorithm for this task. The outcome of the analysis helps farmers maximize their yield, considering factors such as weather conditions, soil quality, and agricultural inputs.

---

## 🚀 **Project Overview**

This project focuses on predicting crop yield by applying various machine-learning techniques. The prediction models aim to help farmers decide which crops to grow based on historical data, environmental conditions, and other influencing factors.

**Key Objectives:**
- **Accurate Crop Yield Prediction**: Develop models to predict crop yield based on factors like temperature, rainfall, and area.
- **Machine Learning Models**: Compare and evaluate different machine learning algorithms (Logistic Regression, Naive Bayes, Random Forest) based on their prediction accuracy.
- **Data-Driven Decision Making**: Provide farmers with actionable insights to maximize crop productivity and choose the right crops for their land and conditions.

---

## 🛠️ **Tools & Technologies Used**

- **Jupyter Notebook**: The development environment for running and testing machine learning algorithms.
- **Python**: The primary programming language for implementing machine learning models.
- **Libraries**:
  - **NumPy**: For numerical operations and handling large datasets.
  - **Pandas**: For data manipulation and preprocessing.
  - **Matplotlib/Seaborn**: For data visualization and analysis.
  - **Scikit-learn**: For implementing machine learning algorithms such as Logistic Regression, Naive Bayes, and Random Forest.

---

## 📂 **Project Structure**

- **`crop_yield_prediction.py`**: Main Python file where machine learning algorithms are implemented.
- **`data_cleaning.py`**: Script to clean and preprocess the dataset for better accuracy.
- **`requirements.txt`**: Lists all the required Python packages to run the project.

---

## 🔧 **Installation & Setup**

### 1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-username/crop-yield-prediction.git  
   cd crop-yield-prediction  
   ```

### 2. **Install Dependencies**  
   Ensure you have **Python 3.x** installed, then install the necessary libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```

### 3. **Run the Model**  
   After installing dependencies, run the main Python script to train the models and make predictions:
   ```bash  
   python crop_yield_prediction.py  
   ```

### 4. **Data Preprocessing**  
   Before running the model, make sure the dataset is cleaned and formatted properly. You can run the preprocessing script to ensure the data is ready for modeling:
   ```bash  
   python data_cleaning.py  
   ```

---

## 📊 **Evaluation Metrics**

The performance of each machine learning algorithm was evaluated using the **Mean Absolute Error (MAE)**. Here are the results:

- **Random Forest**: Achieved the highest accuracy with the lowest MAE, making it the preferred model for predicting crop yield.
- **Logistic Regression**: Provided reasonable predictions but did not perform as well as Random Forest.
- **Naive Bayes**: Showed relatively lower accuracy compared to other algorithms.

---

## 🧑‍🌾 **Key Insights & Results**

- **Random Forest**: This algorithm produced the most accurate predictions of crop yield based on the given features, such as temperature, rainfall, and area.
- **Decision Support for Farmers**: By using the predictions, farmers can decide which crops to grow for maximizing yield in specific conditions.
- **Machine Learning in Agriculture**: This project bridges the gap between modern technology and traditional farming, providing data-driven tools for better decision-making in agriculture.

---



## 📈 **Future Improvements**

- **Integration with Weather APIs**: Incorporating real-time weather data to improve prediction accuracy.
- **Geographical Data**: Adding geographic data to account for variations in soil type and climate across regions.
- **Deployment**: Deploying the model as a web application for farmers to access predictions online.

---

## 📫 **Contact**  
If you have any questions or feedback, feel free to reach out!  
- **Email**: [rashmithapadmashetti1819@gmail.com](mailto:rashmithapadmashetti1819@gmail.com)  
- **LinkedIn**: [Rashmitha Padmashetti](https://www.linkedin.com/in/rashmithapadmashetti/)  


