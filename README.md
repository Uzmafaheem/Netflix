# 📊 Netflix Titles EDA: In-Depth Exploratory Data Analysis
A comprehensive analysis of Netflix’s content library using data cleaning, transformation, visualization, and text analysis techniques.

## 🚀 Project Objective
The goal of this project is to perform a full exploratory data analysis (EDA) of the Netflix Titles dataset.
We investigate:

- Content distribution (Movies vs TV Shows)

- Trends in release years and the years titles were added to Netflix

- Content ratings over time

- Genre popularity

- Top contributing countries

- Duration patterns

- Text analysis of descriptions

- Identification of top directors & key contributors

This project demonstrates skills in data preprocessing, time-series analysis, text mining, visualization, and feature engineering.

## 📈 Business Impact 

This EDA provides valuable insights into Netflix’s content strategy and helps guide data-driven decisions. It highlights how Netflix prioritizes movies, mature-audience content, and globally diverse productions, especially from the US and India. Trends in release years, content age, genres, and ratings help identify what types of titles Netflix invests in and when. These insights can support decisions in content acquisition, production planning, audience targeting, and market expansion.

## 🧠 Concepts Covered
🔧 Data Cleaning & Transformation

- Handling missing values (director, cast, country, date_added, rating)

- Converting date columns to datetime format

- Splitting multi-value text fields (e.g., genres, cast)

## 📈 Time-Series Analysis

- Studying growth of content over time

- Release year vs year added to Netflix

- Content age distribution

🧹 Feature Engineering

- Creating content age: year_added – release_year

- Extracting components from dates (year, month)

## 🔤 Text Data Analysis

- Word frequency analysis

- Word cloud

- Bigram (word pair) extraction

## 🌍 Geographical & Rating Analysis

- Top producing countries

- Distribution of maturity ratings

## 🎨 Advanced Visualization

- Bar charts, line plots, boxplots, heatmaps, word clouds

- Genre explosion analysis

## 📁 Dataset Overview

- Total Records: 7,787 titles

- Types: Movies (~70%), TV Shows (~30%)

Key Columns:

       - type, title, director, cast, listed_in, release_year, date_added, rating, country, duration, description

## 🧹 Data Cleaning Summary
Key fixes:

- Filled missing director and cast with "Unknown"

- Filled missing country with mode

- Dropped null date_added and rating (~0.2% rows)

- Converted date_added → datetime

## 🔍 Key Questions Explored
1️⃣ How has the distribution of content ratings changed over time?

- Netflix content surged between 2016–2019, especially in TV-14, TV-MA, and TV-PG categories.

2️⃣ Is there a relationship between content age and type (Movie vs TV Show)?

- Movies are usually added the same year they release.

- TV Shows show a much wider age range—Netflix frequently acquires older series.

3️⃣ Trends in release year vs year added to Netflix

- Strong spike at age 0 → Netflix Originals

- Long tail → Classic licensed content

4️⃣ Most common word pairs in descriptions

- Themes center around:

- Life, family, love, young, friends

- Action/buildup words: find, new, secret

5️⃣ Who are the top directors on Netflix?

- Top listed directors (excluding “Unknown”):

Jan Suter (21)

Raúl Campos (19)

Marcus Raboy (16)

Martin Scorsese (12)

Steven Spielberg (10)

## 📊 Key Findings
🎬 1. Content Strategy

- Movies dominate the catalog (~70%).

- Massive growth from 2016–2019 (content expansion era).

- Balanced mix of originals + licensed content.

## 🌍 2. Global Dominance

- USA leads in content production.

- India is the second-largest contributor.

- UK, Japan, and South Korea follow.

## 🔞 3. Rating Distribution

- Most content is for mature audiences:

- TV-MA and TV-14 dominate.

## 🎞️ 4. Content Duration

- Movies mostly between 80–120 minutes.

- Majority of TV shows have only 1 season.

## 🎭 5. Genre Popularity

Top genres:

- International Movies

- Dramas

- Comedies

- Action & Adventure

## 📝 6. Textual Themes

Descriptions highlight universal themes:
- life, family, love, friends, world, young, new, secret

## ⏳ 7. Content Age

- Large spike at age 0 → Netflix Originals

- Long tail → Older licensed content

## 📌 Limitations

- Dataset is a snapshot, not updated continuously

- No viewership/ratings → cannot measure popularity

- Some metadata (e.g., director) missing extensively

## 🏁 Final Conclusion

This Netflix EDA project provides a detailed view of Netflix’s content strategy, genre preferences, global expansion, and maturity-level focus. The analysis reveals a strong push toward international content, mature audiences, and original programming. Despite dataset limitations, the insights offer a comprehensive understanding of the platform’s evolving content landscape.

## 📜 Code Included

- ✔ Data cleaning
- ✔ Transformation
- ✔ Genre explosion
- ✔ Time-series plots
- ✔ Rating distribution
- ✔ Word cloud & bigrams
- ✔ Top directors
- ✔ Boxplots, barplots, line charts
  
## 📜 How to Run the Notebook
  - Open Jupyter or Google Colab
  - Run all cells in order

## 📌  Tools Used
- Python
- pandas
- numpy
- seaborn
- matplotlib

## 📊 YData Profiling Report

Full automated profiling report is available here (Download):

- 👉 View Netflix YData Profiling Report: [https://github.com/Uzmafaheem/Netflix/blob/main/netflix_eda_report.html] 

## 🧑‍💻 Author
Faheemunnisa Syeda

- 📧 Contact: [syedafaheem56@gmail.com]

- 🔗 GitHub: [https://github.com/syedafaheem7/]

- 🔗 linkedln: [https://www.linkedin.com/in/faheem-unnisa-s-6270888b/]
