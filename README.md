### Lending Club Rate of Return Prediction using Socio-Economic Factors and SMOTE sampling

#### Concept:
A traditional banking counterpart, Lending Club is an online market place for borrowers and lenders and has become a major player in the peer-to-peer lending business with an average rate of return between 3% and 8% per year. Lenders, before committing their money, carefully investigate a multitude of associated risks such as 
 -borrower defaults
 -liquidity risk
 -poor loan diversification, etc. 
But for a steady return, lenders are advised to diversify their portfolio by investing in different loans with different rate of interest.  Most of these modeling techniques utilize collected borrower’s personal, professional and credit information. This is crucial for non-traditional banks such as Lending Club because to maintain a low-interest rate and expand their customer base, they need to accurately identify and decline potential defaulters. 

One factor that is rarely assessed over the period is the borrower’s zip-code specific socio-economic indicators such as no. of workers, workers in different industry & occupation, below poverty line families, unemployment rate, etc. in a location. In the latest study, median household income for individual zip-code was used to predict loan default and has reported an increase in the accuracy. This study attempts to strategize investment portfolio by two-stage scoring approach, which is an integration of classification of default loans and prediction of annualized rate of return (ARR) using zip-code specific socio-economic indicators from American Fact Finder and loan history data from Lending Club. More specifically, this study will explore re-sampling techniques such as random under-sampling, random over-sampling and SMOTE to further increase the accuracy in prediction using SAS® Enterprise Miner™, 7 SAS® Enterprise Guide®, and Python 3. The numerical study indicates the predicted return and portfolio size is more realistic and better than existing investment methods such as bonds, savings accounts & Prosper Lending

#### Process Flow:

![Process_Flow](https://user-images.githubusercontent.com/54467567/63634640-fd26ae80-c61e-11e9-84c0-73749b99cdf1.PNG)


