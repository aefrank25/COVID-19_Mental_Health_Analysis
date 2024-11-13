# Analyzing Mental Health Trends in the U.S. During COVID

## Project Overview
This project examines mental health trends in the United States during the COVID-19 pandemic, specifically focusing on symptoms of anxiety and depression across various demographics. The goal is to identify patterns and factors influencing mental health outcomes during this period. This project was completed as part of a master's-level business analytics course (CIS 591) at Arizona State University, with contributions from a team of classmates.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)
- [Key Findings](#key-findings)
- [Contributors](#contributors)
- [License](#license)

## Data Source
This analysis uses a publicly available dataset on [Kaggle: Indicators of Anxiety or Depression](https://www.kaggle.com/datasets/melissamonfared/indicators-of-anxiety-or-depression), which includes information on mental health symptoms, demographics, and related factors during the COVID-19 pandemic.

### Data Preparation
Before running our analysis, we performed basic cleanup on the original Excel file to remove errors and inconsistencies. To replicate our analysis:
1. Download the dataset directly from Kaggle.
2. Save it in the `/data` directory of this project.
3. Run the analysis scripts or Jupyter notebooks, which read and process the cleaned data as part of the analysis workflow.

*Note*: Due to licensing, the data cannot be redistributed here. Please download it directly from Kaggle and place it in the `/data` directory.

## Processed Data
The specific file used for our analysis, after initial data cleaning, is located in the `/data/CIS 591_Indicators of Anxiety and Depression Data.csv` file (or replace with your file’s actual name and path). This file includes the dataset in a format ready for analysis. For detailed cleaning steps, refer to the scripts in the `/scripts` folder or the Jupyter notebooks in the `/notebooks` directory.


## Objectives
The main goals of this project are:
- Analyzing trends in anxiety and depression symptoms by demographics (e.g., age, gender).
- Exploring the impact of external factors (e.g., COVID-19 cases, lockdowns) on mental health trends.
- Identifying areas for further research and potential mental health support during pandemic scenarios.

## Technologies Used
- **Python**: Core programming language for data analysis.
- **Libraries**: 
  - `pandas`: Data manipulation
  - `numpy`: Numerical computations
  - `matplotlib` and `seaborn`: Data visualization
  - `scikit-learn`: Machine learning and model evaluation
- **Tools**: Jupyter Notebooks for interactive analysis and visualization.

## Project Structure
```plaintext
├── data/                   # Folder to link external dataset source
├── notebooks/              # Jupyter Notebooks for step-by-step analysis
├── README.md               # Project overview and documentation
└── requirements.txt        # Required libraries
```
# How to Use

1. **Clone the Repository**
   <!-- Command to clone the repository -->
   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/aefrank25/mental-health-trends-covid.git
2. **Install Dependencies**

<!-- Commands to navigate to the project directory and install dependencies -->
Navigate to the project directory and install the required Python packages:
cd mental-health-trends-covid
pip install -r requirements.txt

3. **Download the Dataset**
   - Visit the [Kaggle dataset page](https://www.kaggle.com/datasets/melissamonfared/indicators-of-anxiety-or-depression).
   - Download the dataset and save it to the `/data` directory of this project.
  
4. **Run the Notebooks**
    Open the Jupyter notebooks in the /notebooks directory to follow the step-by-step analysis. Each notebook contains code      and comments that guide you through the data cleaning, exploration, and visualization processes.
   jupyter notebook #run the command

## Key Findings

Some of the main insights from the analysis include:

- **Increased Anxiety and Depression**: There was a significant rise in reported symptoms of anxiety and depression across all demographics during the early stages of the COVID-19 pandemic.
- **Younger Adults More Affected**: Individuals aged 18-29 exhibited higher levels of anxiety and depression compared to older age groups.
- **Impact of Geographic Location**: Certain regions experienced more pronounced mental health challenges, correlating with factors like infection rates and lockdown stringency.
- **Economic Factors**: Unemployment rates and financial instability showed a strong association with increased mental health issues.

**Limitations**: A key limitation of this project was the timeline; we had less than 7 weeks to complete it. This time constraint limited the depth of data exploration and the complexity of our analysis. Additional insights could be gained with further refinement and extended analysis time.

## Contributors

- **Amy Frank**
- **Sreeya Guha**
- **Avinash Chowdhary Maddineni**
- **Kriti Srivastava**
- **Qicheng Vincent Zeng**

*Contributors are listed in alphabetical order by last name.
Each team member participated in data cleaning, analysis, and visualization.*

## Acknowledgments

We would like to extend our gratitude to **Dr. Lu Xiao** for her guidance and support throughout this project as part of the CIS 591 course at Arizona State University. Her insights and feedback were invaluable in helping us achieve our project goals.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this code with proper attribution. See the [LICENSE](LICENSE) file for more details.
