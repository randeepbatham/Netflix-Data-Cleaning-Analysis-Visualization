## Netflix Data: Cleaning, Analysis & Visualization

### Project Type:
Data Analyst / Data Science (EDA & Visualization Project)

### Project Overview
This project analyzes Netflix’s catalog from 2008 to 2021 using data analysis and visualization techniques. We explore the distribution of content, trends over time, genre popularity, country-wise breakdown, and more.

### Tools & Technologies
* Python (Pandas, NumPy)
* Visualization: Seaborn, Matplotlib, WordCloud
* Google Colab
* Dataset Source: Kaggle Netflix Titles Dataset

### Data Preprocessing
* Converted date_added to datetime
* Handled missing values in director, cast, and country
* Removed duplicate entries
* Created new features:
  * genre_count: number of genres per title
  * duration_minutes (Movies), num_seasons (TV Shows)
 
### Visualizations & Key Insights
#### 1. Content Type Distribution
  * ~6,000 Movies and ~2,500 TV Shows
  * Netflix's content strategy leans heavily toward movies.
#### 2. Top 10 Content Release Years
  * Peak content release in 2018 followed by 2019 and 2020.
#### 3. Top 10 Content Release Years
  * United States dominates (47.8% of total titles).
  * India and UK follow.
#### 4. Most Common Genres
  * International Movies (21.7%) and Dramas (19.1%) are the most represented.
#### 5. Top 10 Directors
  * Over 2,500 titles have missing director info.
  * Among known ones, Rajiv Chilaka tops the list.
#### 6. WordCloud of Titles
  * Words like “girl”, “Christmas”, and “movie” frequently appear in titles.

### Feature Engineering
* genre_count: total genres per show/movie.
* duration_minutes: extracted from duration for movies.
* num_seasons: extracted for TV Shows.


### Conclusion
Netflix's content catalog is heavily movie-focused with a dominant presence from the US. The platform favors international, dramatic, and family-oriented content. This project demonstrates the use of Python-based data analysis, preprocessing, and effective storytelling with visualizations.


### Screenshots
![Screenshot 2025-05-30 182414](https://github.com/user-attachments/assets/b51fa417-ffdf-45d1-8fa7-df611f790942)

![Screenshot 2025-05-30 182453](https://github.com/user-attachments/assets/35f52e10-1d32-428c-b138-586f9fc788d7)

![Screenshot 2025-05-30 182516](https://github.com/user-attachments/assets/a3281b62-5eb7-40fe-89dd-6c12734bc7c0)

![Screenshot 2025-05-30 182547](https://github.com/user-attachments/assets/8b6945d2-3c81-4a8a-a3dc-a6e3d4b72bba)

![Screenshot 2025-05-30 182602](https://github.com/user-attachments/assets/27688524-b7a7-4aee-9f36-1ca77477a5e7)


