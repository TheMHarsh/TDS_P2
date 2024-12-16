# Tools in Data Science - Project 2

## Project Synopsis

This project involves the automated analysis of datasets using Python. The primary goal is to load, analyze, visualize, and generate narratives for different datasets using a combination of data science libraries and a language model API.

### Key Steps:

1. **Environment Setup**:
   - Load environment variables from a `.env` file.
   - Install necessary dependencies listed in `requirements.txt`.

2. **Data Loading**:
   - Load CSV datasets with encoding detection using the `chardet` library.

3. **Data Analysis**:
   - Perform basic data analysis including summary statistics, missing values detection, and correlation matrix computation.
   - Use a language model API to suggest further analysis techniques and generate detailed narratives based on the analysis results.

4. **Visualization**:
   - Generate visualizations such as distribution plots and correlation heatmaps using `seaborn` and `matplotlib`.
   - Save the visualizations in the respective dataset directories.

5. **Narrative Generation**:
   - Generate a narrative for each dataset using the language model API.
   - Save the narrative along with embedded visualization links in a `README.md` file within the dataset directory.