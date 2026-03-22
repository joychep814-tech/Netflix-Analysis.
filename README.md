Netflix Content Strategy & Recommendation Engine
A data science project analyzing over 8,000+ Netflix titles to uncover content trends and build a movie recommendation system.

🚀 Project Overview
This project explores the evolution of Netflix's library. Using Python, I performed exploratory data analysis (EDA) to visualize growth patterns and geographical distribution. I also implemented a Machine Learning recommender that suggests movies based on plot similarities.

🛠️ Tech Stack
Language: Python 3

Libraries: Pandas (Data Manipulation), Matplotlib/Seaborn (Visualization), Scikit-Learn (Machine Learning)

Environment: Google Colab / Jupyter Notebooks

📊 Key Insights
Content Spike: Identified a massive shift toward original production starting in 2016.

Library Composition: 70% of the current catalog consists of "Modern" titles (released after 2015).

Global Hubs: Outside of the US, India and the UK are the largest contributors to the platform.

🤖 Machine Learning Feature
I built a Content-Based Recommender using TfidfVectorizer and Cosine Similarity.

Input: A movie or TV show title.

Logic: The engine analyzes the description and genres to find the 5 most statistically similar titles.
