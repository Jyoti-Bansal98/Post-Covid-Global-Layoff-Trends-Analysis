# 🌍 Global Layoff Trends Post-COVID: Data Analysis & Visualization

## 🔹 Project Objective
The COVID-19 pandemic caused unpredictable disruptions in global workforce. This project uncovers Global Layoff Trends Post-COVID (2020–2025), analyzing how industries, company stages, funding levels, and locations influenced workforce reductions worldwide. By transforming raw data into interactive and insightful visualizations, it uncovers hidden patterns, highlights the most affected sectors and regions, and tells a clear story of evolving job market dynamics.
The goal is to deliver actionable, data-driven insights that are easy to explore and understand, enabling recruiters, analysts, investors and policymakers to quickly grasp complex workforce shifts.

---

## 🔹 Dataset
- *Source:* Kaggle / Public dataset
- *Dataset Link:* https://www.kaggle.com/datasets/swaptr/layoffs-2022
- *Rows:* 4150 
- *Columns:* company, industry, location, stage, funds_raised_millions, total_laid_off, percentage_laid_off, date, country, etc.  
- *Description:* The dataset contains layoffs information for global companies from 2020 to 2025 (April). It has been cleaned, missing values handled, and columns transformed for analysis.

---

## 🔹 Analysis Steps
1. *Data Cleaning & Preprocessing* 
   - Standardizing categorical columns (company, industry, location)
   - Handling missing values (NaN) logically
   - Converting dates and numeric columns
   - Removing columns not needed for analysis
2. *SQL & Pandas Analysis*
   - Aggregating layoffs by year, month, industry, country, company, location, stage, and funding  
   - Ranking top companies and countries by layoffs  
   - Computing averages and percentages for deeper insights  
3. *Visualizations & Storytelling*
   - Time-series analysis of layoffs (year-wise, month-wise, month-year)  
   - Country-wise and location-wise analysis  
   - Company-wise, industry-wise, stage-wise layoffs, % wise layoffs
   - Top industries by total layoffs each year
   - Stage-wise total layoffs vs funds raised
   - Relation between total layoffs and percentage layoffs
   - Interactive and professional storytelling insights for each graph  
4. *Insights & Business Impact*
   - Identifying high-risk industries, and stages  
   - Understanding global workforce trends  
   - Linking funding, company stage, and layoffs patterns

---

## 🔹 Analysis & Key Visualizations
To understand the global layoff patterns post-COVID, I analysed the dataset across time, industry, country, location, company, stage and funding. The visualizations below highlight key trends and insights.
##  📌  Time-Based Analysis
###  🗓️  Year-wise Layoffs Trend
<img src="images/lineplot%20for%20Year-wise%20Total%20Layoffs.png" alt = "Year-wise Layoffs" width = "600"/>

###  🗓️  Month-wise Layoffs Trend
<img src="images/Barplot%20for%20Total%20Layoffs%20per%20Month.png" alt = "Month-wise Layoffs" width = "600"/>

###  🗓️  Month-Year wise Layoffs Trend
<img src="images/Heatmap%20for%20Month-Year%20wise%20Total%20Layoff.png" alt = "Month-Year Layoffs" width = "600"/>

##  📌  Geographic Analysis
###  🌍  Country-wise Layoffs Trend
<img src="images/Top%2010%20Countries%20by%20Total%20Layoffs.png" alt = "Country-wise Layoffs" width = "600"/>

### 📍  Location-wise Layoffs Trend
<img src="images/Barplot%20for%20Location%20by%20Layoffs.png" alt = "Location-wise Layoffs" width = "600"/>

##  📌  Industry & Company Analysis
### 🏭  Industry-wise Layoffs Trend
<img src="images/Barplot%20for%20Top%20Industry%20by%20Total%20Layoffs%20Each%20Year.png" alt = "Industry-wise Layoffs" width = "600"/>

<img src="images/Barplot%20for%20Top%20Industry%20by%20Total%20Layoffs%20in%20Top%2010%20Countries.png" alt = "Industry-wise Layoffs" height = "600"/>


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
1. Why do some industries collapse faster than others during global shocks?
   - Because not all sectors are built equally. Hardware, retail, and travel showed us how fragile traditional models can be when the world slows down. These industries           urgently need to build resilient, adaptive strategies if they want to withstand the next disruption.¶
2. If money means power, why did giants like Meta, Tesla, and Intel still cut jobs?
   - Funding doesn’t equal stability. These companies had billions at their disposal, yet even they resorted to massive layoffs. The truth is clear: financial strength alone      cannot shield a company from poor planning or sudden downturns.
3. Are all companies equally at risk, or do some stages carry higher dangers?
   - Not at all. Startups often face percentage-heavy cuts, but IPO-stage companies pose the largest systemic workforce risks. Their sheer size means even a small adjustment      can put hundreds of thousands of jobs on the line - something policymakers and investors must keep in mind.
4. Why did the U.S. dominate the layoff charts?
   - Because of concentration risk. With hubs like SF Bay Area and Seattle driving global tech, the U.S. became the epicenter of layoffs. The lesson? Diversifying talent          globally can spread the risk and create a more balanced, shock-proof workforce.
5. What’s the real fix to prevent mass layoffs?
   - It starts with smarter workforce planning. Companies need to rethink how they hire and scale - focusing on sustainable growth instead of overexpansion that eventually        forces painful mass cuts.
---

## 🔹 This project not only visualizes layoffs but also provides a lens into how businesses can prepare for future shocks in     a more sustainable and resilient way.
