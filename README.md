# End-to-end G-20 Indicators Data Analysis project using Python and Power BI 📊

![g20-countries-1024x538](https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/8ef18a3f-2884-4f57-a08f-c5120f3990c4)

# Prerequisite🔍
#### Ensure the "wbdata" library is installed

#### World Bank Data API:
- The World Bank offers a comprehensive repository of data on global development, encompassing economic, social, and environmental indicators for various countries and regions.
- This data can be accessed programmatically via the World Bank API, which facilitates integration into data analysis workflows.

#### wbdata Library:
- wbdata is a Python wrapper for the World Bank API, simplifying the process of retrieving data without directly handling API requests.
- It provides functions to search for indicators, fetch data, and convert it into pandas DataFrames for analysis.
  
# Introduction ✒️
The project aims to leverage the wbdata library to access and analyze development data from the World Bank, focusing on G-20 countries within a specified date range. By utilizing the wbdata library, the project simplifies the process of retrieving high-quality economic, social, and environmental indicators from the World Bank's extensive repository. Targeting the G-20 countries, a group of major economies allows for a comparative analysis of development trends among these influential nations. 

The analysis is confined to the period from January 1, 2015, to December 31, 2020, enabling the examination of recent trends and changes. The project involves converting the retrieved data into pandas DataFrames for further manipulation and visualization using libraries like Matplotlib and seaborn.

Additionally, the project will leverage Power BI for advanced data analysis and visualization. By importing the processed data into Power BI, the project aims to create interactive dashboards and reports that provide deeper insights and facilitate better decision-making. This approach facilitates a comprehensive analysis of development indicators, providing valuable insights into the progress and challenges faced by the G-20 countries during the specified timeframe.

# Indicators 🚨
### Economic 💸
1. Gross Domestic Product (GDP)
2. Gross National Income (GNI)
3. Inflation Rate
4. Foreign Direct Investment (FDI)
5. Exports of Goods and Services
6. Gross Capital Formation
7. Agricultural land Area
8. Agricultural Production Index

### Social 🤗
1. Unemployment Rate
2. Poverty Rate
3. Life Expectancy
4. Literacy Rate
5. Access To Electricity
6. Mobile Phone Subscriptions
7. Government Expenditure on Education

# Tools Used 🔨
- ### Python 
- ### Power BI

# Report Building in PowerBI 📉

### Visualizations : 
1. Inflation rates over the years
2. Access to Electricity
3. Efficacy of Government Spending on Education
4. Gross Domestic Product (GDP) and Gross Capital Formation
5. Gross National Income (GNI) and Average of Mobile Phone Subscriptions
6. Foreign Direct Investment (FDI)
7. Top 10 Countries with the Highest Life Expectancy
8. Imports Vs. Exports by Average Poverty Rate

## Summary of Plots -

## Page 1: Overview
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/1f2e6875-2ef3-47fe-8a39-fd0da74db91c" height="HEIGHT">
</div>

### 1. Inflation Rate
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/fee90531-df22-42d8-81b4-820260d3bc6c" height="HEIGHT">
</div>

- The "Inflation Rate" line graph shows annual inflation rates for G-20 countries from 2015 to 2020. The X-axis represents years, and the Y-axis shows inflation rates as percentages.
- This visualization allows for easy comparison of inflation trends across G-20 nations, providing insights into economic stability and the impact of global events.

### 2. Access to Electricity
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/731aa783-2c33-4f02-8a40-b502b8729f1d" height="HEIGHT">
</div>

The Filled Map shows that most G-20 countries have near-universal access to electricity, with percentages close to 100%. However, a few countries, such as India and South Africa, show slightly lower percentages, indicating areas where access to electricity still needs improvement.

### 3. Efficacy of Government Spending on Education
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/e406fcf0-1dc7-4c1e-bcef-01ef118e442f" height="HEIGHT">
</div>

