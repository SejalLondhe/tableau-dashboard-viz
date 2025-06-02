## 📊 Anime Analytics Dashboard (Tableau Project)
This project presents a comprehensive Anime Analytics Dashboard built using Tableau, leveraging a rich dataset sourced from Kaggle. It provides deep insights into anime popularity, viewer preferences, quality ratings, seasonal trends, and more.

### 📁 Dataset
Source: Kaggle - Anime Dataset ( https://www.kaggle.com/datasets/bhavyadhingra00020/top-anime-dataset-2024 )


### 📌 Key Visualizations
**1. Anime Type Breakdown by Popularity Score**
Shows how different types (TV, Movie, Specials) contribute to overall popularity.

**2. Viewer Preferences Based on Anime Length**
Displays preference trends between short and long anime formats.

**3. Target Audience Distribution**
Breakdown of anime targeted toward Kids, Teens, and Adults.

**4. Top-Rated Anime by Number of Members**
Highlights the most popular anime titles with the highest member engagement.

**5. Anime Quality Score Distribution**
Categorizes anime into "Excellent", "Good", and "Masterpiece" based on scores.

**6. Anime Popularity by Rating**
Visualizes popularity segmented by rating categories like PG-13, R, G, etc.

**7. Popularity Rise Over Decades**
Tracks the growth of anime popularity from 1999 to 2024.

**8. Seasonal Trends**
Displays anime popularity trends across different seasons (Spring, Fall, etc.).

### 🧹 Data Preprocessing Steps
Before building the Tableau dashboard, the raw Kaggle anime dataset was thoroughly cleaned and transformed using Microsoft Excel. Below are the key steps followed to prepare the data for visualization:

**🔸 1. Rating Category Simplification**
Many anime entries had long or compound rating descriptions. These were simplified to extract the main rating category (e.g., PG-13, R, G) to enable clearer filtering and analysis based on content suitability.

**🔸 2. Duration Normalization**
Anime durations were originally recorded in various formats such as "1 hr. 30 min.", "24 min.", or "Unknown". These were standardized into total minutes to allow consistent comparison of episode lengths and viewer preferences.

**🔸 3. Genre Cleanup**
The genre column often had repeated or concatenated genres due to data duplication (e.g., "ActionAction", "DramaDrama"). These were cleaned to ensure each genre appeared only once per anime entry, improving accuracy in genre-based visualizations.

**🔸 4. Year Extraction**
Many entries included a full date range for the anime’s airing period (e.g., "Jan 2021 to Mar 2021"). Only the starting year was extracted to analyze trends across different years and decades.

**🔸 5. Season Identification**
From the airing dates, the release season (Spring, Summer, Fall, Winter) was identified. This enabled seasonal trend analysis to determine which times of year see the highest anime releases and popularity spikes.

**🔸 6. Weekday Analysis**
The exact day of the week (e.g., Monday, Friday) of the anime's release was derived. This helped in understanding if any particular day tends to have more releases or higher popularity.

**🔸 7. Handling Missing and Inconsistent Data**
Missing or non-standard entries (like "Unknown" or blank cells) were cleaned or replaced with defaults where appropriate.

Text fields were trimmed and standardized for better grouping and filtering in Tableau.



### 🛠 Tools Used
**Tableau** for interactive dashboard creation

**Kaggle Dataset** for real-world anime data

Data Preprocessing using **Tableau built-in tools and Excel** 


### 📌 Insights Gained
TV anime leads in popularity.

Teens are the dominant target audience.

PG-13 rated anime is most prevalent and popular.

Anime popularity has significantly increased since the 2010s.

Fall and Spring seasons see higher anime releases and viewer engagement.


#### 📩 Credits
Dataset: Kaggle Anime Dataset

Created By: Sejal Londhe and Chithira M
