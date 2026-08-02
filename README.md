# Disaster Tweet Information Extraction using NLP & Prompt Engineering

## Overview

This project focuses on extracting critical information from disaster-related tweets using Natural Language Processing (NLP) and Prompt Engineering techniques. Social media platforms such as Twitter provide real-time updates during natural disasters, making them valuable sources of situational awareness for emergency response teams.

The objective of this project is to identify and extract essential information from tweets, including disaster type, affected location, severity, casualties, infrastructure damage, and resource requirements. The extracted information can support disaster management authorities in making faster and more informed decisions.

---

## Objectives

* Classify disaster-related tweets.
* Extract important entities from tweets.
* Identify disaster type and affected locations.
* Summarize disaster information using prompt engineering.
* Demonstrate the application of NLP techniques for emergency response.

---

## Features

* Text preprocessing and cleaning
* Tokenization and normalization
* Named Entity Recognition (NER)
* Information extraction from disaster tweets
* Prompt Engineering for structured information extraction
* Performance evaluation and result analysis

---

## Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* NLTK
* spaCy
* Transformers (Hugging Face)
* OpenAI Prompt Engineering (or equivalent LLM prompts)
* Matplotlib
* Scikit-learn

---

## Dataset

The project uses disaster-related tweets collected from publicly available datasets. Each tweet contains textual information describing disaster events such as:

* Flood
* Earthquake
* Cyclone
* Wildfire
* Landslide
* Building Collapse
* Accident
* Hurricane

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. NLP Pipeline

   * Tokenization
   * Stop-word Removal
   * Lemmatization
   * Named Entity Recognition
5. Prompt Engineering
6. Information Extraction
7. Result Evaluation
8. Visualization

---

## Information Extracted

The system extracts structured information such as:

| Field                 | Description                          |
| --------------------- | ------------------------------------ |
| Disaster Type         | Type of disaster                     |
| Location              | Affected area                        |
| Time                  | Time or date mentioned               |
| Casualties            | Injuries or deaths                   |
| Infrastructure Damage | Roads, bridges, buildings, etc.      |
| Resources Needed      | Food, water, rescue, medical support |
| Severity              | Low / Medium / High                  |

---

## Sample Output

**Input Tweet**

> "Major flooding reported in Chennai. Several roads submerged and rescue teams have been deployed."

**Extracted Information**

```text
Disaster Type      : Flood
Location           : Chennai
Severity           : High
Infrastructure     : Roads submerged
Response           : Rescue teams deployed
```

---

## Repository Structure

```text
Disaster-Tweet-Information-Extraction/
│
├── data/
├── notebooks/
├── src/
├── outputs/
├── images/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/disaster-tweet-information-extraction.git
```

Navigate to the project folder:

```bash
cd disaster-tweet-information-extraction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook or Python scripts to reproduce the results.

---

## Results

The project demonstrates how NLP techniques combined with Prompt Engineering can effectively transform unstructured disaster-related tweets into structured information that supports emergency response and disaster management.

---

## Future Enhancements

* Fine-tune transformer models for disaster-specific information extraction.
* Deploy the solution as a web application using Streamlit or FastAPI.
* Integrate real-time Twitter/X data streaming.
* Add multilingual disaster tweet support.
* Develop an interactive dashboard for emergency response teams.

---

## Learning Outcomes

* Practical application of Natural Language Processing.
* Understanding of Prompt Engineering techniques.
* Information extraction from unstructured text.
* Named Entity Recognition using modern NLP libraries.
* Building an end-to-end NLP pipeline for real-world disaster management.

---

## Author

**Sobana S**

M.Tech – Data Science & Engineering (WILP)
BITS Pilani

---

## License

This project is developed for academic and educational purposes as part of the M.Tech coursework at BITS Pilani.
