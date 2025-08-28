# Google Play Store Data Analytics (Python)

This project focuses on real-time **Google Play Store Data Analytics** using Python, Pandas, and Plotly.  
It includes six interactive visualizations with time-based restrictions and custom filters.  

## Project Tasks

1. **Grouped Bar Chart**  
   Compare average rating and total reviews for the top 10 app categories by installs.  
   - Filter: Rating >= 4.0, Size >= 10MB, Last Update = January  
   - Time Window: 3 PM – 5 PM IST  

2. **Choropleth Map**  
   Visualize global installs by category.  
   - Filter: Top 5 categories, exclude names starting with A, C, G, S  
   - Highlight: Installs > 1M  
   - Time Window: 6 PM – 8 PM IST  

3. **Dual-Axis Chart**  
   Compare installs vs revenue for free vs paid apps.  
   - Filter: Installs > 10,000, Revenue > $10,000, Android > 4.0, Size > 15MB  
   - Content Rating: Everyone  
   - Time Window: 1 PM – 2 PM IST  

4. **Time Series Line Chart**  
   Show installs trend over time by category.  
   - Filter: Reviews > 500, Categories starting with E, C, B  
   - Exclude app names starting with X/Y/Z or containing “S”  
   - Translations: Beauty → हिंदी, Business → தமிழ், Dating → Deutsch  
   - Time Window: 6 PM – 9 PM IST  

5. **Bubble Chart**  
   Analyze app size vs rating with installs as bubble size.  
   - Filter: Rating > 3.5, Installs > 50K, Reviews > 500, Subjectivity > 0.5  
   - Categories: Games, Beauty (हिंदी), Business (தமிழ்), Dating (Deutsch), etc.  
   - Highlight: Games in pink  
   - Time Window: 5 PM – 7 PM IST  

6. **Stacked Area Chart**  
   Show cumulative installs over time by category.  
   - Filter: Rating >= 4.2, Reviews > 1,000, Size between 20MB–80MB  
   - Categories: Start with “T” or “P”  
   - Translations: Travel & Local → Français, Productivity → Español, Photography → 日本語  
   - Highlight: Months with >25% MoM growth  
   - Time Window: 4 PM – 6 PM IST  

---

## Tech Stack
- Python 3.x  
- Pandas, NumPy  
- Plotly Express  
- Jupyter Notebook  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/google-play-analytics.git

