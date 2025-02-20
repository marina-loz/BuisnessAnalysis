# Yandex.Afisha Marketing Analysis

## Project Overview
This project analyzes Yandex.Afisha's marketing efficiency to optimize advertising expenses, identify the most profitable customer acquisition sources, and improve return on investment.

## Goals
- Analyze user behavior: engagement, retention, and session length.  
- Evaluate key financial metrics: **Customer Acquisition Cost (CAC), Lifetime Value (LTV), and Return on Investment (ROI).**  
- Identify **the most and least effective marketing channels** and suggest optimization strategies.  

## Data Sources
- **Website visits (`visits_log_us.csv`)** – user session logs (June 2017 – May 2018).  
- **Orders (`orders_log_us.csv`)** – purchase history and revenue data.  
- **Marketing costs (`costs_us.csv`)** – advertising expenses over time.  

## Key Findings
- **Average CAC:** $9.32 (too high for profitability).  
- **Average LTV:** $1.15 (low compared to CAC).  
- **LTV/CAC Ratio:** 0.12 (inefficient acquisition strategy).  
- **Most profitable sources:** Source 1 and Source 2 (ROMI > 1.2).  
- **Least profitable sources:** Source 3 and Source 10 (ROMI < 0.5).  
- **Best-performing cohorts:** June–October 2017.  
- **Most common session length (Mode):** 60 seconds.  
- **Challenge:** LTV < CAC, leading to negative ROI.  

## Recommendations
- **Increase investment in Source 1 and Source 2** (best returns).  
- **Optimize Source 4, 5, and 9** to improve efficiency.  
- **Reduce or eliminate spending on Source 3 and Source 10** due to low profitability.  
- **Allocate higher budget in November (Black Friday) and May**, peak engagement months.  

## Technologies Used
- **Python, Pandas, NumPy** – data processing.  
- **Matplotlib, Seaborn** – data visualization.  
- **Jupyter Notebook** – analysis.  

## Running the Project
1. Clone the repository:  
   ```bash
   git clone https://github.com/marina-loz/marketing-analysis.git
