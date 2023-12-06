# stat_comp_fp23
Final Project for Statistical Computing @Belmont University Fall 23

This project explores the Billionaires Statistics Dataset (2023) by Nidula Elgiriyewithana, available on Kaggle.
It includes initial exploratory data anlaysis, followed by three types of hypothesis testing:
a chance model, a permutation test, and a bootstrapped confidence interval.

For each hypothesis test, the mean was always selected over the median.  While the mean is less resistent to outliers, this entire project was based around an analysis of outliers.  Because the purpose of this project is to gain insight into outliers, it seemed important to allow the data to be skewed by extreme, outlier events.

The presentation for this project can be accessed here: https://docs.google.com/presentation/d/1szGNmfnNXwYYxj5jh61IX2hduVBj4wvrRUUi-1Lc8Lc/edit?usp=sharing

The data dictionary below comes from the orginal Kaggle dataset.  Additional annotations have been made by me to clarify whether each varibale is quantitative or categorical.  No other changes to the original data dictionary have been made.

Data Dictionary:

rank: The ranking of the billionaire in terms of wealth. Categorical.

finalWorth: The final net worth of the billionaire in U.S. dollars. Quantitative.

category: The category or industry in which the billionaire's business operates. Categorical.

personName: The full name of the billionaire. Categorical.

age: The age of the billionaire. Quantitative.

country: The country in which the billionaire resides. Categorical.

city: The city in which the billionaire resides. Categorical.

source: The source of the billionaire's wealth. Categorical.

industries: The industries associated with the billionaire's business interests. Categorical.

countryOfCitizenship: The country of citizenship of the billionaire. Categorical.

organization: The name of the organization or company associated with the billionaire. Categorical.

selfMade: Indicates whether the billionaire is self-made (True/False). Categorical.

status: "D" represents self-made billionaires (Founders/Entrepreneurs) and "U" indicates inherited or unearned wealth. Categorical.

gender: The gender of the billionaire. Categorical.

birthDate: The birthdate of the billionaire. Categorical.

lastName: The last name of the billionaire. Categorical.

firstName: The first name of the billionaire. Categorical.

title: The title or honorific of the billionaire. Categorical.

date: The date of data collection. Categorical.

state: The state in which the billionaire resides. Categorical.

residenceStateRegion: The region or state of residence of the billionaire. Categorical.

birthYear: The birth year of the billionaire. Categorical.

birthMonth: The birth month of the billionaire. Categorical.

birthDay: The birth day of the billionaire. Categorical.

cpi_country: Consumer Price Index (CPI) for the billionaire's country. Quantitative.

cpi_change_country: CPI change for the billionaire's country. Quantitative.

gdp_country: Gross Domestic Product (GDP) for the billionaire's country. Quantitative.

gross_tertiary_education_enrollment: Enrollment in tertiary education in the billionaire's country. Quantitative.

gross_primary_education_enrollment_country: Enrollment in primary education in the billionaire's country. Quantitative.

life_expectancy_country: Life expectancy in the billionaire's country. Quantitative.

tax_revenue_country_country: Tax revenue in the billionaire's country. Quantitative.

total_tax_rate_country: Total tax rate in the billionaire's country. Quantitative.

population_country: Population of the billionaire's country. Quantitative.

latitude_country: Latitude coordinate of the billionaire's country. Categorical.

longitude_country: Longitude coordinate of the billionaire's country. Categorical.
