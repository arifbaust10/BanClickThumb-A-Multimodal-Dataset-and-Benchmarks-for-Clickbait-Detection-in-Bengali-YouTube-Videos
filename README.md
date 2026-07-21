# BanClickThumb: A Multimodal Dataset and Transformer Fusion Benchmarks for Clickbait Detection in Bengali YouTube Videos


## 📊 Dataset

To run the code in this repository, you will need to use our custom dataset. You can easily find and download it from Kaggle using the links below:

- **Download Dataset:** [BanClickThumb: Bangla Clickbait Dataset](https://www.kaggle.com/datasets/ariful234/banclickthumb-bangla-clickbait-dataset) 
- **Dataset DOI:** [![DOI](https://img.shields.io/badge/DOI-10.34740%2Fkaggle%2Fdsv%2F15501168-blue)](https://doi.org/10.34740/kaggle/dsv/15501168)

*Note: Please download the dataset and extract the files to your local machine before running the code.*



## 📝 Citation

If you use this dataset or the benchmark models in your research, please cite our paper:

**Paper DOI:** [![DOI](https://img.shields.io/badge/DOI-10.48550%2FarXiv.2607.17182-green)](https://doi.org/10.48550/arXiv.2607.17182)  
**arXiv:** [arXiv:2607.17182 [cs.CV]](https://arxiv.org/abs/2607.17182)

**BibTeX:**
```bibtex
@misc{islam2026banclickthumb,
      title={BanClickThumb: A Multimodal Dataset and Benchmarks for Clickbait Detection in Bengali YouTube Videos}, 
      author={Md. Ariful Islam},
      year={2026},
      eprint={2607.17182},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={[https://doi.org/10.48550/arXiv.2607.17182](https://doi.org/10.48550/arXiv.2607.17182)}
}
```

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