The tree chart titled "Efficacy of Government Spending on Education" provides an insightful representation of the total government expenditure on education and the average literacy rate for each G-20 country. In this visualization, the size of each rectangle (or box) corresponds to the amount of government expenditure on education, with larger boxes indicating higher spending. The color of each box reflects the average literacy rate in the respective country, creating a clear visual distinction between countries with varying levels of educational outcomes.

This visualization allows for an immediate and intuitive comparison of educational spending and outcomes across countries. For instance, a large green box signifies a country with substantial educational investment and high literacy rates, suggesting that the spending is effectively translating into positive educational outcomes. On the other hand, a large red box indicates high spending but low literacy rates, pointing to potential inefficiencies or challenges in the education system despite significant investment.

Smaller boxes represent countries with lower spending on education. A small green box would indicate that even with limited funds, the country achieves high literacy rates, highlighting the efficient use of resources. Conversely, a small red box would suggest that low spending correlates with low literacy rates, possibly indicating a need for increased investment or better resource allocation.

## Page 2: Overview
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/5bcb7b71-7ab4-48f9-bcf3-881414663501" height="HEIGHT">
</div>

### 1. Gross Domestic Product (GDP) and Gross Capital Formation 
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/90d916a7-317d-4f12-baeb-a2d1033aaf20" height="HEIGHT">
</div>

The bar plot titled "Gross Domestic Product (GDP) and Gross Capital Formation" ranks G-20 countries from highest to lowest GDP

GDP is depicted by the primary bar, indicating the total market value of all goods and services produced in each country. The Gross Capital Formation measures the net investments in physical assets such as infrastructure, machinery, and buildings.

This visualization shows that the United States, China, the European Union, and Japan are at the top with the highest GDPs, reflecting their substantial economic activity. Correspondingly, these countries also have significant Gross Capital Formation, signifying strong investment in future growth.

In contrast, countries like Argentina and South Africa appear at the lower end of the GDP spectrum, with comparatively smaller bars for both GDP and Gross Capital Formation. This indicates lower overall economic output and investment levels.

### 2. Gross National Income (GNI) and Average of Mobile Phone Subscriptions 
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/ac85c321-8b8e-4a47-b587-60200a580090" width="WIDTH" height="HEIGHT">
</div>

The treemap titled "Gross National Income (GNI) and Average Mobile Phone Subscriptions" provides a detailed comparison of G-20 countries based on their GNI and mobile phone subscription rates. In this visualization, the size of each rectangle represents the total GNI of a country, with larger rectangles indicating higher GNI. The color of each rectangle depicts the average mobile phone subscription rate, with red indicating lower subscription rates and green indicating higher rates.

The largest rectangles represent the countries with the highest GNI, such as the United States, China, and Japan. These large rectangles signify substantial economic output and income generated by these nations.

The color gradient from red to green highlights the variation in mobile phone subscription rates across countries. Countries with dark green rectangles, such as Japan, Italy, and Indonesia have high GNI and high mobile phone subscription rates, indicating widespread access to mobile technology. Conversely, countries with large red rectangles, such as India, and Canada may have high GNI but lower mobile phone subscription rates, suggesting potential areas for improvement in telecommunications infrastructure.

Some countries, like Brazil, France, and China display a mix of medium-sized rectangles with varying shades of green and red. This indicates moderate GNI and varying levels of mobile phone penetration, reflecting diverse economic conditions and technology adoption rates within these nations.

## Page 3: Overview 
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/43fc3c1d-647b-4c68-b3c9-13dc96dd6409" height="HEIGHT">
</div>

### 1. Foreign Direct Investment (FDI)
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/cff90f89-bfe7-47c7-a6ee-4daf65aff92a" height="HEIGHT">
</div>

The bar plot titled "Foreign Direct Investment (FDI)" provides a comparative overview of FDI inflows into G-20 countries. The bars are arranged from the highest to the lowest FDI, facilitating an easy comparison of which countries are attracting the most foreign investment.

