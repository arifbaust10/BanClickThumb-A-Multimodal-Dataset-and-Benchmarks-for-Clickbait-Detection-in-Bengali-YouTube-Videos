# BanClickThumb: A Multimodal Dataset and Transformer Fusion Benchmarks for Clickbait Detection in Bengali YouTube Videos


## 📊 Dataset

To run the code in this repository, you will need to use our custom dataset. You can easily find and download it from Kaggle using the link below:

* **Download Dataset:** [BanClickThumb: Bangla Clickbait Dataset](https://www.kaggle.com/datasets/5345efaf68005de56157e10096c251f1714d5acc19bd85857275ef11be2d5fab)

*Note: Please download the dataset and extract the files to your local machine before running the code.*

## 📂 Project Structure

The code is written in Jupyter Notebooks and is divided into four main folders based on the fusion strategy used:

* **Unimodal:** Contains code for models that use only a single type of data (for example, just text or just images).
* **Early Fusion:** Contains models that combine different types of data right at the beginning of the process.
* **Intermediate Fusion:** Contains models that mix data types in the middle layers of the neural network.
* **Late Fusion:** Contains models that process data separately and combine their final predictions at the very end.

## 🚀 How to Run the Code

Follow these simple steps to run the project on your computer:

### Step 1: Download the Repository
First, clone this repository to your computer using your terminal, or simply download it as a ZIP file and extract it.

    git clone https://github.com/arifbaust10/BanClickThumb-A-Multimodal-Dataset-and-Benchmarks-for-Clickbait-Detection-in-Bengali-YouTube-Videos.git


### Step 2: Download and Place the Dataset
Go to the Kaggle link provided above. Download the dataset and place the data files inside the main project folder. (Make sure to check the file paths inside the notebooks so they match where you placed your data).

### Step 3: Install Required Libraries
Ensure you have Python installed on your system. You will need to install Jupyter and the necessary Python libraries used in the notebooks. You can install Jupyter by running:

    pip install notebook pandas numpy


### Step 4: Open the Notebooks
1. Open your terminal or command prompt.
2. Go to the project folder.
3. Type the following command and press Enter:

    jupyter notebook

4. A web browser window will open. Click on any of the folders (like `Unimodal` or `Early Fusion`), open the notebook file, and run the code cells step by step.
