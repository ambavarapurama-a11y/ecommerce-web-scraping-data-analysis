# E-Commerce Web Scraping & Data Analysis

## Project Overview
This project demonstrates end-to-end web scraping and data analysis using Python. Real product data was scraped from an e-commerce website, cleaned, structured, and analyzed to extract meaningful business insights related to pricing, customer ratings, and product availability.

The project reflects real-world data analyst tasks where data is not always readily available and must be collected from external sources.


## Objective
- Scrape real-time product data from an e-commerce website
- Clean and transform raw scraped data into a structured format
- Analyze pricing, ratings, and availability trends
- Generate insights using data visualization


## Data Source
- Website: **books.toscrape.com**
- This website is a legal practice platform designed for learning web scraping.


## Tools & Technologies
- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- Jupyter Notebook


## Dataset Description
The scraped dataset contains the following columns:
- **Book_Name** – Name of the product
- **Price** – Product price
- **Rating** – Customer rating (1 to 5)
- **Availability** – Stock availability status

The final dataset is saved as:
  ecommerce_books_scraped_data.csv


## Project Workflow
1. Sent HTTP requests to fetch web page content  
2. Parsed HTML using BeautifulSoup  
3. Extracted product name, price, rating, and availability  
4. Cleaned and converted data into numeric formats  
5. Performed exploratory data analysis (EDA)  
6. Visualized pricing and rating trends  
7. Saved the cleaned dataset for further analysis  

## Key Insights
- Product prices vary significantly across listings
- Most products have mid-to-high customer ratings
- Rating distribution helps identify popular products
- Availability data can support inventory planning decisions

## Conclusion
This project demonstrates practical web scraping, data cleaning, and exploratory data analysis skills using Python. By transforming unstructured web data into meaningful insights, the project showcases real-world analytical thinking applicable to entry-level Data Analyst roles, especially in retail and e-commerce domains.