The plot reveals that the United Kingdom, Brazil, and the European Union are the top recipients of FDI, with significantly higher bars indicating substantial inflows of foreign capital. These countries benefit from strong economic policies, market opportunities, and stable political environments, making them attractive destinations for international investors.

Mid-range countries like Indonesia, India, United States also show considerable FDI inflows, reflecting their growing economies and increasing attractiveness to foreign investors due to factors like market size, resource availability, and labor force.

At the lower end, countries such as South Africa, Korea, and Japan have smaller bars, indicating lower levels of FDI. This could be due to various factors, including economic instability, less favorable investment climates, or smaller market sizes.

### 2. Top 10 Countries with the Highest Life Expectancy 
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/85385f88-a22d-4dcb-b21a-1d01d011bc70" height="HEIGHT">
</div>

The bar plot titled "Top 10 Countries with the Highest Life Expectancy" ranks G-20 countries based on their life expectancy. The countries are ordered from highest to lowest life expectancy, providing a clear visual ranking of longevity.

The plot shows that Japan leads with the highest life expectancy, followed closely by Italy and Australia. These countries, represented by the tallest bars, demonstrate life expectancies surpassing 80 years, reflecting their high standards of healthcare, healthy lifestyles, and robust social systems.

Other countries in the top 10, such as Canada, France, and South Korea, also exhibit high life expectancies, indicating well-developed healthcare infrastructure and effective public health policies. These bars, though slightly shorter, still indicate life expectancies in the high 70s to low 80s.

### 3. Imports Vs. Exports by Average Poverty Rate
<div align="center">
  <img src="https://github.com/itzKshitijaC/G-20-Indicators-Analysis/assets/168798073/7a7c1e71-5c0d-4d51-a7a4-2e166c7de9ff" height="HEIGHT">
</div>

The scatter plot titled "Imports vs. Exports by Average Poverty Rate" illustrates the relationship between trade balances (imports and exports) and the average poverty rate across G-20 countries. The X-axis represents the value of imports in billions of dollars, while the Y-axis represents the value of exports in billions of dollars. Each point on the scatter plot corresponds to a country, with the size of the point indicating the average poverty rate: larger points signify higher poverty rates and smaller points indicate lower poverty rates.

 Countries positioned above the diagonal line (where exports equal imports) have a trade surplus, meaning they export more than they import. Countries below this line have a trade deficit, importing more than they export. This visualization highlights the trade balances of G-20 countries, showing which countries are net exporters or net importers.

 The size of each point provides an additional dimension, indicating the average poverty rate. For example, a country with high exports but a large point size may have significant trade success but still struggle with higher poverty rates. Conversely, smaller points in the surplus area suggest that some countries effectively use their trade surplus to maintain lower poverty rates.

 The scatter plot may reveal outliers, such as countries with very high exports but also high poverty rates, suggesting that trade benefits are not evenly distributed within the country. It also shows trends where countries with balanced trade have varying poverty rates, indicating that factors other than trade balances also significantly impact poverty.

 # Conclusion 🔚
This project successfully leverages the wbdata library to access and analyze development data from the World Bank, focusing on G-20 countries between January 1, 2015, and December 31, 2020. By simplifying the retrieval of high-quality economic, social, and environmental indicators, the project enables a detailed comparative analysis of these major economies. Utilizing pandas DataFrames for data manipulation and visualization tools like Matplotlib and Seaborn, the project offers clear, insightful visual representations of development trends.

Further enhancing the analysis, the project incorporates Power BI to create interactive dashboards and reports. These advanced visualizations provide deeper insights into the progress and challenges faced by G-20 countries, facilitating better decision-making. Overall, the project delivers a comprehensive analysis of development indicators, highlighting significant trends and changes within the specified period, and offering valuable guidance for policymakers, researchers, and business leaders.
