Rossman is a well-known drugstore chain in Germany, owned by Dirk Rossmann GmbH. It was founded in 1972 by Dirk Rossmann in Hanover, Germany. 
The chain offers a wide range of products including cosmetics, personal care items, household goods, and pharmaceuticals. Rossman has grown to 
become one of the largest drugstore chains in Germany, with numerous locations throughout the country.
The company is known for its focus on affordable prices, a diverse product selection, and a strong emphasis on customer service. Additionally, 
Rossman is recognized for its commitment to sustainability and social responsibility, implementing various initiatives aimed at reducing its 
environmental footprint and supporting local communities. Rossman has established itself as a popular destination for shoppers in Germany, 
offering convenience and value across its stores.

The data is available on the Kaggle website (https://www.kaggle.com/c/rossmann-store-sales/data). 

Files description:
train.csv - historical data including Sales
test.csv - historical data excluding Sales
store.csv - supplemental information about the stores

Data fields:

Id - an Id that represents a (Store, Date) duple within the test set
Store - a unique Id for each store
Sales - the turnover for any given day (this is what you are predicting)
Customers - the number of customers on a given day
Open - an indicator for whether the store was open: 0 = closed, 1 = open
StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools
StoreType - differentiates between 4 different store models: a, b, c, d
Assortment - describes an assortment level: a = basic, b = extra, c = extended
CompetitionDistance - distance in meters to the nearest competitor store
CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor was opened
Promo - indicates whether a store is running a promo on that day
Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2
PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store
