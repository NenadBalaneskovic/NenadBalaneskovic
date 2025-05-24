# External Machine Learning and AI driven Data Analysis Projects

## Introduction

This section lists some of the external projects involving various algorithmic Machine Learning and AI driven methods within the realm of data analysis in
technical, financial and physical domains which I had the opportunity to implement during my career. Most of them have been pursued 
with the intention of experimenting with numerous modern methods of mathematical physics, information and complexity theory in the 
context of their interaction with capabilities of advanced statistical inference used in the scope of contemporary data analysis.  

Machine learning, while not exclusive to physics, has become an invaluable tool in the field. It involves the use of algorithms and 
statistical models that allow computers to learn patterns from data and make predictions or decisions without explicit programming. 
In physics, machine learning is applied to analyze complex systems, identify patterns in experimental data, and simulate phenomena that 
would be computationally expensive using traditional methods. It is accelerating advancements in areas such as quantum mechanics, 
cosmology, and material science, helping researchers uncover insights that were previously unattainable.

Machine learning is a transformative computational technique that enables systems to learn patterns and make decisions based on data, 
without being explicitly programmed for every task. It relies on algorithms and statistical models, such as neural networks, decision trees, 
and support vector machines, to analyze vast and complex datasets. In physics, where phenomena often involve intricate systems and massive 
amounts of data, machine learning has proven to be a powerful tool for accelerating research and discovery.

In experimental physics, machine learning is employed to process and analyze data from sophisticated instruments, such as particle detectors, 
telescopes, and quantum devices. It helps physicists detect patterns, anomalies, or rare events that might otherwise go unnoticed, such as 
identifying gravitational waves or isolating quantum states. In computational physics, machine learning is used to optimize simulations, solve 
partial differential equations, and reduce the computational cost of modeling complex systems, like fluid dynamics or astrophysical phenomena.

Furthermore, machine learning has paved the way for new approaches to understanding fundamental physical laws. By training models on data from 
experiments and simulations, physicists can uncover hidden relationships and generate predictions about systems that are difficult to study directly. 
For example, machine learning has been used to predict material properties, simulate high-energy physics events, and even design new experiments.

Another significant application of machine learning in physics is in quantum mechanics and quantum computing. Machine learning aids in analyzing 
and optimizing quantum algorithms, as well as interpreting the outcomes of quantum experiments. These methods are crucial for advancing quantum 
technologies and harnessing their potential.

In summary, machine learning is revolutionizing physics by enabling researchers to handle the complexity and scale of modern scientific challenges. 
Its applications span experimental, theoretical, and computational domains, making it a cornerstone in shaping the future of physics research and 
technology development.

The context of the project list displayed below will grow continuously as new accomplished ML-driven data analytical studies and
their pdf reports become available.

## Project list

1. "Bank Marketing Campaign - Predictive Modeling"  

### Description  

This project analyzes customer responses to a bank's term deposit marketing campaign, 
employing machine learning to optimize predictive accuracy and improve future campaign strategies.

**Technologies and Python packages** used in the project:

### **📌 Technologies Used**
- **Machine Learning Algorithms**  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - XGBoost  
  - Ensemble Learning (Stacking, Bagging, Boosting)  

- **Data Preprocessing Techniques**  
  - Handling Missing Values (Imputation & Removal)  
  - One-Hot Encoding & Label Encoding  
  - Scaling & Normalization  
  - Class Balancing (SMOTE)  

- **Evaluation & Metrics**  
  - Accuracy, Precision, Recall, F1-Score  
  - Hyperparameter Tuning  

- **Visualization & Interpretation**  
  - Feature Importance  
  - Heatmaps & Correlation Analysis  
  - Confusion Matrix  

- **Deployment Methods**  
  - Pickle Storage for Trained Models  

---

### **🐍 Python Packages Used**
- **Core Libraries**  
  - `pandas` – Data manipulation  
  - `numpy` – Numerical computations  
  - `scikit-learn` – ML algorithms & preprocessing  
  - `xgboost` – Gradient boosting  

- **Data Preprocessing & Feature Engineering**  
  - `sklearn.preprocessing` – Scaling & encoding  
  - `imbalanced-learn` – SMOTE for class balancing  

- **Machine Learning & Model Evaluation**  
  - `sklearn.linear_model` – Logistic Regression  
  - `sklearn.tree` – Decision Trees  
  - `sklearn.ensemble` – Random Forest & StackingClassifier  
  - `sklearn.metrics` – Evaluation metrics  

