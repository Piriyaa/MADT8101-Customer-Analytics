# Churn & Campaign Scoring
## Import data
* CustomerID	= Unique customer ID
* Churn	Churn = Flag
* Tenure= Tenure of customer in organization
* PreferredLoginDevice  =Preferred login device of customer
* CityTier = City tier
* WarehouseToHome	= Distance in between warehouse to home of customer
* PreferredPaymentMode = Preferred payment method of customer
* Gender = Gender of customer
* HourSpendOnApp = Number of hours spend on mobile application or website
* NumberOfDeviceRegistered = Total number of deceives is registered on particular customer
* PreferedOrderCat = Preferred order category of customer in last month
* SatisfactionScore = Satisfactory score of customer on service
* MaritalStatus = Marital status of customer
* NumberOfAddress = Total number of added added on particular customer
* Complain = Any complaint has been raised in last month
* OrderAmountHikeFromlastYear = Percentage increases in order from last year
* CouponUsed = Total number of coupon has been used in last month
* OrderCount = Total number of orders has been places in last month
* DaySinceLastOrder = Day Since last order by customer
* CashbackAmount = Average cashback in last month


## Undertanding the data & Cleasing Data
<img width="460" alt="Capture 1" src="https://github.com/Piriyaa/MADT8101-Customer-Analytics/assets/128346376/0fdcb834-15b3-4947-88d8-a77fe836e38d">

<img width="419" alt="Capture" src="https://github.com/Piriyaa/MADT8101-Customer-Analytics/assets/128346376/f5c62ccc-fb05-4612-acc0-abd89ce2094a">


## Feature selection

### ignore_features 
* PreferredLoginDevice
* CityTier
* PreferredPaymentMode
* Gender
* PreferedOrderCat
* MaritalStatus
* Complain

## Trainging 
normalize=True, fix_imbalance=True, data_split_stratify=True

<img width="466" alt="4" src="https://github.com/Piriyaa/MADT8101-Customer-Analytics/assets/128346376/4be5edb8-8980-4c76-b6c5-22878f024369">


#### truning (best model)
<img width="302" alt="5" src="https://github.com/Piriyaa/MADT8101-Customer-Analytics/assets/128346376/19ef516a-d5bf-42cd-b242-bcdb56fd57d4">

<img width="490" alt="6" src="https://github.com/Piriyaa/MADT8101-Customer-Analytics/assets/128346376/7c6c8808-4aac-4013-972b-ae8c9b6a4ef9">


<img width="418" alt="7" src="https://github.com/Piriyaa/MADT8101-Customer-Analytics/assets/128346376/81b153ff-cee4-4828-8474-b991bdd36052">

<img width="577" alt="8" src="https://github.com/Piriyaa/MADT8101-Customer-Analytics/assets/128346376/4ee686ec-0c25-44c6-8c0c-9bc1b4f96af5">



