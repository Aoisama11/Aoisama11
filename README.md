- 👋 Hi, I’m @Aoisama11
- 👀 I’m interested in trying a new adventure.
- 🌱 I’m currently working on a project.
- 😄 Pronouns: She
- ⚡ Fun fact: The first computer bug was an actual bug!
-  In 1947, computer scientist Grace Hopper and her team found a moth stuck in a relay of the Harvard Mark II computer. They had to "debug" the machine by removing the moth, and this is how the term "bug" became popular for software and hardware glitches.

# World Bank Population Dataset Visualizer

This project is a Python-based data visualization tool designed to analyze and visualize population datasets. It specifically handles **gender-based population data** using three input files:
1. **Main Population Dataset**: Contains overall population data for all countries and years.
2. **Male Population Dataset**: Contains male population data for all countries and years.
3. **Female Population Dataset**: Contains female population data for all countries and years.

The program is built to run in the **Google Colab** environment, leveraging its interactive capabilities for file uploads and data analysis.

## Features
1. **File Upload Support**:
   - Upload three datasets (main, male, and female population) interactively in Google Colab.
2. **Data Preprocessing**:
   - Cleans and reshapes datasets to make them suitable for analysis.
   - Merges the datasets into a single, unified dataset containing male and female population data.
3. **Visualizations**:
   - **Gender Distribution for a Specific Year**:
     - Bar chart comparing male and female populations for a given year (default: 2020).
   - **Gender Trends Over Time**:
     - Line chart showing male and female population trends across all available years.

## Getting Started

### Prerequisites
- Python 3.x
- Libraries:
  - `pandas`
  - `matplotlib`
  - `openpyxl`

You can install the required libraries in Google Colab by running:
```python
!pip install pandas matplotlib openpyxl
```

### Running the Program
1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/).
2. **Copy the Code**:
   - Copy the Python script provided in the repository into a Colab notebook cell.
3. **Upload Files**:
   - When prompted, upload the following three files:
     - Main population dataset.
     - Male population dataset.
     - Female population dataset.
4. **View Visualizations**:
   - The program will generate the following charts:
     - **Gender Distribution for a Specific Year**: A bar chart for male vs. female population.
     - **Gender Trends Over Time**: A line chart showing male and female population trends.

## Example Datasets
Here’s an example of how the datasets should be structured:

### Main Population Dataset
| Country Name | Indicator Name     | 1960   | 1961   | 1962   | ... |
|--------------|--------------------|--------|--------|--------|-----|
| Country A    | Population, total | 100000 | 105000 | 110000 | ... |

### Male Population Dataset
| Country Name | Indicator Name    | 1960   | 1961   | 1962   | ... |
|--------------|-------------------|--------|--------|--------|-----|
| Country A    | Male Population   | 50000  | 52000  | 54000  | ... |

### Female Population Dataset
| Country Name | Indicator Name    | 1960   | 1961   | 1962   | ... |
|--------------|-------------------|--------|--------|--------|-----|
| Country A    | Female Population | 50000  | 53000  | 56000  | ... |

## Code Overview

### File Upload
- The program prompts the user to upload three files interactively in Colab.

### Data Preprocessing
- The datasets are reshaped using `pandas.melt` to convert year columns into rows.
- The male, female, and main datasets are merged into a single dataset for analysis.

### Visualizations
1. **Gender Distribution for a Specific Year**:
   - Compares the male and female population for a specific year.
   - Default year: 2020.
2. **Gender Trends Over Time**:
   - Shows trends in male and female populations across all years.

## Example Outputs
- **Gender Distribution for 2020**:
  ![Example Bar Chart](https://via.placeholder.com/400x300.png?text=Gender+Distribution+Bar+Chart)

- **Gender Trends Over Time**:
  ![Example Line Chart](https://via.placeholder.com/400x300.png?text=Gender+Trends+Line+Chart)

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Contact
For questions or support, please feel free to contact the repository owner or open an issue.
