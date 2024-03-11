###Q1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
###Ans 1. The relationship between the "Product" and "Product_Category" entities is one-to-many. This means that a single product can belong to one category, but a category can have many products assigned to it.

###Q2. How could you ensure that each product in the "Product" table has a valid category assigned to it?
###Ans 2. Make the category_id field in the Product table not nullable: This would mean that every product must have a category_id assigned to it, and it cannot be left empty.
