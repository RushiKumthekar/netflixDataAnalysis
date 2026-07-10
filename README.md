# Netflix Content Analysis 🎬

An Exploratory Data Analysis (EDA) project focusing on the global Netflix media catalog. This project profiles the dataset to clean missing information, analyze content distributions, and uncover trends across movies and television shows.

## 📌 Project Overview
The goal of this project is to explore and understand the content strategy of Netflix. By inspecting the dataset attributes, this analysis addresses core questions regarding how content is distributed across different formats, target audiences, and production hubs.

The analysis follows a clear three-step workflow:
1. **Data Assessment**: Reviewing the dataset structure, total records, and characteristics of each attribute.
2. **Data Cleaning**: Identifying and quantifying missing values across the dataset to understand where data gaps exist (such as missing director or cast details).
3. **Exploratory Analysis**: Filtering and querying the data to find specific trends, such as content breakdowns by country and age ratings.

---

## 📊 Dataset Overview
The analysis is performed on a dataset containing **8,807 unique titles** with **12 core attributes**:
* `show_id`: Unique identifier for each entry.
* `type`: Categorical identifier separating entries into **Movies** or **TV Shows**.
* `title`: The official title of the film or show.
* `director`: The director(s) involved in the production.
* `cast`: Main actors featured in the content.
* `country`: Country or countries where the content was produced.
* `date_added`: The date the title was made available on Netflix.
* `release_year`: The original release year of the production.
* `rating`: The target audience age rating (e.g., TV-MA, PG-13, R).
* `duration`: Running time (measured in minutes for movies or seasons for TV shows).
* `listed_in`: Associated genres and thematic categories.
* `description`: A brief summary of the plot.

---

## 📈 Key Findings & Insights

* **Missing Data Profile**: A significant portion of the dataset lacks specific details. For instance, over 2,600 titles are missing a listed director, and more than 800 entries lack explicit country or cast details.
* **Audience Distribution**: The catalog is heavily geared toward mature audiences, with `TV-MA` emerging as the most frequent maturity rating in the dataset (accounting for over 3,200 titles).
* **Targeted Filtering**: The analysis demonstrates the ability to drill down into highly localized segments, successfully isolating specific subsets such as Canadian-produced movies tailored for a TV-14 audience.

👨‍💻 About the Author
Hrushikesh Nitin Kumthekar 🎓 MSc in Data Analytics | National College of Ireland (Dublin, Ireland)

💻 Computer Engineering Graduate I design structured analytics pipelines and turn unstructured, messy datasets into clear, business-driven database solutions. This repository serves as a hands-on demonstration of my skills in PostgreSQL database schema configuration, target data manipulation, pipeline sanitization techniques, and downstream business intelligence metrics extraction.

🚀 Connect With Me
LinkedIn: linkedin.com/in/rnk89
GitHub: github.com/RushiKumthekar

---

## 🛠️ Tools Used
* **Python**: Used for writing the analysis logic.
* **Pandas & NumPy**: Used for structuring, cleaning, and filtering the tabular data.
* **Matplotlib & Seaborn**: Used for generating visual representations and charts of the trends.

---

## 👨‍💻 About the Author

**Hrushikesh Nitin Kumthekar** 🎓 **MSc in Data Analytics** | National College of Ireland (Dublin, Ireland)

💻 **Computer Engineering Graduate** I design structured analytics pipelines and turn unstructured, messy datasets into clear, business-driven database solutions. This repository serves as a hands-on demonstration of my skills in PostgreSQL database schema configuration, target data manipulation, pipeline sanitization techniques, and downstream business intelligence metrics extraction.
