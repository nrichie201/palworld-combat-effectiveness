# Palworld Combat Effectiveness Analysis
**DS3000 Data Science Project - July 2025**

## Overview
Data science analysis of 225 Palworld characters to predict combat effectiveness and identify undervalued fighters using web scraping, machine learning, and statistical analysis.

## Key Findings
- **44% prediction accuracy** using non-combat features (rarity, element, work skills)
- **59 undervalued Pals identified** that outperform rarity expectations
- **Work specialization trade-off discovered**: Diverse workers are weaker fighters
- **4 combat archetypes** identified through K-Means clustering

## Technologies Used
- **Python**: Data analysis and modeling
- **BeautifulSoup**: Web scraping palworld.gg database
- **Scikit-learn**: Linear regression, K-Means clustering, cross-validation
- **Pandas**: Data manipulation and cleaning
- **Matplotlib/Plotly**: Data visualization and interactive plots

## Files
- `project1.5.ipynb`: Complete analysis notebook
- `data/`: Scraped datasets (225 Pals, 8 features)
- `DS 3000 Project (1).pdf`: Final presentation slides

## Results
Linear regression achieved R² = 0.436 predicting combat effectiveness from rarity, elemental type, and work capabilities. K-Means clustering revealed performance-based combat tiers validated through elbow method analysis.
