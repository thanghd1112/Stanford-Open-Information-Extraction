# Stanford Open Information Extraction (OIE)

## Overview
This project focuses on applying the Stanford OpenIE tool to perform Open Information Extraction (OIE) for English texts. The primary objective is to evaluate the effectiveness of information extraction in English, serving as a foundation for similar applications in Vietnamese. The goal is to extract structured triples (subject-relation-object) from unstructured text, facilitating information retrieval and natural language understanding. The project includes an exploration of potential adaptations for Vietnamese text data.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [Author](#author)

## Features
- Implementation of Stanford OpenIE for extracting triples from English Wikipedia data.
- Evaluation of model performance using precision and recall metrics.
- Exploration of methods to adapt OpenIE for Vietnamese text.
- Data preprocessing and ground truth creation for performance benchmarking.

## Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Libraries: `stanfordnlp`, `numpy`, `pandas`, `matplotlib`, `scikit-learn`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/thanghd1112/Stanford-Open-Information-Extraction.git
   cd Stanford_OIE_English
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the Stanford CoreNLP toolkit and models:
   - [Stanford CoreNLP Download Page](https://stanfordnlp.github.io/CoreNLP/)
   - Place the `.jar` and model files in a directory accessible to your script.

## Dataset
- **English Dataset**: Extracted from English Wikipedia with a focus on the travel domain.
- **Ground Truth**: Manually created dataset for evaluating the extracted triples.

## Usage
1. Open the Jupyter Notebook `Stanford_OIE_English.ipynb`.
2. Configure the Stanford CoreNLP path in the notebook.
3. Run the notebook cells to:
   - Load and preprocess the data.
   - Apply the OpenIE tool for extracting triples.
   - Evaluate the model's performance.

## Project Workflow
1. **Data Collection**: Extract text data from Wikipedia using scraping tools.
2. **Data Preprocessing**: Clean and format the text for input to the OpenIE tool.
3. **Triple Extraction**: Use Stanford OpenIE to extract subject-relation-object triples.
4. **Performance Evaluation**: Measure precision and recall based on ground truth.
5. **Exploration**: Investigate the potential application of OpenIE for Vietnamese text.

## Results
- Successfully extracted meaningful triples from English Wikipedia data.
- Evaluated model performance with metrics like precision and recall.
- Identified challenges in applying the tool to Vietnamese text, including language-specific limitations.
- Example output: ![Triple Extraction Output](graph.png)

## Future Work
- Adapt Stanford OpenIE for Vietnamese text, including:
  - Language-specific preprocessing techniques.
  - Developing custom models for Vietnamese language support.
- Extend the dataset to include other domains and languages.
- Explore integration of OpenIE into downstream NLP tasks like question answering or summarization.

## Contributing
We welcome contributions to improve this project. To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request in the main repository.

---
**Author:** [Hoàng Thăng](https://www.linkedin.com/in/thang-hoang-3b6954295) 
**Institution:** [University of Foreign Languages and Information Technology, Ho Chi Minh City](https://fit.huflit.edu.vn/)  
**Supervisor:** [Dr. Trần Khải Thiện](https://fit.huflit.edu.vn/giang-vien/tran-khai-thien/)

---
Thank you for reading!