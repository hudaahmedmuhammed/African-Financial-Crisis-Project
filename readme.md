# African Financial Crisis ( Kaggle/datasets)
## by (Huda Abd El-Majeed)


## Dataset

> This Dataset specifically focuses on the Financial Crises that occurred from 1860 to 2014, in 13 African countries, including: Algeria, Angola, Central African Republic, Ivory Coast, Egypt, Kenya, Mauritius, Morocco, Nigeria, South Africa, Tunisia, Zambia and Zimbabwe, with 10 features(systemic, currency, inflation and banking crises, exch usd , domestic debt, sovereign external debt, gdp weighted, inflation annual cpi and independence) and 1055 entries after cleaning.
 
#### Columns : 
case : A number which denotes a specific country
cc3 : A three letter country code
country : The name of the country
year : The year of the observation
systemic_crisis : "0" means that no systemic crisis occurred in the year and "1" means that a systemic crisis occurred in the year.
exch_usd : The exchange rate of the country vis-a-vis the USD
domestic_debt_in_default : "0" means that no sovereign domestic debt default occurred in the year and "1" means that a sovereign domestic debt default occurred in the year
sovereign_external_debt_default : "0" means that no sovereign external debt default occurred in the year and "1" means that a sovereign external debt default occurred in the year
gdp_weighted_default : The total debt in default vis-a-vis the GDP
inflation_annual_cpi : The annual CPI Inflation rate
independence : "0" means "no independence" and "1" means "independence"
currency_crises : "0" means that no currency crisis occurred in the year and "1" means that a currency crisis occurred in the year
inflation_crises : "0" means that no inflation crisis occurred in the year and "1" means that an inflation crisis occurred in the year
banking_crisis : "no_crisis" means that no banking crisis occurred in the year and "crisis" means that a banking crisis occurred in the year
> Source( https://www.kaggle.com/chirin/africa-economic-banking-and-systemic-crisis-data )


## Summary of Findings

- __Egypt__ has the highest number of crises Cases, followed by __South Africa__ and __Zimbabwe__.
- __Central African Republic, Nigeria__ and __Ivory Coast__ have the lowest number of crises cases in order.
- __Most exchange rates__ of the countries are between __0 and 80__ (The National Currency per USD). 
- __50%__ of cases the exchange rate is __0.9__. 
- __In fewer cases__ the exchange rates from __80 to 145 and from 230 to 290__ come in second place.
- __The Fewest cases__ are the exchange rates between __380 and 740__.
- __In 96% of the cases, countries are not Domestic indebted.__ 
- __In 85% of the cases, countries are not external indebted.__
- __As shown, sovereign external debts are more than the domestic debts in the most cases.__
- __The Inflation annual CPI in the most cases is high with the percentages between 2% and 12%.__
- __The negative percentages express the decreasing in the inflation indicator, the lowest percentage it reached was -28.5%__.
- __There in no Banking Crisis in 91% of the cases__.

## Key Insights for Presentation

- __Almost all the countries suffer from inflation at different rates.__
- __Angola__, __Zambia__ and __Nigeria__ have the __highest increasing in the Inflation annual CPI rate__ in order.
- __Egypt__ and __South Africa__ have the __lowest increasing in the Inflation annual CPI rate__
- __It is obvious that the increasing in the inflation rates cause increasing in the probability of the banking crisis occurrence.__
- __According to the distributions, when the Inflation CPI rate is close to or equal zero, The incidence of currency crisis is much lower than the no crisis cases.__
- __The increasing in the inflation rate cause increasing in the currency crisis.__ 
- __According to the Systemic, Banking, Currency and inflation crises distributions, the No crisis cases is much higher than the crisis occurrence cases.__
- __In the Systemic crisis distibutions, Central African Republic, Zimbabwe, and Kenya have the highest values of crisis occurrence cases, Mauritius mostly has No systemic crisis.__
- __In the Inflation crisis distributions, Angola, Zambia and Zimbabwe are the highest in the crisis occurrence cases. South Africa is the lowest.__
- __In the Banking crisis distributions, Central African Republic, Zimbabwe and Nigeria have Banking crisis with the highest values. Mauritius and Ivory Coast have the lowest Banking crisis occurrence values.__
- __The percentage of both No Crisis and Not Indebted cases is 80.1%, while the percentage of the country is being  Indebted and there is no crisis is 11.1% and it's higher than the banking crisis occurrence while the country isn't Indebted which is 4.8%__
- __In the presence of the Banking Crisis while the increasing of the Inflation CPI Rate, we can see that the No Systemic Crisis Cases is higher than the Systemic Crisis occurrence.__
- __According to this exploration, we can say that there is no strong relationship between Banking and Systemic Crisis while the increasing of the Inflation CPI Rate and none of them affects the other directly, not like we've explored in the previous one.__
- __When the country is in Sovereign External Indebted and the Inflation Rate increases, The occurrence rate of the Banking Crisis is much higher than the No Banking Crisis cases.__
- __The Sovereign External Debt affects the Banking Crisis occurrence during the increasing of the Inflation CPI Rate.__
- __During the increasing of the exchange rate vs the USD, The No Currency crisis cases is higher than the crisis occurrence, but in the Inflation Crisis occurrence we can see that the Currency Crisis Occurrence is higher than the No Currency cisis cases.__
- __The Inflation Crisis occurrence affects on the occurence and the increasing in the Currency Crisis occurrence.__