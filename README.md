# Electric Vehicle Market Segmentation in India
This repository presents an in-depth segmentation analysis of the Electric Vehicle (EV) market in India, with a focus on the two-wheeler segment. The analysis leverages multiple datasets to provide insights into vehicle specifications, market trends, and consumer preferences to help a startup identify key market segments.

# Table of Contents
  Introduction
  Contents
  Datasets
  Analysis Overview
  Key Findings
  Dependencies
  Installation
  Usage
  Future Scope

# Introduction
With the rise in environmental consciousness and government incentives, India's EV market, particularly the two-wheeler segment, is booming. This repository uses data from multiple sources to analyze the market landscape and segment the customer base. The project aims to aid an EV startup in identifying potential customers, understanding their needs, and positioning their products effectively.

# Contents
Report.pdf: A detailed report outlining the analysis, insights, and recommendations.
ev_segmentation.ipynb: A Jupyter notebook with Python code for data preprocessing, analysis, and clustering.
Data/: Directory containing the datasets used for analysis.
# Datasets
smev_data.xlsx: Contains data on electric vehicle market trends, state-wise distribution, and sales figures for electric two-wheelers in India.

ev_model_spec.csv: A dataset featuring detailed specifications of various electric vehicle models, including price, mileage, battery capacity, and top speed.

ev2_bikewale.csv: Contains technical specifications and performance metrics for different electric two-wheeler models listed on BikeWale, a prominent online platform for vehicle comparisons.

Each dataset plays a crucial role in understanding the market dynamics, consumer preferences, and technical specifications of the vehicles.

# Analysis Overview
This project uses a structured approach to segment the EV market based on technical specifications, sales data, and customer preferences.

# Steps Involved:
Data Preprocessing: Cleaning and standardizing the datasets for consistency.
Exploratory Data Analysis (EDA): Uncovering insights into sales trends, state-wise distributions, and key factors influencing customer choices.
Principal Component Analysis (PCA): Used to reduce dimensionality and focus on key factors.
KMeans Clustering: Market segmentation based on vehicle features such as price, battery life, mileage, and performance metrics.
Visualization: Clear visualizations to depict trends, segmentations, and market opportunities.
Key Findings
Growth in Two-Wheeler Segment: The two-wheeler electric vehicle market in India has seen consistent growth, with certain states showing faster adoption.
Consumer Preferences: Consumers lean toward two-wheeler EVs that offer better mileage, longer battery life, and higher top speeds at a competitive price.
State-wise Insights: Some states are leading in terms of adoption, which could be useful for market entry strategies.
Detailed findings and analysis can be found in the Report.pdf file.

# Dependencies
The following Python libraries are required to run the analysis:

numpy
pandas
matplotlib
seaborn
scikit-learn
# Installation
To set up the project locally, follow these steps:

# Clone the repository:

bash
Copy code
git clone https://github.com/DebiPrasadMohanty/Electric-Vehicle-Market-Segmentation.git
cd Electric-Vehicle-Market-Segmentation
Set up a virtual environment (optional but recommended):

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
# Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy code
jupyter notebook ev_segmentation.ipynb
# Usage
Open the ev_segmentation.ipynb notebook in your Jupyter environment.
Follow the step-by-step code execution for data preprocessing, EDA, PCA, and clustering.
Review the visualizations and segmentations provided in the notebook.
# Future Scope
Three- and Four-Wheeler Segment Analysis: Extend the study to include three- and four-wheeler segments, as the EV market expands beyond two-wheelers.
Predictive Models: Use predictive models to forecast future sales and market trends.
Consumer Behavior Analysis: Include more granular data on consumer behavior, charging infrastructure, and policy effects on EV adoption.
