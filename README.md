Customer ID: A unique identifier to track individual customers and differentiate between them.
Name: Personalization of service and marketing communications.
Phone Number: Useful for quick communication about orders or delivery.
Address (Billing/Shipping): Needed for delivery orders or billing purposes.
Cart ID: Tracks the shopping session.
Associated Customer ID: Links the cart to a specific customer for account-based shopping.
Items in Cart: Tracks selected products for order preparation.
Total Price: Displays cost to the customer in real-time.
Discount Code: Allows for promotions to be applied directly.
Product
Product ID: Uniquely identifies each product.
Name: Clear identification for customer selection.
Description: Provides details to help customers understand what they’re buying.
Price: Essential for billing and transparency.
Ingredients: Caters to dietary preferences and allergy considerations.
Availability/Stock Status: Ensures customers are aware of product availability.
Category
Category ID: Organizes products into logical groups for easier browsing.
Name: Labels product groups (e.g., "Smoothies," "Yogurt Bowls").
Parent Category: Enables hierarchical structuring (e.g., "Desserts" → "Frozen Yogurt").
Customization Options
Customization ID: Tracks specific customizations for product personalization.
Associated Product ID: Links customization to relevant products.
Option Name: Describes the customization (e.g., "Extra Honey").
Additional Cost: Accounts for pricing variations due to customizations.
3. Order-Related Entities
Order
Order ID: Tracks individual orders for both customers and the store.
Customer ID: Links the order to the customer who placed it.
Order Date: Provides a timeline of orders.
Order Status: Helps in tracking progress (e.g., "Pending," "Delivered").
Payment Status: Ensures payment clarity for the business.
Total Amount: Reflects final billing details.
Delivery Type: Differentiates between in-store pickup and delivery orders.
Payment
Payment ID: Tracks each payment uniquely.
Associated Order ID: Links payment to the correct order.
Payment Method: Identifies how the customer paid (e.g., Credit Card).
Payment Date: Ensures payment timelines are clear.
Payment Status: Differentiates between successful, failed, or pending payments.
Delivery
Delivery ID: Tracks delivery operations.
Order ID: Connects delivery details to the respective order.
Delivery Address: Essential for ensuring correct delivery.
Delivery Time: Helps in customer communication and time management.
Delivery Status: Tracks the progress of the delivery.
4. Marketing & Promotions Entities
Discount Code
Code ID: Identifies each discount uniquely for tracking and redemption.
Code Value: Indicates the discount offered (e.g., "10% Off").
Expiry Date: Ensures promotions have a defined time limit.
Associated Customer: Enables personalized promotions
Employee
Employee ID: Tracks individual employees.
Name: Identifies employees for accountability.
Role: Differentiates between staff responsibilities (e.g., Delivery Driver, Cashier).
Contact Information: Ensures quick internal communication.
Inventory
Item ID: Uniquely identifies each inventory item.
Product/Topping/Ingredient Name: Tracks what’s in stock.
Stock Level: Monitors availability.
Restock Date: Helps predict inventory shortages
