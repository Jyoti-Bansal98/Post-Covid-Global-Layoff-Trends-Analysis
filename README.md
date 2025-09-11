# 🌍 Global Layoff Trends Post-COVID: Data Analysis & Visualization

## 🔹 Project Objective
This project explores *global layoff trends post-COVID*, analyzing how industries, company stages, funding, and locations influenced workforce reductions. Through clean datasets, SQL & Pandas analysis, and engaging visualizations, it uncovers patterns, highlights the most affected sectors, and provides actionable insights for companies, investors, and policymakers.

---

## 🔹 Dataset
- *Source:* Kaggle / Public dataset  
- *Rows:* XXXX  
- *Columns:* company, industry, location, stage, funds_raised_millions, total_laid_off, percentage_laid_off, date, country, etc.  
- *Description:* The dataset contains layoffs information for global companies from 2020 to 2025 (April). It has been cleaned, missing values handled, and columns transformed for analysis.

---

## 🔹 Analysis Steps
1. *Data Cleaning & Preprocessing*
   - Handling missing values (NaN)  
   - Standardizing categorical columns (company, industry, location)  
   - Converting dates and numeric columns  
2. *SQL & Pandas Analysis*
   - Aggregating layoffs by year, month, industry, country, stage, and funding  
   - Ranking top companies and countries by layoffs  
   - Computing averages and percentages for deeper insights  
3. *Visualizations & Storytelling*
   - Time-series analysis of layoffs (year-wise, month-wise, month-year)  
   - Country-wise and location-wise analysis  
   - Company-wise, industry-wise, and stage-wise layoffs  
   - Interactive and professional storytelling insights for each graph  
4. *Insights & Business Impact*
   - Identifying high-risk industries and stages  
   - Understanding global workforce trends  
   - Linking funding, company stage, and layoffs patterns

---

## 🔹 Key Visualizations
| Visualization | Description |
|---------------|-------------|
| Year-wise Total Layoffs | Shows global layoffs trend from 2020–2025 |
| Month-wise Layoffs | Identifies peak and low months across years |
| Country-wise Layoffs | Total layoffs by country, highlighting the most affected |
| Location-wise Layoffs | Hotspots like SF Bay Area, Seattle, and Bengaluru |
| Company-wise Layoffs | Top companies affected, with funding overlay |
| Industry & Stage Analysis | Average % layoffs and total layoffs across industries and company stages |
| Funding vs Layoffs | Shows relationship between company funding and layoffs |
| Percentage Laid Off Distribution | Counts of companies by percentage layoffs |

All plots include insights, storytelling, and human touch for easy interpretation.

---

## 🔹 Insights & Key Findings
- *Post-COVID layoffs peaked* between 2021–2023, with Jan 2023 showing the highest layoffs globally.  
- *Industry impact:* Hardware, Consumer, Retail, and Travel were heavily affected.  
- *Company funding doesn’t guarantee stability:* Even highly funded companies like Meta, Tesla, Intel had massive layoffs.  
- *Stage sensitivity:* IPO-stage firms shed large absolute numbers, while early-stage startups faced sharp percentage cuts.  
- *Geography matters:* The U.S., especially SF Bay Area and Seattle, dominated layoffs.  
- *Top companies affected:* Intel, Microsoft, Amazon, Meta, Netflix, Tesla, Flipkart.  
- *Major insights:* Workforce planning, adaptive models, and risk management are critical for resilience.

---

## 🔹 Future Outlook / Business Impact
*Questions & Learnings*:  
1. How do companies at different growth stages behave during crises?  
   - Early-stage startups face sharp percentage layoffs, while IPO-stage firms shed large absolute numbers. This highlights the need for *balanced hiring and sustainable growth*.  

2. Which industries need better risk management?  
   - Hardware, Retail, and Travel are highly exposed to market cycles and require *adaptive business models*.  

3. Does high funding prevent layoffs?  
   - Not necessarily. Even heavily funded giants had to cut jobs, showing that *financial strength alone cannot prevent layoffs*.  

4. How can geographic concentration risk be mitigated?  
   - Companies should *diversify talent globally* to reduce risk in localized hubs.  

---

## 🔹 How to Run
1. Clone the repo:
```bash
git clone https://github.com/yourusername/Global_Layoffs_Analysis.git
