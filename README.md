# 🎮 Video Game Sales & Ratings Analysis

## 🔍 Overview
This project analyzes a dataset of video games, exploring sales, ratings, and user reviews across different platforms and genres.  
It includes **data preparation, hypothesis testing, and insights** about the video game industry.

## 📊 Dataset
The dataset (`games.csv`) contains:
- **Name** – Video game title  
- **Platform** – Console/platform  
- **Year_of_Release** – Release year  
- **Genre** – Game genre  
- **NA_sales** – Sales in North America (millions USD)  
- **EU_sales** – Sales in Europe (millions USD)  
- **JP_sales** – Sales in Japan (millions USD)  
- **Other_sales** – Sales in other regions (millions USD)  
- **Critic_Score** – Professional reviews (0–100)  
- **User_Score** – User reviews (0–10)  
- **Rating** – ESRB rating  

## 🛠️ Tech Stack
- **Python**  
- **Pandas / NumPy** – Data manipulation  
- **SciPy** – Statistical testing  
- **Matplotlib / Seaborn** – Visualization  

## 📈 Hypothesis Testing
- **Platform comparison**: Are user ratings for Xbox One and PC the same?  
  - Result: Significant difference (p < 0.05).  
- **Genre comparison**: Are user ratings for Action and Sports games different?  
  - Result: No significant difference (p > 0.05).  

## 🎯 Key Insights
- Nintendo likely focused on portable consoles in 2017, given strong market positioning.  
- Sony and Microsoft concentrated on PlayStation 4 and Xbox One, respectively.  
- Popular genres: Action, Sports, Racing, Shooter.  
- Sales in NA/EU correlate slightly with critic scores, but **user scores show little correlation**.  
- In Japan, sales are not related to either critic or user ratings.  

## ▶️ How to Run
1. Download the notebook (`video_game_analysis.ipynb`).  
2. Upload it to [Google Colab](https://colab.research.google.com/).  
3. Run the cells step by step.  

## 📬 Contact
**Diego Mappe**  
- [LinkedIn](https://www.linkedin.com/in/diego-m-107314208/)
- [GitHub](https://github.com/dmappe)  
- Email: diegomappe@gmail.com
