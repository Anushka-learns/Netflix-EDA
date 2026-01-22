# Netflix-EDA
📊 Netflix Content Strategy Analysis (EDA)

📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on Netflix’s content catalog to uncover trends in content production, genre distribution, and regional focus. The goal is to derive data-backed strategic insights that can inform content investment decisions.
The analysis focuses on what Netflix should invest in next, rather than just describing the dataset.

🎯 Objectives
-Analyze content growth trends over time
-Compare Movies vs TV Shows to identify strategic shifts
-Identify dominant and underrepresented genres
-Explore regional and international content distribution
-Provide actionable recommendations based on data

Dataset
Source: Netflix Titles Dataset (CSV)
Size: ~8,800 titles
Features include:
	type (Movie / TV Show)
	date_added
	country
	listed_in (genres)
	duration

🧹 Data Cleaning & Preprocessing

Key preprocessing steps:

Extracted year from date_added
	Cleaned duration column by separating:
  
	Movie duration (minutes)
  
	TV show duration (seasons)
  
Split multi-valued columns:

	Genres (listed_in)
  
	Countries (country)
  
Removed nulls and inconsistencies for accurate analysis

🔑 Key Insights (Humanized & Decision-Focused)

-Netflix’s content strategy shows a clear shift beginning around 2016, where TV shows started growing faster than movies. This isn’t accidental. TV shows encourage repeat engagement, longer watch time, and higher retention compared to one-off films. The data strongly suggests that Netflix’s growth strategy aligns more with episodic, long-form content than standalone movies.

-When looking at genres, Netflix’s catalog is heavily concentrated in a small number of popular categories, indicating possible saturation. While these genres perform well, over-reliance on them may limit future growth unless Netflix diversifies into underrepresented genres with rising demand.

-A deeper look at international content reveals an important imbalance. International movies form a large portion of the catalog, with the United States acting as a major hub for hosting and distributing this content. However, international TV shows are comparatively underrepresented, despite global audiences increasingly favoring localized, serialized storytelling.

-Finally, regional analysis highlights that several countries have high content volume but low genre diversity. This suggests missed opportunities where Netflix could invest in region-specific originals across new genres, rather than replicating the same content mix globally.

Overall insight:
Netflix’s strongest growth opportunity lies in expanding international TV series, particularly in underrepresented genres and regions, while continuing to prioritize TV shows as a core driver of long-term user engagement.

🛠️ Tools & Technologies

-Python

-Pandas, NumPy

-Matplotlib, Seaborn

-Jupyter Notebook

🚀 How to Run

1.Clone the repository

2.Install required libraries

3.Open netflix_eda.ipynb in Jupyter Notebook

4.Run cells sequentially
