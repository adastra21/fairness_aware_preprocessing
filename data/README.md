# Datasets

* [Allstate Dataset](https://github.com/the-markup/investigation-allstates-algorithm)
* [German Dataset](https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29)


# Data Dictionaries

## Allstate Dataset

| #  | Name                               | Variable           | Definition                                                      | Original source                   |
| -- | ---------------------------------- | ------------------ | --------------------------------------------------------------- | --------------------------------- |
| 1  | Territory                          | territory          | Territory of policyholder                                       | Maryland Insurance Administration |
| 2  | Gender                             | gender             | Gender of policyholder                                          | Maryland Insurance Administration |
| 3  | Birthdate                          | birthdate          | Birthdate of oldest driver on policy                            | Maryland Insurance Administration |
| 4  | Ypc                                | ypc                | Years with Prior Carrier                                        | Maryland Insurance Administration |
| 5  | Current Premium                    | current\_premium   | Current semi-annual premium for car insurance                   | Maryland Insurance Administration |
| 6  | Indicated Premium                  | indicated\_premium | Current premium after new risk calculation                      | Maryland Insurance Administration |
| 7  | Selected Premium                   | selected\_premium  | Current premium discounted by CGR factor to retain policyholder | Maryland Insurance Administration |
| 8  | CGR                                | cgr                | Complementary Group Rating                                      | Maryland Insurance Administration |
| 9  | CGR Factor                         | cgr\_factor        | CGR Factor assigned to each policyholder                        | Maryland Insurance Administration |
| 10 | County                             | county             | County of Zip code                                              | Maryland Insurance Administration |
| 11 | County Code                        | county\_code       | County code of County                                           | Maryland Insurance Administration |
| 12 | Zip code                           | zipcode            | Zip code of policyholder                                        | Maryland Insurance Administration |
| 13 | Town                               | town               | Town of Zip code                                                | 2015 ACS 5-year Survey            |
| 14 | Area                               | area               | Area of Zip code                                                | 2015 ACS 5-year Survey            |
| 15 | Total Population                   | population         | Total Population in Zip code                                    | 2015 ACS 5-year Survey            |
| 16 | White Population                   | white\_population  | Total White Population in Zip code                              | 2015 ACS 5-year Survey            |
| 17 | Percentage of Non-White Population | perc\_nonwhite     | Non-white population / Total population                         |                                   |
| 18 | Minority                           | minority           | Zip code with >= 75% non-white population                       |                                   |
| 19 | Age                                | age                | 2020 – Birthdate                                                |                                   |


## German Dataset

| #  | Name                                                                | Variable                           | Definition                                                             |
| -- | ------------------------------------------------------------------- | ---------------------------------- | ---------------------------------------------------------------------- |
| 1  | Loan duration                                                       | month                              | Duration in months                                                     |
| 2  | Loan amount                                                         | credit\_amount                     | Credit amount                                                          |
| 3  | Loan installment as Percentage of Income                            | investment\_as\_income\_percentage | Installment rate in percentage of disposable income                    |
| 4  | Years in current residence                                          | residence\_since                   | Present residence since                                                |
| 5  | Age                                                                 | age                                | Age ≤ 25 is 0, age > 25 is 1                                           |
| 6  | Number of credits                                                   | number\_of\_credits                | Number of existing credits at this bank                                |
| 7  | Dependents                                                          | people\_liable\_for                | Number of people being liable to provide maintenance for               |
| 8  | Sex                                                                 | sex                                | Sex = female is 0, sex = male is 1                                     |
| 9  | Checking account balance is negative                                | status=A11                         | Balance on checking account is < 0                                     |
| 10 | Checking account balance is low                                     | status=A12                         | Balanced on checking account is ≥ 0 but < 200 DM                       |
| 11 | Checking account balance is high                                    | status=A13                         | Balance on checking account is ≥ 200 DM                                |
| 12 | No checking account                                                 | status=A14                         | No checking account                                                    |
| 13 | No credit history                                                   | credit\_history=A30                | No loans at any bank                                                   |
| 14 | No credit history at this bank                                      | credit\_history=A31                | No loans at this bank                                                  |
| 15 | Good credit history                                                 | credit\_history=A32                | Loans at this bank but paid back on time                               |
| 16 | Average credit history                                              | credit\_history=A33                | Loans at this bank but paid back with delays                           |
| 17 | Bad credit history                                                  | credit\_history=A34                | Unpaid loans at other banks                                            |
| 18 | Purpose of loan is to pay for a new car                             | purpose=A40                        | Purpose of loan is to buy a new car                                    |
| 19 | Purpose of loan is to pay for a used car                            | purpose=A41                        | Purpose of loan is to buy a used car                                   |
| 20 | Purpose of loan is to pay for miscellaneous                         | purpose=A410                       | Purpose is miscellaneous                                               |
| 21 | Purpose of loan is to pay for furniture or equipment                | purpose=A42                        | Purpose of loan is to buy furniture or equipment                       |
| 22 | Purpose of loan is to pay for radio or television                   | purpose=A43                        | Purpose of loan is to buy radio or television                          |
| 23 | Purpose of loan is to pay for domestic appliances                   | purpose=A44                        | Purpose of loan is to buy domestic appliances                          |
| 24 | Purpose of loan is to pay for repairs                               | purpose=A45                        | Purpose of loan is to pay for repairs                                  |
| 25 | Purpose of loan is to pay for education                             | purpose=A46                        | Purpose of loan is to pay for education                                |
| 26 | Purpose of loan is to pay for retraining                            | purpose=A48                        | Purpose of loan is to pay for retraining                               |
| 27 | Purpose of loan is to pay for a business                            | purpose=A49                        | Purpose of loan is to start a business                                 |
| 28 | Savings account balance is low                                      | savings=A61                        | Balance on savings account is < 100 DM                                 |
| 29 | Savings account balance is medium                                   | savings=A62                        | Balance on savings account is ≥ 100 DM and < 500 DM                    |
| 30 | Savings account balance is high                                     | savings=A63                        | Balance on savings account is ≥ 500 DM and < 1000 DM                   |
| 31 | Savings account balance is very high                                | savings=A64                        | Balance on savings account is ≥ 1000 DM                                |
| 32 | No savings account                                                  | savings=A65                        | No savings account                                                     |
| 33 | Unemployed                                                          | employment=A71                     | Unemployed                                                             |
| 34 | Employed at current job for less than a year                        | employment=A72                     | Employed for < 1 year                                                  |
| 35 | Employed at current job for less than 4 years but more than a year  | employment=A73                     | Employed for ≥ 1 year and < 4 year                                     |
| 36 | Employed at current job for less than 7 years but more than 4 years | employment=A74                     | Employed for ≥ 4 year and < 7 year                                     |
| 37 | Employed at current job for more than 7 years                       | employment=A75                     | Employed for ≥ 7 year                                                  |
| 38 | No other debtors to loan request                                    | other\_debtors=A101                | Other debtors are None                                                 |
| 39 | Co-applicant to loan request                                        | other\_debtors=A102                | Other debtors include Co-applicant                                     |
| 40 | Guarantor to loan request                                           | other\_debtors=A103                | Other debtors include Guarantor                                        |
| 41 | Owns real estate                                                    | property=A121                      | Property includes real estate                                          |
| 42 | Owns building society certificate or life insurance                 | property=A122                      | Property includes building society savings agreement or life insurance |
| 43 | Owns other assets                                                   | property=A123                      | Property includes car or other, not already counted in Savings balance |
| 44 | Owns no property                                                    | property=A124                      | No property                                                            |
| 45 | Pays installment to banks                                           | installment\_plans=A141            | Installment plans with banks                                           |
| 46 | Pays installment to stores                                          | installment\_plans=A142            | Installment plans with stores                                          |
| 47 | Does not pay any installments                                       | installment\_plans=A143            | No other installment plans                                             |
| 48 | Rents housing                                                       | housing=A151                       | Housing is rented                                                      |
| 49 | Owns housing                                                        | housing=A152                       | Housing is owned                                                       |
| 50 | Free housing                                                        | housing=A153                       | Housing is free                                                        |
| 51 | Unemployed and unskilled non-resident                               | skill\_level=A171                  | Unemployed or unskilled, nonresident                                   |
| 52 | Unskilled resident                                                  | skill\_level=A172                  | Unskilled, resident                                                    |
| 53 | Skilled                                                             | skill\_level=A173                  | Skilled, official                                                      |
| 54 | Highly skilled                                                      | skill\_level=A174                  | Highly skilled, manager, self-employed or officer                      |
| 55 | Does not own telephone                                              | telephone=A191                     | No telephone registered under customer name                            |
| 56 | Owns telephone                                                      | telephone=A192                     | 1 or more telephone registered under customer name                     |
| 57 | Is foreigner                                                        | foreign\_worker=A201               | Yes                                                                    |
| 58 | Is not foreigner                                                    | foreign\_worker=A202               | No                                                                     |
| 59 | Good credit or bad credit                                           | credit                             | Credit rating                                                          |
