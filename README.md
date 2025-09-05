Virat Kohli IPL Performance Analysis

📖 Overview

This project provides an in-depth statistical analysis of Virat Kohli's performance throughout his Indian Premier League (IPL) career up until 2024. By leveraging Python's data analysis and visualization libraries, this project explores various facets of his batting statistics, including performance against different oppositions, at various venues, and across different seasons.

The analysis is conducted within a Google Colab notebook (PROJECT_VIRAT.ipynb), which details each step of the data cleaning, exploration, and visualization process.

📊 Analysis Covered
The analysis delves into several key performance indicators, including:

Overall Career Summary: A look at his aggregate runs, strike rate, average, boundaries, and other career milestones.

Performance vs. Opposition: A detailed breakdown of his batting record against every IPL team.

Dismissal Analysis: Investigating the modes of dismissal and the bowlers who have dismissed him most frequently.


🛠️ Technologies Used
This project utilizes the following technologies and Python libraries:

Python 3.x

Google Colab

seaborn

matplotlib: For visual representations.

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

🚀 How to Run this Project
You can run this project either on Google Colab or on your local machine.

Option 1: Running on Google Colab (Recommended)
Navigate to Google Colab.

Go to File > Upload notebook and select the PROJECT_VIRAT (2).ipynb file.

On the left-hand side, click the "Files" icon to open the file browser.

Click the "Upload to session storage" icon and upload your dataset (e.g., virat_kohli_ipl.csv).

You can now run the notebook cells. Google Colab comes with most of the required libraries pre-installed.

Option 2: Running Locally
Clone the Repository:

git clone [https://github.com/your-username/virat-kohli-ipl-analysis.git](https://github.com/your-username/virat-kohli-ipl-analysis.git)
cd virat-kohli-ipl-analysis

Create a Virtual Environment (Recommended):

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install Dependencies:
Make sure you have a requirements.txt file with the necessary libraries.

pip install -r requirements.txt

If you don't have a requirements.txt file, you can install the libraries manually:

Seaborn: For making statistical graphics more attractive and informative.

📄 Dataset
The analysis is based on a dataset containing ball-by-ball information of Virat Kohli's IPL career. The dataset includes columns such as:
match_id	inning	batting_team	bowling_team	over	ball	batter	bowler	non_striker	batsman_runs	extra_runs	total_runs	extras_type	is_wicket	player_dismissed	dismissal_kind	fielder.

Note: Please ensure the dataset file (e.g., virat_kohli_ipl.csv) is present in the project directory for the notebook to run correctly.