- **Visualization**  
  - `matplotlib` – Plotting graphs  
  - `seaborn` – Statistical visualizations  

- **Deployment & Model Persistence**  
  - `pickle` – Saving models  

This setup ensures **efficient preprocessing, accurate ML modeling, proper evaluation, and reproducibility**. 

2. "Boarder Crossing Forecasting - SARIMAX Modeling"  

### Description  
 
This project attempts at forecasting the number of boarder crossings between USA and 
Canada based on the corresponding kaggle data set of The Bureau of Transportation Statistics (BTS) containing entries from 1996 to 2024, 
employing Python's SARIMAX forecasing scheme to optimize predictive accuracy and improve future security strategies.  

**Technologies** and **Python packages** used in the project:

---

### **📌 Technologies Used**
- **Time Series Forecasting**  
  - SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables)  
  - Fast Fourier Transform (FFT) for periodicity estimation  
  - Custom & automated cross-validation  
  - Grid search for hyperparameter tuning  

- **Data Engineering & Processing**  
  - DuckDB for data extraction and querying  
  - Pandas for data manipulation  
  - Aggregation techniques for monthly entry volume analysis  
  - Train/Test split for model validation  

- **Ensemble Learning & Optimization**  
  - Automated SARIMAX grid search  
  - Model parameter storage for reproducibility  

- **Evaluation Metrics**  
  - RMSE (Root Mean Squared Error)  
  - MAPE (Mean Absolute Percentage Error)  
  - Execution duration tracking  

- **Visualization & Interpretation**  
  - Forecast plots for historical trends and predictions  
  - Performance comparison of different SARIMAX models  

---

### **🐍 Python Packages Used**
- **Core Libraries for Data Handling**  
  - `pandas` → DataFrame operations & time-series manipulation  
  - `numpy` → Numerical computations  

- **Database & Querying**  
  - `duckdb` → SQL-style queries on structured datasets  

- **Time Series Forecasting & Statistical Modeling**  
  - `statsmodels` → SARIMAX model implementation  
  - `scipy.fftpack` → FFT-based periodicity detection  

- **Machine Learning & Evaluation**  
  - `sklearn.model_selection` → Train/Test split & cross-validation  
  - `sklearn.metrics` → RMSE & MAPE calculation  

- **Visualization Tools**  
  - `matplotlib` → Standard plotting for trends & comparisons  
  - `seaborn` → Advanced statistical visualizations  

---

This setup provides **strong predictive modeling capabilities, efficient data handling, and optimized forecasting methods**.

3. "Stock Price Forecasting - SARIMAX Modeling with Akima Interpolation"  

This project attempts at forecasting the temporal stock prices 
evolution based on a ficticious csv file containing daily stock prices by means of Akima interpolated stock price data subject to 
SARIMAX and critical point modeling implemented via the physical theory of critical phenomena.  

**Technologies** and **Python packages** used in the project:

---

### **📌 Technologies Used**
✔ **Time Series Forecasting**  
   - SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables)  
   - Akima Interpolation for trend smoothing  
   - Critical Point Analysis for volatility estimation  
   - Adaptive Trend Detection for stock price evolution  
   - Grid Search Optimization for SARIMAX parameter tuning  

✔ **Data Processing & Engineering**  
   - Data generation (synthetic stock prices)  
   - Feature extraction (first & second derivatives of price trends)  
   - Characterization of trend types (Bullish Surge, Sharp Decline)  
   - Structured CSV-based data storage for analysis  

✔ **Evaluation Metrics**  
   - RMSE (Root Mean Squared Error)  
   - MAE (Mean Absolute Error)  
   - $$R^2$$ (R-squared performance metric)  
   - Execution time tracking  

✔ **Visualization & Interpretation**  
   - Akima-interpolated stock prices  
   - Trend detection graphs  
   - SARIMAX-forecasted price plots  

✔ **Storage & Documentation**  
   - Model-generated forecasts stored in `critical_trends.csv`  
   - Markdown documentation with embedded references and research papers  

---

### **🐍 Python Packages Used**
✔ **Core Libraries for Data Handling**  
   - `pandas` → Data manipulation, CSV reading/writing  
   - `numpy` → Numerical computations  

✔ **Time Series Forecasting & Modeling**  
   - `statsmodels.tsa.statespace.sarimax` → SARIMAX forecasting model  
   - `scipy.interpolate.Akima1DInterpolator` → Akima interpolation for trend analysis  

✔ **Machine Learning & Optimization**  
   - `sklearn.model_selection` → Grid search hyperparameter tuning  
   - `sklearn.metrics` → RMSE, MAE, R-squared calculations  

