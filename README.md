# 🎮 Steam Games EDA

Exploratory Data Analysis (EDA) project based on a dataset of games available on the Steam platform. This project is part of my data analyst portfolio and was developed using Python and Jupyter Notebook.

## 📁 Project Structure
```
eda-steam/
├── data/
│   ├── steam_raw.csv           # Original dataset
│   └── steam_cleaned.csv       # Cleaned dataset
├── notebooks/
│   └── steam_eda.ipynb         # Jupyter Notebook with the analysis
├── archive/
│   └── steam_data.zip          # Original compressed file (optional)
```
### 📚 Notebooks Available

- [🇬🇧 English Version](notebooks/steam_eda_ENG.ipynb)
- [🇪🇸 Versión en Español](notebooks/steam_eda_ESP.ipynb)

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## 🧹 Data Cleaning Process

- Removed null values and duplicates
- Converted text columns to appropriate formats
- Created a cleaned version of the dataset for analysis

### 📊 Key Analysis Topics

This EDA addresses the following questions:

1. What are the top 10 most played games?
2. Which is the best-selling video game genre?
3. Which genres have the highest average reviews?
4. How much has the top-selling developer earned?
5. How does being an Early Access title affect review scores?
6. Which developer has released the most games and covered the most genres?
7. In which month (based on available data) were the most games published?
8. How many hours are played on average per game genre each month?
9. Do Free-to-Play games receive better or worse reviews?
10. How has the number of achievements per game evolved over time?

### 🔍 Key Insights

- 🎮 **Top 3 Most Played Games** are *Dota 2*, *PUBG*, and *Counter-Strike*, leading the platform by total playtime.
- 💰 **Best-Selling Genres** include *Action*, *Adventure*, *Strategy*, *RPG*, and *Simulation*.
- ⭐ Genres with the **highest average review scores** are *Action*, *Adventure*, *RPG*, *Strategy*, and *Simulation*.
- 🏆 The **top-selling developers** by revenue are *PUBG Corp.* (€2B), *Valve* (€1.3B), and *CAPCOM* (€0.6B).
- ⚠️ **Early Access games** receive **very positive reviews** on average, indicating community support despite unfinished status.
- 🏗️ *Choice of Games*, *Warfare Studios*, and *Ripknot Systems* are the **most prolific developers** by number and variety of games published.
- 📅 The **month with the highest number of game releases** was **March 2018**, with **787 new titles**.
- ⏱️ Players spend an average of **900 hours/month** on **Action** genre, showing strong long-term engagement.
- 💸 **Free-to-Play games** receive a high average of **83% positive reviews**, suggesting strong player satisfaction.
- 🏅 The **number of achievements per game** increased significantly in **2016**, reflecting a shift in game design towards player engagement.

## 📌 Notes

- All data used is public and comes from a third-party dataset compiled from Steam, covering the period from 1997 to 2019.
- This is a solo project developed for learning and portfolio purposes.

## 👤 Author

**Ferran Piqueras Pons**  
[LinkedIn](https://www.linkedin.com/in/fpiqueraspons/) · [GitHub](https://github.com/Tzantza)

---