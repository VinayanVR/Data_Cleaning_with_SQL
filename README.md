# Data_Cleaning_with_SQL
In this Project we are going to see how we can use SQL for cleaning the data 

## Intro : In this Project we are going to clean the data using SQL IN MYSQL Workbench
## The date contains the details of  housing sales  from some states  in USA

The Schema  we are going to use is

UniqueID	-  Int
ParcelID	- Varchar
LandUse	-         Varchar
SaleDate-         Varchar
SalePrice	- Varchar
LegalReference	- Varchar
SoldAsVacant	- Varchar
OwnerName	- Varchar
Acreage	        - Varchar
LandValue	- Varchar
BuildingValue	- Varchar
TotalValue	- Varchar
YearBuilt	= Varchar
Bedrooms	-Varchar
FullBath	- Varchar
HalfBath	- Varchar
ADDRESS	        - Varchar
CITY	        - Varchar
OWNER_ADDRESS	- Varchar
OWNER_STATE	 -Varchar
OWNER_CITY	  Varchar

1)IN the first step we are going to find the duplicate values and going to remove it
2) BREAKING CITY ADDRESS INTO INDIVIDUAL COLUMNS
3) Breaking  Owners ADDRESS into Invidiual Columns
4) CHANGING  Y & N  From SOLD AS VACANT AS YES AND NO
5) DROPING UNWANTED COLUMNS
