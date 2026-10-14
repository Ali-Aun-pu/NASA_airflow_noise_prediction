# 🔊 NASA Airfoil Noise Prediction with PySpark ML

This project uses **PySpark ML** on the NASA Airfoil Self-Noise dataset to estimate the noise an airfoil produces. It walks through a complete **machine learning pipeline** on Apache Spark, from preparing the features to training and evaluating several models.

## 📂 Project Structure

* `NASA_airfoil_noise_detection.ipynb` – Jupyter Notebook containing the entire PySpark ML workflow
* `requirements.txt` – list of required Python and PySpark packages
* `data/` – (optional) dataset files or download instructions

## 🚀 Getting Started

1. Download the repository:

   ```bash
   git clone https://github.com/waqas001-pu/NASA-airfoil-noise-detection.git
   cd NASA-airfoil-noise-detection
   ```

2. Install the required packages (Spark must already be set up in your environment):

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook NASA_airfoil_noise_detection.ipynb
   ```

## 📊 Dataset

The data is taken from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise).
It has **1,503 records**, each with 5 input features and one target value, the scaled sound pressure level.

## 🛠️ Tech Stack

* **PySpark ML** (Pipelines, Transformers, Estimators)
* Python
* Jupyter Notebook
* Pandas (used for early data exploration)
* Matplotlib / Seaborn (used for plotting)

## ✨ Key Features

* Loading and cleaning the data with PySpark
* Scaling features and assembling vectors using Spark ML tools
* Training regression models such as Linear Regression, Decision Tree Regressor, and Random Forest Regressor
* Measuring model quality with **RMSE** and **R²**
* A full ML pipeline running on a distributed framework

## 📈 Results

* Built working PySpark ML pipelines for several regression models
* Compared the models' metrics to find the one that performs best
* Showed how PySpark ML supports scalable machine learning workflows

## 📜 License

This project is released under the MIT License.
