# Do Parents Talk to Boys and Girls Differently During Play?

![Banner](Images.png)


## Introduction

Recently, there has been increasing focus on gender differences and parenting in research and the popular press. This is especially prominent in light of gender disparities in STEM education. One reason for this disparity might stem from how parents speak to their young children during play (e.g., Crowley, Callanan, Tenenbaum, & Allen, 2001; Tenenbaum & Leaper, 2003).

The goal of this project was to investigate whether parents would speak to their children differently depending on gender in a neutral play setting in our laboratory.

## Data Collection

Data for this project came from a study investigating word learning skills in toddlers in a lab at UT Austin. The research assistant, they transcribed a random sample of parent-child play sessions. In this project, thumulated data and examined the types of words parents use with their toddlers during a brief play session with this [toy](https://www.melissaanddoug.com/products/bug-catching-magnetic-puzzle-game?gclid=EAIaIQobChMIxZTwxMqf2QIVW57ACh1mvgIKEAQYAyABEgLZD_D_BwE&product_id=ae0f052115fca3351fc50a1fa59a6392&utm_campaign=PLA_B_Active_Play_Desk&utm_content=a6&utm_medium=shopping&utm_source=google&utm_term=Active_Play_Outdoor) in the lab.

## Technologies Used

- **Python**: For data analysis and manipulation.
- **Jupyter Notebook**: For interactive data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **NLTK (Natural Language Toolkit)**: For text processing and analysis.
- **Scikit-learn**: For machine learning models.
- **Matplotlib**: For data visualization.
- **Seaborn**: For enhanced data visualization.
- **SQLite**: For database management.
- **Git**: For version control.
- **GitHub**: For project hosting and collaboration.

## Project Structure
```
.
├── data
│ ├── raw
│ └── processed
├── notebooks
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_exploratory_data_analysis.ipynb
│ └── 03_modeling.ipynb
├── src
│ ├── data_preprocessing.py
│ ├── exploratory_data_analysis.py
│ └── modeling.py
├── README.md
└── requirements.txt
```



- **Data/raw**: Contains the raw data files.
- **Data/processed**: Contains the processed data files.
- **Notebooks**: Contains Jupyter notebooks for different stages of the project.
- **src**: Contains Python scripts for data preprocessing, exploratory data analysis, and modeling.
- **README.md**: This file.
- **Requirements.txt**: Lists the Python packages required for the project.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/parent-child-gender-differences.git
    ```
2. Change into the project directory:
    ```bash
    cd parent-child-gender-differences
    ```
3. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the data preprocessing script:
    ```bash
    python src/data_preprocessing.py
    ```
2. Open the exploratory data analysis notebook:
    ```bash
    jupyter notebook notebooks/02_exploratory_data_analysis.ipynb
    ```
3. Run the modeling script:
    ```bash
    python src/modeling.py
    ```

## Authors

- [Data_Attracts_Kay](https://github.com/DataattractsKay)

## Acknowledgements

- Thank you to the research scholars and participants who made this study possible.
- This project was conducted at the University of Texas at Austin.


