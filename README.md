# Description
This is a Performance test script written in Jmeter. 

# Installation
Please download the .jmx and .csv files to your local environment. Drag and drop the .jmx file 
to Jmeter GUI. And update .csv file path in the script. Then you can run the script.

# Test steps

Only once with a single user on Jmeter;
1. 15 product information is added to the CSV (optional url, id etc.)
2. Product information is read from the relevant CSV and added to the cart.
3. During adding to the cart, it is checked whether the price of the product is below 100 TL. 
4. 10 items are added to the cart.
5. After adding 10 items in the basket, continue as a guest, go to the user information page, enter the user information (address etc.) .
6. Go to the payment screen with the relevant user .