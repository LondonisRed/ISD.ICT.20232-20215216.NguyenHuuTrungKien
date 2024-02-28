To place an order ,we need these use cases: “Checkout and payment”, “View Cart”, “Edit cart information”, “Review and Cancel Order”.
1. View Cart 

Basic flow:
- customers need to review the cart and select the products they want to purchase

2. Edit Cart information 

Basic flow:
- The software allow customers to modify quantity of products, remove and add products.
- The software display cart information, including the total price of
products excluding VAT, the total price of products including VAT, a list of products with product information (product name, quantity, and price).

Alternative flow:
- Notify customers if the inventory quantity of any product is insufficient and will display the quantity of each product that is lacking.

3. Checkout and payment

Basic flow:
- The customers request to place an order.
- The software check whether the inventory quantity is sufficient to provide to the customer.
- If yes then go to filling delivery information.
- The software will ask customers to set up delivery information. 
- Each time customers enter or update the delivery address, the software will calculate (or recalculate) the delivery fee, total product price including delivery fee.
- The software will check the input information. ask customers to update if there are any required fields left blank or invalid information.
- If there no mistake, the software allow the customers to process to provide payment information. 
- Customer have the option to select rush order delivery.
- The software checks whether the delivery address supports this service and if any
products are eligible.
- In cases where both the products and delivery address support rush order delivery, the software requests additional rush order delivery information from the customer.
- Customers can adjust the delivery method or the items they wish to purchase if necessary.
- The software recalculates the delivery fees and updates the corresponding invoice.
- The software will display and temporarily save invoice information, including the list of products in the cart, quantity, product prices, total product price excluding VAT, total product price including VAT, delivery fee, and total amount to be paid.
- Customers select a payment method. 
- For each payment method, customers need to provide the necessary information as requested.
- After a successful payment, the software will display the transaction ID, cardholder's name, deducted amount, transaction details, and transaction date and time.

Alternative flow:
+ Flow 1:
	- The software will ask customers to update the cart if the inventory quantity is insufficient and will display the inventory quantity for each unmet product.
	-  The customers request to place an order again.
+ Flow 2:
	- The software ask customers to update the cart there are any required fields left blank or invalid information.
+ Flow 3:
	- If no products are eligible or the delivery address doesn't support rush order
delivery, the software prompts the customer to update the delivery information or delivery method.


4. Reviewing and cancel order.

Basic flow:
- The order will be in a pending processing state, and the software will send all order and transaction information to the customer's email. 
- Customers can review order information or cancel orders using the link sent in the email regarding the order and transaction.
- Customers can choose to cancel the order when reviewing the order information before the order is approved.
- After the customer confirms the cancellation, the full amount will be refunded to the payment method used for this order through VNPay.