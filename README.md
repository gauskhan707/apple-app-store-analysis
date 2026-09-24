# Apple App Store — Exploratory Data Analysis

End-to-end exploratory analysis of the Apple App Store dataset, focused on data quality, feature engineering, business questions, visualization, and interpretation.

## Project scope

- ~1.2M / 1.23M app records are described in the source analysis
- 21 attributes
- 16 business-focused questions
- Data cleaning and validation
- Feature engineering (app size, free/paid classification, content-rating grouping)
- Category, downloads, ratings, pricing, reviews, developer activity, and release-trend analysis
- Matplotlib and Seaborn visualizations
- SciPy referenced for scientific/statistical analysis

## Dataset

The source analysis identifies the Kaggle **Apple AppStore Apps** dataset, collected in October 2021:

https://www.kaggle.com/datasets/gauthamp10/apple-appstore-apps

The raw dataset is **not bundled** in this repository. Download it from the source above and place it where the notebook expects it (or update the path in the notebook).

## Key findings documented in the source analysis

- Games dominate app volume/download-related measures in the analysis.
- Weather is reported as having the highest average user rating among genres in the analyzed data.
- 2020 is reported as the year with the highest number of app releases.
- App size shows little relationship with price in the correlation/visual analysis.
- Educational apps are reported as having comparatively high revenue in the analyzed dataset.
- The source analysis flags noise/limitations in the `Content_Rating` field.

These are findings from the supplied source analysis; they are not presented as current App Store statistics.

## Repository structure

```text
apple-app-store-analysis/
├── README.md
├── .gitignore
├── requirements.txt
├── notebooks/
│   └── apple_app_store_eda_reconstructed.ipynb
└── reports/
    └── apple_app_store_eda_report.html
```

## Tech stack

Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy · Jupyter

## Notes

This GitHub package was reconstructed from the archived project/workbook content available in the user's Library because the original Apple project archive was not available to re-upload in the current chat. The reconstruction preserves the documented analysis rather than inventing new results.
