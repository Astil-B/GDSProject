# GDSProject - Exam Project in Generative Data Science (UCPH)

This repository contains the exam project for the course Generative Data Science (GDS) at the University of Copenhagen (UCPH). The project focuses on the detection of fake news using the LIAR dataset and neural network architectures.

## Project Description
The goal of this project is to build and evaluate a machine learning model capable of classifying statements based on their truthfulness. The workflow covers the entire data science pipeline, including data scraping, preprocessing, exploratory data analysis, model development, and final evaluation.

## Repository Structure
The project is divided into several parts, each documented in its own Markdown and Jupyter Notebook file:

- Part 1: Initial data exploration and preprocessing.
- Part 2: Feature engineering and data splitting.
- Part 3: Model architecture design and initial training.
- Part 4: Hyperparameter tuning and model optimization.
- Part 5: Final evaluation and discussion of results.

Additional files:
- LIARrun.ipynb: The main execution script for the LIAR dataset.
- best_fakenews_model.pt / fakenews_model_final.pt: Saved PyTorch models.
- liar_dataset/: Directory containing the raw and processed dataset.
- word_distribution.png: Visual representation of the dataset characteristics.

## Getting Started

### Prerequisites
To run the notebooks, you need a Python environment with the following libraries:
- PyTorch
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Lab

### Installation
1. Clone the repository:
   git clone https://github.com/Astil-B/GDSProject.git
2. Navigate to the folder:
   cd GDSProject
3. Install dependencies (if a requirements file is provided or manually via pip):
   pip install torch pandas matplotlib scikit-learn

## Usage
Open the Jupyter Notebooks in chronological order (Part 1 to Part 5) to follow the development process. You can use TesterNN.ipynb to test the performance of the saved models on new or existing data.

## Authors
Developed by Kian Nicklas og Emil as part of the GDS-UCPH exam.

## License
This project is for educational purposes and follows the guidelines set by the University of Copenhagen.
