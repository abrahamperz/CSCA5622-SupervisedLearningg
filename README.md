# CSCA 5622: Introduction to Machine Learning: Supervised Learning

## Course Information
- **Institution**: University of Colorado Boulder
- **Course**: [CSCA5622: Supervised Learning](https://www.colorado.edu/cs/academics/online-programs/mscs-coursera/csca5622)
- Author: Jose Abraham Perez Martinez
- **Instructor**: [Professor Geena Kim](https://www.colorado.edu/program/data-science/geena-kim)

## Project Overview
This project is the culmination of the CSCA5622. It involves applying various machine learning algorithms to a dataset to predict diseases based on given symptoms. The project aims to compare the performance of different models and provide insights into their effectiveness.

## Requirements
- **Python Version**: 3.9.6
- Jupiter Notebook
- **Libraries**:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `jupyter`
  - `ipython`


## Installation
To set up the project environment, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
    ```
Create a virtual environment:
 ```
python3.9 -m venv venv
source venv/bin/activate`
 ```
Install the required libraries:

 ```pip install -r requirements.txt ```

Project Structure

- data/: Contains the dataset used for the project.

- notebooks/: Contains the Jupyter Notebook with the project code and analysis.

- results/: Contains the output files and visualizations generated by the notebook.

## Conclusion
**Random Forest** algorithm demonstrated higher condidence in its predictions compared to Logistic regression, in this case we can see the difference for the Common Cold. This suggest that Random Forest is more effective for classification.
