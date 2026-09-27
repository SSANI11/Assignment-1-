# Assignment-1-
Assignment 1
1) Sum, Count, Average:					
• What is the total price of all products in the dataset?					10100 =SUM(D2:D35)
• How many products are there in the dataset?					34 =COUNTA(B2:B35)
• Calculate the average price of the products.					297.0588235 =AVERAGE(D2:D35)
2) Min and Max:					
• Determine the minimum price among all products.					30 =MIN(D2:D35)
• Find the maximum price among all products.					1000 =MAX(D2:D35)
   3) IF Function:	
	• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.   =IF(D2>=500,"High Price","Standard Price")
4) SUMIF and COUNTIF:									
• Calculate the total price for products in the 'Electronics' category using the SUMIF function.				8050  =SUMIF(F2:F35,"Electronics",D2:D35)
• Determine the count of products with a price less than $100 using the COUNTIF function.								11   =COUNTIF(D2:D35,"<100")
5) Text Formatting - LEFT, RIGHT, MID:	
	• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function. =LEFT(A2,2)
	• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function. =RIGHT(A2,2)
	• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.  =MID(A2,4,3)
