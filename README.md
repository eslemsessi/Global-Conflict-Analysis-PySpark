# Analysis of YouTube Trends: Gaza Conflict (PySpark)

## Project Overview
This project analyzes the digital footprint of news and media trends related to the Gaza conflict using **Apache Spark**. By processing datasets from both the **US and UK markets**, the project identifies high-impact channels and analyzes public engagement through likes and view counts.

## Features
- **Big Data Processing:** Utilizes PySpark for efficient handling of 15,000+ data rows.
- **Cross-Regional Analysis:** Compares trending data between the USA and Great Britain.
- **Data Mapping:** Joins raw CSV metrics with JSON metadata for category identification.
- **Visual Insights:** Generates engagement reports using Seaborn and Matplotlib.

## Tech Stack
- **Language:** Python 3.x
- **Engine:** Apache Spark (PySpark)
- **Environment:** Google Colab / Hadoop Simulation
- **Libraries:** Pandas, Matplotlib, Seaborn

## How to Run
1. Upload the dataset from Kaggle (YouTube Trending Video Dataset).
2. Run the `notebooks/Analysis_Report.ipynb` in Google Colab.
3. Ensure the `US_category_id.json` is in the root directory for category mapping.

## Conclusion
The analysis reveals that 'News & Politics' remains the primary driver of content, with significant engagement spikes in international news outlets compared to local creators.
