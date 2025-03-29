# Oyo State Election Analysis Dashboard

This dashboard visualizes the geospatial analysis of the Oyo State election data, highlighting spatial-temporal anomalies, cluster analysis, and vote distribution patterns.

## Features

- Overview of election results
- Geospatial analysis of voting patterns
- Cluster analysis of polling units
- Outlier detection for anomalous voting behaviors
- Historical trends analysis

## Local Setup

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```

## GitHub Actions Deployment Setup

This project includes GitHub Actions to automatically deploy to Streamlit Cloud when you push to the main branch.

### Setup Instructions

1. Create a Streamlit Cloud account at https://streamlit.io/cloud
2. In your GitHub repository settings, go to "Secrets and variables" > "Actions"
3. Add a new repository secret named `STREAMLIT_CREDENTIALS_TOML` containing your Streamlit credentials

## License

[MIT License](LICENSE) 
