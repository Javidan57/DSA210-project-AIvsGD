# ai-vs-graphic-design-employment
# ai-vs-graphic-design-employment
The Influence of AI Growth on the Unemployment Rate of Graphic Designers
Project Overview

This project explores the relationship between the rise of AI technologies (such as Midjourney, DALL·E, and Canva AI) and the employment rate of graphic designers. The main goal is to examine whether the increasing adoption of AI-driven creative tools correlates with a decline in job demand, job postings, or employment rates among graphic designers over recent years.

The project will apply data science techniques to analyze trends, visualize relationships, and quantify correlations between AI popularity and employment data from 2015–2024.

Motivation

The rapid growth of generative AI has revolutionized the creative industry. Many graphic designers worry that AI tools capable of producing artwork in seconds are replacing traditional design jobs.
This project aims to find data-backed evidence: Is AI truly reducing job opportunities for designers, or are the effects overstated?

Understanding this relationship can help students, educators, and professionals prepare for future shifts in the creative labor market.

Objectives

Analyze long-term trends in graphic design employment and AI popularity.

Compute correlations between AI growth and job availability in creative sectors.

Visualize how employment numbers, salaries, and AI adoption have evolved over time.

Discuss whether correlation implies causation — and highlight ethical and societal implications.

Research Questions

Is there a negative correlation between AI tool popularity and employment rates of graphic designers?

Has AI adoption affected job postings or wages in creative industries?

Which factor (AI popularity or macroeconomic shifts) better explains employment trends?

Data Sources

This project will combine two datasets to satisfy the enrichment requirement:

1. Employment Data (Job Side)

Source: U.S. Bureau of Labor Statistics (BLS)

URL: https://www.bls.gov/oes/current/oes271024.htm

Contains yearly employment and wage statistics for the “Graphic Designers (27-1024)” occupation from 2012–2024.

Will also include optional Kaggle datasets on job postings or creative industry employment.

2. AI Popularity Data (AI Side)

Source: Google Trends

Search Terms: “AI art”, “Midjourney”, “DALL·E”, “Canva AI”, “AI design tools”

Method: Export search interest data (2015–2024) to CSV.

Combine and normalize them into a single AI Popularity Index.

Data Collection Plan

Collect employment data

Download CSV files from BLS and/or Kaggle datasets for graphic design jobs and salaries.

Collect AI popularity data

Export Google Trends data for each search term as CSV.

Combine (enrich) datasets

Merge both datasets by year to align AI popularity with employment data.

Clean data

Handle missing years or inconsistent formats using pandas.

Analyze and visualize

Use Python libraries (matplotlib, seaborn) to create time-series and scatter plots.

Expected Outcomes

A measurable correlation coefficient showing whether AI growth aligns with decreasing job counts.

Line charts showing AI adoption vs. employment trend.

A clear, visual summary of whether AI’s rise coincides with declining opportunities for designers.

A short discussion on the ethical implications of automation in creative industries.

Tools & Libraries

Python

pandas, numpy, matplotlib, seaborn, scipy

Jupyter Notebook