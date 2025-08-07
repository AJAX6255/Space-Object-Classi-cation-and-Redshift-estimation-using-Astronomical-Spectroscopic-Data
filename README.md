# A Computational Approach to Observational Cosmology: Redshift Prediction and Object Classification

## Introduction

Esteemed colleagues and fellow researchers,

Welcome to this repository, which documents a computational exploration into two fundamental challenges in observational cosmology: the prediction of redshift and the classification of celestial objects. This work leverages machine learning techniques to analyze photometric data from the Sloan Digital Sky Survey (SDSS), providing a practical demonstration of how modern data science can be applied to astrophysical research.

The accurate determination of redshift is paramount for understanding the large-scale structure of the universe and the nature of cosmic expansion. Similarly, the ability to classify celestial objects—such as galaxies, quasars (QSOs), and stars—is essential for a wide range of astronomical studies, from stellar evolution to the distribution of matter in the cosmos.

This project is presented as a series of Jupyter notebooks, each addressing a specific aspect of our investigation. We invite you to explore the code, replicate our findings, and build upon this work in your own research endeavors.


## Project Components

This repository is organized into two primary components:

1.  **Redshift Prediction (`Hubble Diagram Project.ipynb`)**: This notebook employs machine learning regression models to predict the redshift of celestial objects based on their photometric properties (magnitudes in the u, g, r, i, and z filters). It also includes visualizations of the data, such as a 2D map of galaxy locations, to provide a visual context for our analysis.

2.  **Object Classification (`Final_Classification_of_Space_Object.ipynb`)**: This notebook focuses on the classification of celestial objects into three distinct categories: galaxies, quasars, and stars. It utilizes a variety of supervised learning algorithms and includes hyperparameter tuning to optimize classification accuracy.

## Repository Structure

```
/
├── 📄 Classification of Space Objects.ipynb
├── 📄 Final_Classification_of_Space_Object.ipynb
├── 📄 Hubble Diagram Project.ipynb
└── 📄 README.md
```


## Data

The data used in this project is sourced from the Sloan Digital Sky Survey (SDSS), a comprehensive astronomical survey that has mapped a significant portion of the night sky. The dataset includes photometric measurements, celestial coordinates, and spectroscopic classifications.

**Note on Data Files**: The original data files (`input.csv` and `New Text Document.csv`) are not included in this repository due to their size. Researchers interested in replicating this work should obtain the relevant data from the SDSS database. The notebooks provide the necessary context for understanding the data structure.


## Methodology and Findings

### Redshift Prediction

In our investigation of redshift prediction, we evaluated three regression models:

-   **Random Forest Regressor**: This model demonstrated the highest efficacy, achieving a coefficient of determination (R²) of **0.721**.
-   **Decision Tree Regressor**: This model yielded a moderate R² of **0.500**.
-   **Linear Regression**: As expected for a non-linear astrophysical problem, this model showed a low R² of **0.003**.

These results underscore the power of ensemble methods, like Random Forest, in handling complex, high-dimensional astrophysical data.

### Object Classification

For the classification of celestial objects, we employed a suite of supervised learning algorithms. The most notable results were obtained with:

-   **Decision Tree Classifier**: After hyperparameter tuning, this model achieved a classification accuracy of approximately **94.6%**.
-   **Random Forest Classifier**: This model also performed exceptionally well, with an accuracy of around **96%**.


## Setup and Execution

To run the notebooks in this repository, please ensure you have a Python environment with the following libraries installed:

-   NumPy
-   Pandas
-   Seaborn
-   Matplotlib
-   Scikit-learn
-   Plotly

You can install these dependencies using `pip`:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn plotly
```

Once the environment is set up, you can launch Jupyter Notebook and navigate to the repository to execute the notebooks.


## Conclusion

This project serves as a practical introduction to the application of machine learning in astrophysics. The results demonstrate the potential of these techniques for both redshift prediction and object classification, two critical tasks in modern cosmology. We hope this work will be a valuable resource for students and researchers alike, and we encourage further exploration and refinement of these methods.

Yours in science,

A Professor of Astrophysics
