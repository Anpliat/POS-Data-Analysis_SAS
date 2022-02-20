# POS Data Analysis (SAS Programming and Data Mining)

### Purpose
Conduct an analysis of a clothing company to provide suggestions on how the organization should act in order to operate in a more efficient and effective way.

### Programming languages and tools:
* Base SAS
* SAS Enterprise Miner

## Datasets description
The datasets consist of POS data from a physical store that sells women’s clothes. The available data are included in the following tables.

### Customer table
This table is related to the data about the customers and contains the following columns:
* ID: Customer ID, (unique for every customer)
* BIRTHDAY: date of birth
* SEX: gender

### Document table
This table contains data about the issued receipt (sale or return) and contains the following columns:
* BASKETID: ID of the receipt
* SALESDATE: date when the receipt was issued
* MOVEMENT: takes the values «400 ή 401» i.e. sale or return
* ID: Customer ID that is related with the basket (receipt)

### Basket table
This table contains the following columns:
* BASKETID: ID of the receipt
* PROMOTION: Code of the promotional activity, if null then there is no promotional activity
* SKU: SKU of the product
* PRICE: Price of the product

### ProductCategory table
This table contains the following columns:
* PRODUCTCATEGORY: Code of the product category
* DESCRIPTION: Description of the product category

### Color table
This table contains the following columns:
* COLOURID: Code of the color
* DESCRIPTION: Description of the color
