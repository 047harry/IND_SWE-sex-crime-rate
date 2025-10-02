Project Goal:
 As part of improving my data analysis skills, I explored a social question:
 👉 “Did Sweden’s legalization of pornography in 1971 reduce sex crime rates, and how does that compare with India?”
My initial hypothesis (illusion): liberalizing laws would reduce reported sex crimes.
Q) why Sweden..?
A) Because in European countries sweden have the highest sex crime rate. 

Data Journey:
>Data Collected:
Sweden sexual offence data (1950–2023)
India NCRB rape/sexual offence data (2016–2022, age-wise)
World Bank population data for both countries.

>Data Cleaning: Structured state-wise and year-wise datasets, standardized columns, merged with population tables.

>Data Modeling:
 To ensure fair comparison, I modeled crime rates as per 100,000 population.

>DAX Formula used in Power BI:
Rate_per100k =
 DIVIDE([Cases Reported],
 LOOKUPVALUE(Population[Value],
 Population[Year], Table[Year],
 Population[Country], Table[Country])
 ) * 100000

>Visualization: Built interactive reports in Power BI with:
Time-series line charts (Sweden 1950–2023)
India vs Sweden comparison (2016–2022)
Age-group stacked bars for India.

Key Findings:
1. In Sweden, reported sexual offences increased after 1971 instead of decreasing.
2. In India, rates were much lower (2016 → India = 2.9 vs Sweden = 204.4 per 100k).
3. But low rates in India don’t necessarily mean lower crime — they reflect under-reporting, stigma, and narrow legal definitions.
4. Even when India expanded its rape laws in 2013 & 2018, the reforms did not lead to a dramatic reduction.

Insights:
1. Data reflects law, reporting culture, and awareness — not just behavior.
2. My illusion was wrong: liberalization alone doesn’t “fix” crime statistics.
3. True progress requires freedom for individuals to think, act responsibly, and move beyond rigid ancient philosophies that stigmatize natural human behavior.

Personal Note:
 I’m still a beginner in data analysis, but I’m learning day by day and really 
enjoying this domain. Projects like this help me sharpen my skills in data collection, cleaning, modeling, visualization, and interpretation.
This journey is just the beginning, and I’m excited to keep improving!

In this project i worked more on Collecting and Cleaning the data.
