# Automation-using-selenium
```markdown
# Amazon Product Scraper

## Description
This Python script uses Selenium to scrape product information from Amazon's website. It searches for a specified query, in this case, 'iphones,' and collects information about the products found.

## Prerequisites
- Python 3.x installed
- Selenium library installed (`pip install selenium`)
- Appropriate web driver installed (e.g., Chrome driver)

## Usage
1. Make sure you have Python and the required libraries installed.
2. Download and install the web driver compatible with your browser (e.g., Chrome driver for Google Chrome).
3. Update the code to specify the correct path to your web driver. For example:
   ```python
   driver = webdriver.Chrome(executable_path='path_to_chromedriver')
   ```
4. Run the script.
   ```bash
   python amazon_scraper.py
   ```
5. The script will open Amazon, search for 'iphones,' and collect product information.

## Output
- The script will print the number of products found and display the product names.

## Customization
- You can modify the script to search for different products by changing the query:
   ```python
   driver.find_element("xpath", "//input[@id='twotabsearchtextbox']").send_keys('your_product_query')
   ```

- You can also customize the web driver and its settings as per your requirements.

## Note
- Ensure that web scraping complies with Amazon's terms of service and legal regulations.

## Author
Akshit Singh

