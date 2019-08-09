# SWISH_TechnicalCheck
The code is written as a part of SWISH Online recruitment test.

Intially coffee is served at original price. From the next time customer orders the coffee, the bill is reduced to p% of the previous bill.
so, temp=(int)(temp*((float)(100-p))/100); is used to calculate the new price every time.
Inorder to calculate the total amount to be paid before getting a free coffee, the above calculated new price must be added to previous sum.
sum=sum+(int)(temp*((float)(100-p))/100); is used to calculate total required amount.
