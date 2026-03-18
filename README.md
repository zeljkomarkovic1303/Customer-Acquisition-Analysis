⚙️ Installation & Setup
Clone the repository

or download the ZIP file from GitHub.

Ensure Dataset Placement
Make sure the Customer Acqusition.csv file is in the same directory as the .ipynb notebook.

Install Dependencies
If running locally, install the required libraries:

Run the analysis
Open the notebook in VS Code, Jupyter, or upload it to Google Colab and click Run All.

Workflow Overview
The analysis follows a structured data pipeline:

Data Loading: Importing datasets and inspecting initial structures (df.head(), df.info()).

Preprocessing: Detecting null values (df.isna()) and correcting data types.

Segmentation: Grouping customers by City, Product Type (Gold/Silver/Platinum), and Segment.

Visualization: Generating count plots and bar charts to identify key business trends.

Key Insights
Customer Demographics: Distribution of "Salaried" vs "Self-Employed" clients across major cities.

Credit Analysis: Understanding the correlation between product tiers and assigned credit limits.

Product Popularity: Visualizing which card types are most frequently acquired.

Requirements
Python 3.7 or newer

Pandas & NumPy

Matplotlib & Seaborn

Jupyter Notebook environment

Academic Purpose
This project was developed as a practical assignment to demonstrate:

Proficiency in Python for data science.

Ability to work with real-world CSV datasets.

Skills in data visualization and interpretation.

Clean and documented coding practices.

Future Improvements
Integrate Machine Learning models to predict customer segments.

Add deeper time-series analysis if date data is available.

Develop an interactive dashboard using Streamlit.

License
This project is developed for educational purposes.
