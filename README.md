# 🍕 Pizza Shop Data Analysis  

## 📖 Project Overview  
Find the zip file for the task named “Pizza+Place+Sales.zip” in the Datasets folder on the drive. It contains four CSV files: Orders, Order Details, Pizzas, and Pizza Types. You’ll also find a data dictionary that describes each dataset
Tip: You can join the four CSV files into a single data frame before you start your analysis.


Pizza Place Sales
A year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.
---

## 🗂️ Dataset  
- **Combined_df**
- **CombinedSize**: 48620 rows  
- **Features**:  
Table	Field	Description
- orders	order_id	Unique identifier for each order placed by a table
- orders	date	Date the order was placed (entered into the system prior to cooking & serving)
- orders	time	Time the order was placed (entered into the system prior to cooking & serving)
- order_details	order_details_id	Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
- order_details	order_id	Foreign key that ties the details in each order to the order itself
- order_details	pizza_id	Foreign key that ties the pizza ordered to its details, like size and price
- order_details	quantity	Quantity ordered for each pizza of the same type and size
- pizzas	pizza_id	Unique identifier for each pizza (constituted by its type and size)
- pizzas	pizza_type_id	Foreign key that ties each pizza to its broader pizza type
- pizzas	size	Size of the pizza (Small, Medium, Large, X Large, or XX Large)
- pizzas	price	Price of the pizza in USD
- pizza_types	pizza_type_id	Unique identifier for each pizza type
- pizza_types	name	Name of the pizza as shown in the menu
- pizza_types	category	Category that the pizza fall under in the menu (Classic, Chicken, Supreme, or Veggie)
-pizza_types	ingredients	Comma-delimited ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)

---

## 🛠️ Tools & Libraries  
- Python 🐍  
- Pandas – Data manipulation  
- Matplotlib / – Visualization  
- Jupyter Notebook – Analysis environment  

---

## 🔍 Analysis & Insights  
- **Recommended Analysis**
What is the total revenue/sales?
Find the total quantity sold.
Find the total orders.
How many pizza types do they sell?
Find the average price of the pizzas.
What are the peak hours of sales?
Find the total sales made on each day of the week. Which day of the week is when sales are made the most?
Find the top 5 bestselling pizzas.
Find the sales made in each month. Any trend noticeable?
Are there pizza types that are not doing well on the menu?

---

## 📊 Visualizations  
Some key charts include:  
- Month sales trend
- Quantity sold by pizza category  
- Quantity sold by Pizza sizes
