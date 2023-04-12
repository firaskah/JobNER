# Job Posting Entity Extraction

This repository contains code and examples to demonstrate how to extract job entities (Job Title, Company Name, Job Location, Job Description, Required Skills, Education Requirements, Job Type, Salary) from job postings using a pre-trained RoBERTa NER model. The goal is to show how to train and use a RoBERTa NER model to extract job entities from job postings and highlight them in a Jupyter notebook.

## Getting Started

To get started, you can clone this repository to your local machine:

```
git clone https://github.com/<username>/<repository-name>.git'
```

Then, navigate to the cloned directory:

```
cd JobNER
```

## Installation

To run the code in this repository, you will need to install the following dependencies:

- Python 3.6+
- Jupyter Notebook
- PyTorch
- Transformers
- Pandas
- Numpy

You can install these dependencies using pip:

```
pip install jupyter torch transformers pandas numpy
```

## Usage

To use this repository, you can follow the steps outlined in the Jupyter notebooks located in the `notebooks/` folder:

1. `01_data_preparation.ipynb`: This notebook shows how to prepare your job posting data for training the RoBERTa NER model.

2. `02_fine_tuning_roberta.ipynb`: This notebook shows how to fine-tune the pre-trained RoBERTa model on your labeled job posting data.

3. `03_predict_entities.ipynb`: This notebook shows how to use the fine-tuned RoBERTa model to extract job entities from job postings and highlight them in a Jupyter notebook.

You can also modify the code in these notebooks and the `data/` folder to fit your specific use case and data.

## Data

The `data/` folder contains a small dataset of simulated job postings generated from GPT-3.5. You can use this data to train and test the RoBERTa NER model. The data is provided in both CSV and JSON formats.

## Models

The `models/` folder contains a pre-trained RoBERTa NER model and a fine-tuned RoBERTa NER model. You can use these models to extract job entities from job postings.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The pre-trained RoBERTa model used in this repository is provided by the Hugging Face Transformers library: https://github.com/huggingface/transformers
- The simulated job postings were generated using GPT-3.5.



