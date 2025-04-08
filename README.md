# [Rent Calculator](https://github.com/hainguyen1511/C-plus-plus/blob/main/Nguyen-Hai-prog1.cpp)
* Algorithm for the rental calculating program
> [!NOTE] 
> Step 1 – I will print the “Welcome the user to calculator”.
Side detail: I need to figure out the data type of the program first it might be float or double since we need to multiply rational number. I can assume the correct data types are entered by the user. This program will ask for input, also it will guide user what is for input. 
1a. The program will ask the user to input the width "Input the width in feet: "
1b. The program will ask user to input the length "Input the depth in feet: "
1c. The program will ask user how long they stay in month "How long you want to rent: "
1d. The program will ask user the popularity require of the location "Do you want locked with wall or not? (1 Yes,0 No): "
1e. We use the base price for the input "The popular rate from 0-100 in percentage: "

> [!NOTE]
> Step 2--Echo out the information in this format: Your input is….by…. feet ………month of rental, there is ……space need to be locked and surrounded by full walls. Busy rate you want is…%. And the base price is per square feet"
Side detail: The number is filtered and does not need to be verify at this point. I will make sure there is separate value to hold total amount because we will show the total amount first before calculation. For calculation make sure data type are same. Different data type can result in calculation error.

> [!NOTE]
> Step 3 – The calculation of the program.
Show the total amount of money first without deduction or surcharge in it.
3a. deduction = total amount * 0.05 when rented month more than 1 month less than 4 months.
3b. deduction = total amount * 0.2 when more than 4 months.
3c. surcharge = total amount * 0.3 when locked space is.
3d. I am trying to figure out this paragraph “The price per square foot price is increased directly proportionally to the amount of foot traffic received with $100 price per square foot for the highest price possible.” The math will be base price + popular percentage * 100 per square feet
> [!NOTE]
> Step 4--I will show the deduction, surcharge and popular cost and the total amount.
Side detail: I will make sure to reset values here to reenter the inner loop.

> [!NOTE]
> Step 5—I will ask the user if they want to quit. The whole program should be in a loop until the user change conditional value.

> [!NOTE] 
> Step 6—End the program properly.
