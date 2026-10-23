# Global Music Streaming Listener Preferences | Python EDA

## 📌 Project Overview
This project explores global music-streaming listener preferences using Python and Exploratory Data Analysis (EDA). It examines listener demographics, streaming-platform usage, favourite music genres, listening times, subscription types, and most-played artists to identify patterns in the available dataset.

The objective is to transform raw data into meaningful insights that support data-driven understanding of music-listening behaviour.

## 🎯 Business Objectives
- Analyse the age distribution of listeners.
- Identify the most frequently used streaming platforms.
- Explore the distribution of listeners' favourite music genres.
- Understand listening preferences across morning, afternoon, and night.
- Examine the relationship between most-played artists and subscription types.
- Compare music-genre preferences across different age groups.

## 🛠️ Tools & Technologies
- **Python** – Data analysis and exploratory analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computing
- **Matplotlib** – Data visualisation
- **Seaborn** – Statistical visualisation
- **Jupyter Notebook / Google Colab** – Development environment

## 📂 Dataset Overview
The project uses a dataset named `Global_Music_Streaming_Listener_Preferences.csv`.

The analysis references the following fields:
- Age
- Country
- Streaming Platform
- Top Genre
- Listening Time (Morning/Afternoon/Night)
- Most Played Artist
- Subscription Type
- Minutes Streamed Per Day
- User_ID

The dataset is used to explore listener demographics, platform preferences, music genres, and streaming behaviour.

**Note:** The CSV dataset is required to execute the notebook. Ensure that the dataset is available at the file path specified in the notebook. Share the dataset publicly only if its licence or source permits redistribution.

## 🔍 Project Workflow

### 1. Data Loading & Inspection
- Load the dataset using Pandas.
- Review the dataset structure and descriptive statistics.
- Inspect missing values and duplicate records.
- Examine unique values and categorical variables.
- Remove the User_ID column from the working DataFrame when present.

### 2. Univariate Analysis
Analyse individual variables through visualisations:
- Age distribution using a histogram with a density curve.
- Streaming-platform frequency using a count plot.
- Favourite music genres using a pie chart.
- Listening-time preferences using a count plot.

### 3. Bivariate & Multivariate Analysis
- Compare the most-played artists across subscription types.
- Visualise genre preferences across age groups using a heatmap.
- Group records by subscription type to examine the availability of streaming-minute data.

## 📊 Key Visualisations

| Visualisation | Purpose |
|---|---|
| Age Distribution Histogram | Understand the distribution of listener ages |
| Streaming Platform Count Plot | Compare the frequency of streaming platforms |
| Favourite Genre Pie Chart | Explore the distribution of music genres |
| Listening Time Count Plot | Examine listening-time preferences |
| Artist vs. Subscription Type | Compare artist counts across subscription categories |
| Age Group vs. Genre Heatmap | Identify genre-count patterns across age groups |

## 💡 Business Relevance
This analysis demonstrates how exploratory data analysis can help organise and interpret customer-preference data. Similar analytical approaches can support audience segmentation, customer behaviour analysis, and preference-based business decisions.

The project focuses on descriptive patterns in the available dataset; it does not establish causal relationships or prove that the results represent all music-streaming users.

## ▶️ How to Run the Project

### Option 1: Google Colab
1. Open the `.ipynb` notebook in Google Colab.
2. Upload `Global_Music_Streaming_Listener_Preferences.csv`.
3. Ensure the CSV path matches the path used in the notebook.
4. Execute the notebook cells sequentially.
5. Review the generated tables and visualisations.

### Option 2: Run Locally
1. Clone or download the repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Place the CSV dataset in the project directory.
4. Update the dataset path in the notebook if required.
5. Launch Jupyter Notebook and execute the cells.

## ⚠️ Limitations
- The analysis depends on the quality and coverage of the source dataset.
- Missing values and duplicates are inspected, but not every potential data-quality issue is addressed through a comprehensive cleaning pipeline.
- The subscription-type analysis counts non-null streaming-minute records; it does not calculate average or total streaming minutes.
- Results are descriptive and should not be interpreted as causal findings.
- Specific business conclusions should be added only after validating the notebook's actual outputs.

## 🧠 Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data Cleaning and Quality Checks
- Python Programming
- Pandas Data Manipulation
- Descriptive Statistics
- Data Visualisation
- Categorical Data Analysis
- Grouping and Aggregation
- Analytical Thinking and Business Interpretation

## 👨‍💻 Author
**Koushik Dubey**

This project is part of my Data Analytics portfolio and demonstrates my ability to explore datasets, analyse patterns, create visualisations, and communicate findings using Python.

---

*If you find this project useful, feel free to explore the notebook and its analysis.*
