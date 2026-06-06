# IDOOU – AI Ethics Project

A Udacity Nanodegree project exploring fairness and bias in a personalized activity recommender app using IBM's AIF360 toolkit.

## Project Overview

IDOOU is a hypothetical mobile app that recommends local activities (parks, movies, hiking, libraries, etc.) to users based on their profile. This project builds a **budget predictor** and analyzes its fairness properties with respect to education level.

**Problem statement**: Do users with bachelor's or master's degrees have a privileged budget (≥ $300) compared to users who graduated from high school?

**Key tools**: IBM AIF360, TensorFlow, scikit-learn, fairlearn, PyTorch, LIME, Captum

## Dataset

`udacity_ai_ethics_project_data.csv` — ~300,000 synthetic records from a user experience study, with features including:
- `gender`
- `age`
- `education_level`
- `budget` (target variable, in USD)

## Setup

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
2. Create and activate the environment:
   ```bash
   conda create -n idoou python=3.10
   conda activate idoou
   conda install scipy
   pip install -r requirements.txt
   ```
3. Open `AI Ethics Project -- STARTER.ipynb` in VS Code and select the `idoou` kernel.

## License

This project is based on course materials from Udacity, Inc., licensed under the
[Creative Commons Attribution-NonCommercial-NoDerivs 3.0 License](LICENSE).
