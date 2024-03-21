
# Ecommerce Analysis 📊

## Project Description
This project aims to analyze ecommerce activity using the Instacart Market Basket data to uncover insights into consumer behavior, product popularity, and shopping patterns. By examining datasets related to aisles, orders, departments, products, and order_products, the analysis provides a comprehensive view of the shopping trends on the Instacart platform.

## Technologies Used
- Python 🐍
- SQL 🛢
- pandas 🐼
- psycopg2
- SQLAlchemy

## Languages Used
- Python
- SQL

## Process of the Project
The project follows a structured approach to data analysis:
1. **Data Loading**: Using Python with pandas for loading data into a SQL database.
2. **Database Connection**: Utilizing psycopg2 and SQLAlchemy for SQL database connections and engine creation.
3. **SQL Operations**: Performing data manipulation and analysis using SQL to prepare data for a detailed examination.
4. **Data Analysis**: Conducting various analyses to explore consumer behaviors, product trends, and order patterns.

## Datasets
The analysis utilizes datasets from the [Instacart Market Basket Analysis](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data) competition on Kaggle, focusing on:
- `aisles`: Contains information on the category of each product.
- `departments`: Provides details about the department classification of items.
- `orders`: Records of orders, including order time, user ID, and order sequence.
- `products`: Product details including product name and its association with aisles and departments.
- `order_products`: Mapping of products to orders, indicating which products were bought together.

## Data Model
The project's data model, designed using draw.io, illustrates the relationships between tables such as Orders, Products, Order Products, Aisles, and Departments. This model is crucial for understanding the structure of the database and the interactions between different data entities.

## Operations in Python and SQL Files
- **Python File**: Utilizes pandas for data manipulation, psycopg2, and SQLAlchemy for database interactions, facilitating the data loading process.
- **SQL File**: Contains commands for creating temporary tables to join orders, products, and order_products, enabling comprehensive analysis of order details and product information.

## 🚀 Getting Started
To replicate this analysis:
1. Ensure Python is installed on your system.
2. Install required libraries using `pip install pandas psycopg2 sqlalchemy`.
3. Set up your SQL database and use the provided SQL file to structure your database.
4. Use the Jupyter Notebook for loading data and performing initial analyses.

## 📈 Analysis and Insights
The project uncovers various insights into shopping behavior, including product popularity, reordering patterns, and time-based shopping trends. For detailed findings, refer to the analysis section within the Jupyter notebook.

## 📚 Additional Information
For further details on the datasets, operations, and analyses conducted in this project, please refer to the accompanying Jupyter notebook and SQL script.

## 🤝 Contributing
Contributions to extend or improve the analysis are welcome. Please ensure to follow the project's contribution guidelines.

## 📜 License
This project is open-source and available under the MIT license.

## 🙏 Acknowledgements
Special thanks to Kaggle for providing the Instacart Market Basket Analysis dataset and to the developers of the libraries used in this project.