✔ **Visualization Tools**  
   - `matplotlib.pyplot` → Standard plotting for trends and comparisons  
   - `seaborn` → Advanced statistical visualizations  

✔ **Storage & Model Persistence**  
   - `pickle` → Saving critical data trends for reproducibility  

---

This setup provides **robust time series forecasting, efficient stock price trend analysis, and reliable volatility estimation** using **SARIMAX and Akima interpolation techniques**.

4. "Sentiment Analysis Project - News Sentiment Evaluation"  

### Description 
This project analyzes sentiments of news headlines contained within the Groundnews website by means of a customized Pythonic GUI.  

**Technologies** and **Python packages** used in the project:

---

### **📌 Technologies Used**
✔ **Natural Language Processing (NLP)**  
   - Sentiment analysis using **NLTK VADER**  
   - Named Entity Recognition (NER) via **SpaCy**  
   - Keyword extraction  
   - Word Cloud visualization  

✔ **Web Scraping & Data Fetching**  
   - Fetching news headlines from **Ground News**  
   - **BeautifulSoup** for HTML parsing  

✔ **Graphical User Interface (GUI)**  
   - **PyQt5-based GUI** for interactive analysis  
   - **Real-time sentiment trend visualization** using **PyQtGraph**  

✔ **Data Processing & Export**  
   - **Pandas** for structured data handling  
   - CSV storage for analysis results  
   - PNG export for graphical outputs  

✔ **Visualization & Trend Analysis**  
   - **Word Cloud** for keyword representation  
   - Sentiment trend **plotting and tracking**  
   - **Interactive graphs** to display sentiment evolution  

✔ **Performance Optimization**  
   - Asynchronous threading for news fetching  
   - UI interaction improvements for seamless experience  

---

### **🐍 Python Packages Used**
✔ **Core Libraries for Data Handling**  
   - `pandas` → Data manipulation, CSV exporting  
   - `numpy` → Numerical computations  

✔ **Natural Language Processing (NLP) & Sentiment Analysis**  
   - `nltk.sentiment.vader` → Sentiment polarity scoring  
   - `spacy` → Named Entity Recognition (NER)  
   - `wordcloud` → Generating keyword cloud visualizations  

✔ **Web Scraping & Data Fetching**  
   - `beautifulsoup4` → Parsing HTML content for news headlines  

✔ **Graphical User Interface (GUI) & Visualization**  
   - `PyQt5` → Interactive GUI elements  
   - `PyQtGraph` → Real-time sentiment trend visualization  

✔ **Performance Optimization & Asynchronous Execution**  
   - `threading` → Multi-threaded news fetching  
   - `requests` → Asynchronous HTTP requests (suggested future enhancement)  

---

This setup provides **a powerful NLP-driven sentiment analysis application**, combining **real-time news data**, **text processing**, 
**interactive visualization**, and **efficient data storage** for valuable insights.
 


5. "GAN vs OpenCV Chessboard Reconstruction"  

### Description 
This project aims to compare traditional OpenCV-based methods for chessboard image 
reconstruction with Generative Adversarial Network (GAN)-driven approaches. The goal is to evaluate the effectiveness of deep 
learning in reconstructing secluded or obscured chessboard sections more accurately than conventional techniques.  

**Technologies** and **Python packages** used in the project:

---

### **📌 Technologies Used**
✔ **Computer Vision Techniques**  
   - Edge Detection (`cv2.Canny`)  
   - Contour Detection (`cv2.findContours`)  
   - Perspective Transformation (`cv2.getPerspectiveTransform`)  

✔ **Deep Learning (GAN)**  
   - Generative Adversarial Networks (GAN) for chessboard reconstruction  
   - Adversarial loss optimization  
   - TensorFlow/Keras-based model training  

✔ **Image Preprocessing & Augmentation**  
   - Grayscale normalization  
   - Image resizing (`cv2.resize`)  
   - Dataset creation for GAN training  

✔ **Performance Optimization & Deployment**  
   - GPU acceleration using Google Colab (T4 GPU)  
   - Batch processing for faster training  
   - Model persistence (`gan_chessboard_model.h5`)  

✔ **Evaluation & Comparison**  
   - Reconstruction accuracy in obstructed images  
   - Processing speed and computational efficiency  
   - Comparison between GAN-based and OpenCV-based methods  

---

### **🐍 Python Packages Used**
✔ **Core Libraries for Data Handling & Computation**  
   - `numpy` → Numerical operations  
   - `pandas` → Data handling  

