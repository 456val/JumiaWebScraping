#  Jumia Web Scraping for Discounts

This project automates the process of collecting and analyzing **product prices and discounts** from [Jumia](https://www.jumia.com.ng), one of Africa’s largest e-commerce platforms.  
It’s designed to help identify **price drops**, **track discounts**, and **monitor product trends** over time.

##  Project Overview

The notebook scrapes key product details such as:
-  **Product Name**
-  **Current Price**
-  **Old Price / Discount Percentage**
-  **Ratings & Reviews**
-  **Category / Subcategory**
-  **Product URL**

All collected data is then **cleaned, structured, and saved** in a CSV/Excel file for further analysis.

## Technologies Used

- **Python 3**
- **BeautifulSoup** – for parsing HTML
- **Requests** – for fetching web pages
- **Pandas** – for data cleaning and export
- **Jupyter Notebook** – for code execution and visualization

## Features
✅ Scrapes multiple pages automatically  
✅ Extracts and stores price & discount information  
✅ Saves clean data to `jumia_discount_data.csv`  
✅ Simple and reusable scraping logic  
✅ Ideal for building price-tracking or market-insight tools

##  Output

| Product Name | Current Price | Old Price | Discount | Rating | URL |
|---------------|---------------|------------|-----------|---------|-----|
| Samsung A14   | ₦120,000      | ₦150,000   | 20%       | 4.5⭐   | jumia.com.ng/... |

## How It Works

1. Send HTTP requests to Jumia category/product URLs  
2. Parse HTML with BeautifulSoup  
3. Extract product name, price, and discount data  
4. Clean and structure data using Pandas  
5. Export to CSV/Excel for analysis
   
## Future Improvements

- Add Selenium for dynamic content scraping  
- Automate periodic scraping (daily/weekly updates)  
- Integrate with a database for historical price tracking  
- Visualize discount trends over time

## License

This project is for **educational and research purposes only**.  
Respect the target website’s **robots.txt** and **terms of service** when scraping.


Example output file:
