# Project Purpose
My three friends and I were watching the news one day when a frequent topic came up: the government's spending on the military.  We were all in a data science class at the time, so we wondered if we could use a data-driven approach to shed light on some possible correlations between a government's military spending and the happiness of its citizens.

We beleived that military expenditure would influence population happiness levels. Our project focused on determining the nature and direction of this correlation. Additionally, we examined the relationships between military spending and factors contributing to happiness, including government trust, life expectancy, and perceived freedom.

Throughout history, military spending has been associated with government corruption, affecting public trust. It can also indirectly influence health programs and citizens' sense of national security, which may correlate with feelings of freedom. By analyzing these relationships, we aimed to reveal the nuanced impact of military spending on various aspects of population happiness.

# Research Question: 
Does military spending as a percentage of GDP have a positive, negative, or insignificant correlation with a country’s overall happiness? Does military spending correlate to more specific factors of happiness, such as freedom, health expectancy, and government trust? Are those factors of happiness strongly correlated with overall happiness or are they more inelastic?

# Data Cleaning:
We used 3 datasets; one for the happiness of citizens within a country, another for the military spending of countries, and a third for the GDP of the country.  For consistency, we only focused on the years 2015-2018 since those were the only years present in all 3 data sets.  Each data set was also filtered to make sure there were no NaN values in any of the rows.  

All three datasets were merged into one dataset by performing an inner join on the country name in order to only include entries related to countries that appeared within every original data set.

# Methodolody
We created four different linear regression models each with a different target for the regression: one with overall happiness as the target, one with freedom as the target, one with government trust as the target, and one with health as the target.  We did this to determine the relationship between percent of GDP spent on military and a country’s happiness, freedom, government trust, and health.  

# Results:
We found no clear correlation between military spending as a function of overall GDP and a country's happiness and more specific factors that make up happiness such as freedom, health, and government trust.
