# 🚀 Standard Data Analysis Workflow

## 1. Data Loading & Environment Setup
- **Action**: Import essential libraries (`pandas`, `numpy`, `kagglehub`) and fetch the dataset.
- **Goal**: Ensure the environment is ready and the data is loaded without errors.

## 2. Data Cleaning (Pre-processing)
- **Action**: Transform "dirty" raw data into an "analysis-ready" format.
  - Convert currency strings (e.g., `$12,345`) to numeric floats.
  - Reformat `Date` strings into `datetime` objects for time-series analysis.
  - Handle missing values (Nulls) and standardize categorical text.

## 3. EDA (Exploratory Data Analysis)
- **Action**: Discover the underlying patterns and distributions of the data.
  - Use `df.describe()` for summary statistics and check for outliers.
  - Visualize distributions using histograms or box plots.
- **Goal**: Identify hidden anomalies or trends before applying deep logic.

## 4. Business Insight & Question-driven Analysis
- **Action**: Answer key business questions through structured exploration.
  - **Segment & Aggregate**: Use `groupby` to compare performance across dimensions (e.g., Channel, Audience).
  - **Pattern Recognition**: Examine differences, trends, and anomalies in the results.
  - **Cross-verification**: Validate findings using multiple metrics (e.g., checking both ROI and Conversion Rate).
  - **Insight Synthesis**: Consolidate results into concise, evidence-based statements.

## 5. Data Visualization & Insights
- **Action**: Convert complex numbers into a visual story.
  - Generate charts using Python (`Seaborn`, `Plotly`) for deep-dive analysis.

---

# 🚀 Marketing Analytics Framework: By Data Type

| **Data Type** | **Primary Analysis Theme** | **Business Questions & Metrics** |
| --- | --- | --- |
| **Aggregated Data** | **Channel ROI & Budget Optimization** | ROI, CPA, Budget Allocation, Diminishing return |
| **Transaction Data** | **RFM, LTV & Customer Segmentation** | Recency, Frequency, Monetary |
| **User Log Data** | **Funnel & Cohort Analysis** | Conversion Rate, Retention Rate, Drop-off, Churn Rate |
| **Experiment Data** | **A/B Testing & Incrementality** | P-value, Lift, Control vs Test |

