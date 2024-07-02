
# NLP Project: TF-IDF from Scratch

This project showcases the implementation of a Term Frequency-Inverse Document Frequency (TF-IDF) model from scratch using Python. The goal is to preprocess textual data, tokenize the text, and compute the TF-IDF scores without relying on existing libraries.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In this project, I have demonstrated how to build a TF-IDF model from the ground up. This includes steps for data preprocessing, tokenization, creating word to index mapping as well as reverse mapping and the computation of TF-IDF scores. The project is implemented in a Jupyter Notebook, making it easy to follow along and understand each step of the process.

## Dataset

The dataset used in this project is the BBC Text Classification dataset, which contains textual data categorized into different news topics. The dataset is downloaded from [this source](https://www.kaggle.com/shivamkushwaha/bbc-full-text-document-classification).

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/nihalmorshed/nlp-tfidf-from-scratch.git
   ```
2. Navigate to the project directory:
   ```bash
   cd nlp-tfidf-from-scratch
   ```
3. Install the required libraries:
   ```bash
   pip install pandas numpy nltk
   ```

## Usage

Open the Jupyter Notebook to see the implementation details:
```bash
jupyter notebook TF_IDF_from_Scratch.ipynb
```

## Features

- **Data Loading**: Load the dataset into a pandas DataFrame.
- **Text Preprocessing**: Tokenize the text data using NLTK.
- **TF-IDF Calculation**: Compute TF-IDF scores from scratch.
- **Result Visualization**: Display the computed TF-IDF scores.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
