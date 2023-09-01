# Housing-Data-Portfolio-Project
The dataset was cleaned and queried using SQL Server.

# IMPORTING DATA
I created a database called Project, then imported the dataset which I named Housing in Microsoft SQL Management Server Studio.

# DATA CLEANING
[Uploading image.png…]
![Uploading image.png…]()



# Going through the dataset, I observed that the dataset needed cleaning.

The Date is not in the standard format.
Some rows in the PropertyAddress is NULL
The PropertyAddress has both the City and House Address in the same column.
The OwnerAddress has the state, city, and address on the same column.
Some roles in the SoldAsVacant has Y and N instead of Yes or No.
There are some duplicate rows that need to be removed.
Some Columns would not be useful for the analysis and therefore should be deleted.

# Housing Data – Data Cleaning. 
Converted the Sale Date to the standard date format 
Populated the PropertyAddress Column (Replaced Null Values with Required Data By analyzing based on ParcelId Column). 
Separating the PropertyAddress Column Into City and PropertySplitAddress . 
Splitting the OwnerAddress into three. 
Changing Y and N to Yes and No in SoldAsVacant Column 
Removing Duplicate Rows 
Deleting Unused Columns 

 
 
