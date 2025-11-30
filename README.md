# The Influence of AI Growth on the Employment and Wage Trends of Graphic Designers  
## First step of the project
## Project Overview 
This project investigates the relationship between the rise of AI technologies (such as **Midjourney**, **DALL·E**, **Canva AI**, and **ChatGPT**) and the employment trends of graphic designers.  
By analyzing data from the past decade (2015–2024), this project aims to uncover whether the growing popularity of AI-driven creative tools correlates with a decline in employment opportunities or job demand for graphic designers.

### Key Research Questions
- How strongly does the rise of AI tools (measured by search trends or adoption metrics) correlate with employment or job postings for graphic designers?
- Is there a visible impact of AI popularity on designer salaries or wage growth?
- Can data-driven evidence support the hypothesis that AI automation is transforming the creative job market?

---

## Motivation
Over the last few years, tools like **Midjourney**, **DALL·E**, **Canva AI**, and **ChatGPT** have changed the way digital art and design are created.  
Many designers fear that AI-generated content may be replacing human creativity, while others see it as a way to increase efficiency and creativity.

This project aims to analyze real data to understand whether these fears are justified.  
By studying employment and AI popularity trends together, I want to explore if the creative industry is being disrupted—or just evolving—in response to AI innovations.

---

## Objectives
- Find out if there is a negative/positive correlation between AI tool adoption and graphic designer employment.  
- Identify how salaries, job postings, and industry growth have changed over the last 10 years.  
- Create visualizations that clearly show the trends between AI growth and design jobs.  
- Discuss whether AI has replaced or reshaped creative work and what the data suggests about the future.

## Second Step of the Project
## Data Sources

### 1. Employment and Wage Data (Primary Dataset)  
Source: U.S. Bureau of Labor Statistics (BLS)  
URL: https://www.bls.gov/oes/current/oes271024.htm  
Description:  
Yearly state-level statistics for the occupation "Graphic Designers" (27-1024), including:  
- Total employment  
- Median annual wages  
- Industry-level data  

Files used:  
Graphic_Designer_data/

### 2. AI Popularity Data (Enrichment Dataset)  
Source: Google Trends  
Keywords: AI Art, DALL·E, Midjourney, Canva AI, ChatGPT  

Files used:  
AI_data/

## Step 2: Data Collection, Cleaning, and EDA

### Cleaning Methods  
- Normalized inconsistent numeric formats  
- Selected graphic designer rows (OCC_CODE = 27-1024)  
- Extracted year information  
- Computed national total employment  
- Calculated national median wage  
- Averaged monthly Google Trends interest into yearly scores  
- Merged datasets on "Year"  

### Final Merged DataFrame Columns  
Year, Employment, Median_Wage, AI_Popularity, Emp_Change_%, Wage_Change_%, AI_Change_%

## EDA Visualizations

![Employment Over Time](plots/graph_empl_over_time.png)
![Median Wage Over Time](plots/graph_med_wage_time.png)
![AI Popularity Over Time](plots/ai_popul_over_time.png)
![Normalized Trends](plots/empl_wage_aipop.png)
![AI vs Employment Scatter](plots/ai_vs_graph_empl.jpg)
![AI vs Wage Scatter](plots/ai_vs_graph_wage.jpg)

## Hypothesis Tests

### AI Popularity vs Employment  
Conclusion: No significant statistical evidence that AI popularity affects employment levels.

### AI Popularity vs Wage  
Conclusion: Strong statistical evidence that AI popularity is positively associated with wage increases.

## Key Findings  
1. No significant impact of AI growth on employment levels.  
2. Strong positive relationship between AI popularity and median wages.  
3. All metrics show stable or increasing trends.  
4. AI may enhance designer productivity and value.

## Repository Structure

DSA210_Project/  
│  
├── AI_data/  # contatins csv dataset regarding AI trends  
├── Graphic_Designer_data/ # contains xlsx datasets regarding Wages and employment  
├── plots/  
├── collection_and_analysis.ipynb  
└── README.md  

## Requirements  
`pandas, numpy, matplotlib, seaborn, scipy, openpyxl`
