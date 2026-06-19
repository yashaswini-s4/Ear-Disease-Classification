# An Explainable AI Framework for Ear Disease Classification Using Otoscopic Images

## Overview

This project presents a **Multimodal Explainable AI Framework** for classifying ear diseases using **otoscopic images** and **patient symptoms**. It combines deep learning, machine learning, and Explainable AI (XAI) techniques to provide accurate and interpretable predictions.

## Features

* Ear disease classification using Vision Transformer (ViT)
* Symptom-based prediction using Random Forest
* Multimodal late fusion for improved prediction accuracy
* SHAP for symptom explainability
* Grad-CAM for image visualization
* LLM-generated clinical explanations

## Technologies Used

* Python
* PyTorch
* Scikit-learn
* Vision Transformer (ViT)
* SHAP
* Grad-CAM
* Gradio
* Google Gemini API

## Dataset

### Image Dataset

https://www.kaggle.com/datasets/ucimachinelearning/otoscopic-image-dataset

### Symptom Dataset

Custom dataset containing 500 patient symptom records.

## Project Files

* `finalEARDISEASE_withoutcomments.ipynb` – Complete project implementation
* `report.pdf` – Project report
* `final_mini_project.pptx` – Project presentation

## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run all the cells in `finalEARDISEASE_withoutcomments.ipynb`.

## Results

| Model                    | Accuracy |
| ------------------------ | -------- |
| Random Forest            | 84%      |
| Vision Transformer (ViT) | 97.5%    |
| Multimodal Fusion        | 98.3%    |

## License

This project is developed for academic and educational purposes.
