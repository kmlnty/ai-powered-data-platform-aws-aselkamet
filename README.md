AI-Powered Data Platform (AWS Simulation)
**Author:** Asel Kamet
**Course:** AWS Data Engineering Midterm Project **Date:** May 2025
Project Overview
This project simulates an AI-powered data platform using cloud-style architecture inspired by AWS.
It processes **multi-modal data** including text (reviews), images, and time-series sales and applies machine learning models for analysis and forecasting.
All results are visualized through a simulated dashboard.
Technologies Used
- Python 3.9+
- pandas (ETL)
- TextBlob (NLP sentiment analysis) - Prophet (time-series forecasting)
- PIL (image processing)
- Streamlit (dashboard)
- smtplib (SNS/SES simulation)
Project Structure
ai_platform_main.py unified_run.ipynb data/
sales.csv
sample_image.jpg
short_report.pdf
aselkamet_academic_report.pdf # Academic report presentation.pptx # Final presentation slides
# Unified script for full pipeline # Jupyter version of pipeline
# Time-series sales data
# Image for CV simulation
# Main report (4 pages)
architecture_diagram.png bonus_features.pdf bonus_code_examples.py README.md
# AWS-style architecture diagram
# Bonus tasks (Step Functions, IAM, SES)
# Bonus code samples # You are here
How to Run This Project
### 1. Install requirements
pip install pandas textblob pillow prophet streamlit
### 2. Run full pipeline python ai_platform_main.py
### 3. Launch the dashboard
streamlit run dashboards/streamlit_app.py
Bonus Features
- Simulated **Step Functions** orchestration (`run_pipeline()`)
- **SNS/SES** email notification using Python's `smtplib`
- Example **IAM policy** in JSON format (role-based access control)
Demo Video
> 5-minute walkthrough with voice showing the platform in action
Author

**Asel Kamet**
Engineering and Natural Sciences Faculty [GitHub Profile](https://github.com/kmlnty)
