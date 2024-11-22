# COVID and Mental Health Analysis

## Purpose
This project analyzes the impact of the COVID-19 pandemic on mental health indicators such as anxiety and depression. Publicly available datasets from Kaggle were used to uncover trends and insights that can guide public health strategies.

Note: Some of the interactive Plotly visualizations in this project may not render correctly on GitHub. To fully experience the interactive features, open the notebook in Google Colab using the link below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aefrank25/COVID-19_Mental_Health_Analysis/blob/main/ASU_MSBA_Team_Project_COVID_and_US_Mental_Health_Trends%20(3).ipynb)

## Implementation
The project was conducted as part of the CIS 591 course at Arizona State University (ASU) under the supervision of Dr. Lu Xiao. Excel was used for data cleaning. Python was utilized for data processing, statistical analysis, and visualization. We focused on identifying patterns across demographics and geographic regions in the United States to better understand the pandemic's impact on mental health.

## Objectives
The main goals of this project are:
- Analyzing trends in anxiety and depression symptoms by demographics (e.g., age, gender).
- Exploring the impact of external factors (e.g., COVID-19 cases, lockdowns) on mental health trends.
- Identifying areas for further research and potential mental health support during pandemic scenarios.

## Steps Involved
1. **Data Collection:** Downloaded public dataset from Kaggle focusing on mental health during COVID-19.
2. **Data Cleaning:** Processed and cleaned the data to ensure consistency and reliability.
3. **Exploratory Data Analysis (EDA):** Conducted EDA to identify trends and outliers.
4. **Visualization:** Created visual representations to illustrate key findings.
5. **Reporting:** Documented findings in reports and presentations.

## Future Steps
- Expand analysis to include additional datasets for more comprehensive insights.
- Implement predictive models to forecast future mental health trends.
- Develop an interactive dashboard to visualize trends in real-time.
- Collaborate with public health experts to interpret findings and propose solutions.

## Data Source
This analysis uses a publicly available dataset on [Kaggle: Indicators of Anxiety or Depression](https://www.kaggle.com/datasets/melissamonfared/indicators-of-anxiety-or-depression), which includes information on mental health symptoms, demographics, and related factors during the COVID-19 pandemic.

### Data Preparation
Before running our analysis, we performed basic cleanup on the original Excel file to remove errors and inconsistencies. To replicate our analysis:
1. Download the dataset directly from Kaggle.
2. Save it in the main directory of this project.
3. Run the Jupyter notebook, which reads and processes the cleaned data as part of the analysis.

*Note*: Due to licensing, the data cannot be redistributed here. Please download it directly from Kaggle and place it in the main directory.

### Processed Data
The specific file used for our analysis, after initial data cleaning, is located in the `CIS 591_Indicators of Anxiety and Depression Data.csv` file. This file includes the dataset in a format ready for analysis. There is also an Excel file included, with the data organized.

## Technologies Used
- **Excel**: Used for initial data cleaning, inspection, and preliminary analysis, including handling missing values, removing duplicates, and organizing data for further 
             processing.
- **Python**: Core programming language for data analysis, visualization, and statistical modeling.
- **Libraries**: 
  - `pandas`: Data manipulation
  - `numpy`: Numerical computations
  - `matplotlib` and `seaborn`: Data visualizations
  - `plotly`: Interactive visualizations
- **Tools**: `Jupyter Notebooks` and `Google Colab` for interactive analysis and visualization.

## How to Use

1. **Clone the Repository**
   <!-- Command to clone the repository -->
  git clone https://github.com/aefrank25/COVID-19_Mental_Health_Analysis.git

2. **Navigate to the Project Directory**
   <!-- Command to navigate to the project directory -->
  cd COVID-19_Mental_Health_Analysis

3. **Refer to [requirements.txt](requirements) for a List of Required Libraries**
  <!-- Install required Python packages -->
  
4. **Run the Jupyter Notebook:**
   Open the file: ASU_MSBA_Team_Project_COVID_and_US_Mental_Health_Trends (3).
   Run the cells sequentially to perform the data analysis and view results.
   
5. **Using Google Colab (Optional):**
   1. Upload the .ipynb notebook file to your Google Colab environment
   2. Add this cell at the start of the notebook to ensure all necessary libraries are installed:
      !pip install pandas numpy matplotlib seaborn plotly
   3. Run all cells in the notebook to execute the analysis.

## Key Findings

Some of the **main insights** from the analysis include:

- **Increased Anxiety and Depression**: There was a *significant rise* in reported symptoms of **anxiety and depression** across *all demographics* during the *early stages* of the COVID-19 pandemic.
- **Younger Adults More Affected**: Individuals aged 18-29 exhibited **higher levels of anxiety and depression**, *compared to older age groups*.
- **Impact of Geographic Location**: Certain *regions* experienced **more pronounced mental health challenges**, correlating with factors like infection rates and lockdown stringency.
- **Economic Factors**: **Unemployment rates** and **financial instability** showed a *strong association* with **increased mental health issues**.

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
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

**Note**: The dataset used in this project is not owned by me and is publicly available on Kaggle. Please refer to the [original dataset](https://www.kaggle.com/) for licensing terms and conditions.