✔ **Computer Vision & Image Processing**  
   - `opencv-python` → Edge detection, contour detection, perspective transformation  
   - `matplotlib` → Visualization of reconstructed images  

✔ **Deep Learning & Neural Networks**  
   - `tensorflow.keras` → GAN model implementation & training  
   - `tensorflow.keras.models` → Model saving & persistence (`save_model`)  
   - `tensorflow.keras.optimizers` → Loss function optimization  

✔ **System & File Operations**  
   - `os` → File management  
   - `shutil` → File copying/moving  

✔ **Google Colab Integration**  
   - `Google Colab GPU Acceleration` → Faster training execution  
   - Interactive runtime configuration  

---

This setup provides **a powerful AI-driven chessboard reconstruction system**, leveraging 
**traditional computer vision (OpenCV)** and **deep learning-based GAN techniques** for superior image completion.

6. "Real Estate Data Set Analysis in Flower Hill"  

### Description 
This project involves a large data set related to real estate sales for a 
fictional town of Flower Hill. The aim is to combine the analysis of this data set with PyMongo, MLflow, Python 
(SARIMAX times series forecasting, classification, Neural Networks, Kohonen Maps) and DAG-like process organization of ML-tasks. 
Thus, we are blending data engineering, machine learning, forecasting, and process automation into a well-structured framework.  

**Technologies** and **Python packages** used in the project:

---

### **📌 Technologies Used**
✔ **Database & Data Storage**  
   - **MongoDB (PyMongo)** → NoSQL database for storing real estate transactions.  
   - **Apache Airflow** → DAG-based automation for machine learning workflows.  
   - **MLflow** → Model tracking, logging, and versioning for ML experiments.  

✔ **Machine Learning & Forecasting**  
   - **SARIMAX** → Time series forecasting for property price trends.  
   - **Classification Models** → Predict buyer types, resale probability, and price ranges.  
   - **Neural Networks** → Deep learning models for pattern recognition.  
   - **Kohonen Maps** → Self-organizing neural networks for clustering districts.  
   - **Random Forest** → Classification & decision-making for district identification.  

✔ **Data Engineering & Processing**  
   - **Feature Engineering** → Extracting key property attributes for ML models.  
   - **Data Cleaning** → Handling missing values, formatting timestamps, and standardizing currency.  
   - **Automated Forecast Updates** → Using DAG scheduling in Airflow.  

✔ **Visualization & Interpretation**  
   - **Real Estate Price Trends** → Box plots, comparative district analyses.  
   - **Urban Expansion & Buyer Segmentation** → Cluster analysis with Kohonen maps.  
   - **Market Control & Economic Cycles** → Comparative analytics across districts.  
   - **Sentiment Analysis & Economic Growth Forecasts** → Exploring price evolution in different districts.  

✔ **Performance Optimization & Deployment**  
   - **Windows 10 (Anaconda Environment)** → Isolated ML/AI dependencies.  
   - **Cloud-Based Solution for Scaling** → Suggested AWS/GCP/Azure deployment options.  
   - **GPU Acceleration for Faster Computation** → Optimization for ML workloads.  

---

### **🐍 Python Packages Used**
✔ **Core Libraries for Data Handling & Computation**  
   - `pandas` → DataFrame operations for structured transactions.  
   - `numpy` → Numerical computations for forecasting models.  
   - `pymongo` → MongoDB integration for transaction storage & retrieval.  

✔ **Machine Learning & Forecasting Models**  
   - `statsmodels.tsa.statespace.sarimax` → SARIMAX for property price forecasting.  
   - `sklearn.ensemble.RandomForestClassifier` → Random Forest model for classification.  
   - `kohonen` → Kohonen Maps for self-organizing district clustering.  
   - `tensorflow.keras` → Neural Networks for property price prediction.  

✔ **Pipeline Automation & Model Tracking**  
   - `apache-airflow` → DAG-based execution for ML tasks.  
   - `mlflow` → Model logging, tracking, and visualization.  

✔ **Visualization & Interpretation**  
   - `matplotlib` → Standard plotting for time series & district comparisons.  
   - `seaborn` → Advanced statistical visualizations.  

✔ **System & Deployment Tools**  
   - `pickle` → Model persistence & saving trained classifiers.  
   - `shutil` → File management for structured dataset handling.  

---

This setup provides **a structured ML pipeline for analyzing real estate trends**, leveraging
**MongoDB, Airflow, MLflow, and various machine learning models** for **forecasting, classification, clustering, and trend analysis**.

