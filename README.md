# One Piece Season 2: Sentiment-Led Marketing Strategy & Character Rollout Insights

## 📑 Executive Summary

**The Challenge**

Live-action anime adaptations historically face high levels of fan skepticism. While One Piece Season 1 successfully broke this pattern, Season 2 introduces a new challenge: onboarding a large ensemble cast (Baroque Works) without losing the momentum and goodwill built in the first season.

**The Solution**

This project applies a data-first marketing approach. By analyzing over one year of Season 1 audience reviews alongside immediate community reactions to the Season 2 trailer, new cast members are segmented into three actionable marketing tracks:

- **Revenue Generation:** Identifying fan-favorite characters for merchandise prioritization
- **Organic Growth:** Identifying “hype engines” that drive viral, social-first engagement
- **Brand Protection:** Identifying casting-related risks to proactively mitigate negative PR

**Key Results**

1. **Market Readiness:** A strong Season 2 Demand Ratio confirms the audience is primed for the March 2026 launch
2. **Top Asset:** Nico Robin emerges as the highest-performing character asset, with 54% positive sentiment
3. **Viral Catalyst:** Igaram / Baroque Works generate the strongest humor-driven engagement, ideal for top-of-funnel awareness
4. **Strategic Pivot:** Current data supports de-prioritizing Vivi in early promotional materials due to active casting-related friction within the community

## 📌 Project Overview

Following the critical success of One Piece Season 1 (86% Rotten Tomatoes), this project uses multi-platform exploratory data analysis (EDA) to inform and optimize the marketing rollout strategy for Season 2 (launching March 10, 2026).

The analysis combines historical audience data from IMDb and Rotten Tomatoes with real-time engagement signals from the Season 2 trailer to identify hype drivers, merchandise opportunities, and brand safety risks.

## 🎯 Project Objectives

1. **Retrospective Analysis:** Quantify a Season 2 Demand Ratio from Season 1 reviews to validate market readiness
2. **Trailer Engagement Mapping:** Measure audience reception to new characters using YouTube like-to-comment ratios and keyword frequency analysis
3. **Strategic Categorization:** Segment characters into actionable marketing pillars—Merchandise Leads, Meme Catalysts, and Risk Mitigation

## 📊 Key Findings

1. **Nico Robin (Merchandise Lead):** Maintains a 54% positive sentiment, positioning her as the primary candidate for high-value merchandise rollout
2. **Igaram & Baroque Works (Meme Catalysts):** Drive the strongest humor-based engagement, making them ideal for viral short-form campaigns (Reels, TikTok)
3. **Vivi (Brand Safety Risk):** Exhibits negative sentiment 50% above platform average, indicating a need to limit early high-visibility promotion until audience perception stabilizes

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Selenium, Pandas, NumPy, Matplotlib, Pandasql, Seaborn, WordCloud, VADER
- **Sentiment Analysis:** VADER (Valence Aware Dictionary and sEntiment Reasoner)
- **Querying:** SQL-style logic via Pandas / Pandasql

## 📂 Project Structure

**EDA:** Primary analysis notebook containing data cleaning, visualizations, and strategic insights
1. one_piece_eda.ipynb

**Data:** Cleaned CSV files from IMDb, Rotten Tomatoes, and YouTube comments
1. one_piece_imdb_df_cleaned.csv
2. one_piece_rt_df_cleaned.csv
3. one_piece_yt_df_cleaned.csv

**Data Cleaning Codes:** Mainly used Pandas, Pandasql, and VADER
1. one_piece_imdb_cleaning.ipynb
2. one_piece_rt_cleaning.ipynb
3. one_piece_trailer_en_cleaning.ipynb

**Web Scraping Codes:** Used Selenium mainly
1. one_piece_imdb_web_scraping.ipynb
2. one_piece_rt_web_scraping.ipynb
3. one_piece_trailer_en_web_scraping.ipynb

***Note:** For YouTube comments, I used the YouTube API for more accurate data.

**Visualizations:** Exported charts and word clouds used in the final strategy report
1. Introduction
   <img width="1163" height="653" alt="Slide1" src="https://github.com/user-attachments/assets/0cb46c1a-a8a0-4147-abda-08445924894f" />
   
2. Overview
   <img width="1160" height="650" alt="Slide2" src="https://github.com/user-attachments/assets/9767e837-aec2-4691-915e-620630782241" />

3. Global Audience's Anticipation of Season 2
   <img width="1158" height="650" alt="Slide3" src="https://github.com/user-attachments/assets/dd119fe9-61c8-4c02-9e1d-d9d69cc9dfd4" />

4. Marketing Suggestions Based on Characters
   <img width="1159" height="650" alt="Slide4" src="https://github.com/user-attachments/assets/7fd3c392-7ec5-4c3a-b0ef-24eb0219150f" />

5. Executive Summary
   <img width="1161" height="648" alt="Slide5" src="https://github.com/user-attachments/assets/006af413-44a6-45c0-975f-4325ccfbe016" />

6. End
   <img width="1161" height="651" alt="Slide 6" src="https://github.com/user-attachments/assets/07e451eb-5bbf-49db-889d-3530d631cf0f" />

## 🚀 Recommended Marketing Actions

1. **Lead with Robin:** Highly recommended to anchor the first wave of physical merchandise around Nico Robin
2. **Meme-First Social Strategy:** Deploy humor-driven content featuring Igaram and Mr. 3 to maximize organic reach
3. **Vivi Sentiment Monitoring:** Delay Vivi-centric solo promotions until live-action performance can positively shift the current casting narrative

## 🔗 Connect with Me

If you’d like to talk about **data analysis, Python, or TV Series 😄**, feel free to reach out:

- **Email:** jkim3615@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/jae-hwan-kim/
