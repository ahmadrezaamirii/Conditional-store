# Conditional store
---
## A store offers special discounts to its customers. The discount rules are as follows:

If the purchase amount is more than $1000, a 20% discount is applied.

If the purchase amount is between $500 and $1000, a 10% discount is applied.

If the purchase amount is less than $500, no discount is applied.

Write a program that receives the purchase amount from the user and displays the final amount.

input:
````
purchase_amount = float(input("Enter price: "))
if purchase_amount >= 1000 :
    discount = purchase_amount * 0.2
elif 500 <= purchase_amount < 1000 :
    discount = purchase_amount * 0.1
else :
    discount = 0
````
Calculation final amount:
````
final_amount = purchase_amount-discount
print(final_amount)
````
***
[My GitHub profile:](https://github.com/ahmadrezaamirii)

[My LinkedIn:](https://www.linkedin.com/in/ahmadreza-amiri-46936b1b2/)