# Largest Companies in the USA by Revenue - Python

## Objectives

The project "Largest Companies in the USA by Revenue - Python" aims to extract, clean, and analyze data regarding the largest companies in the USA based on their revenue. The primary objectives include:

- **Web Scraping**: Develop a web scraping tool using Python and BeautifulSoup to extract data from Wikipedia's list of the largest companies, processing over 100 records.
- **Data Cleaning and Transformation**: Implement data cleaning and transformation techniques to structure the scraped data into a pandas DataFrame, ensuring accuracy and completeness.
- **Key Information Extraction**: Extract essential information such as company rank, name, industry, revenue, growth rate, number of employees, and headquarters location.
- **Data Export**: Save the cleaned dataset to a CSV file for further analysis and visualization, demonstrating proficiency in data export and storage practices.
- **Market Analysis Application**: Utilize the dataset for marketing strategies or investment decisions regarding these companies.

## Impact

The impact of this project is significant in several ways:

- **Business Insights**: By analyzing the largest companies in terms of revenue, stakeholders can gain insights into market trends, industry performance, and competitive landscapes.
- **Investment Decisions**: The dataset can aid investors in making informed decisions based on company performance metrics such as revenue and growth rate.
- **Data Literacy**: The project showcases essential skills in web scraping, data cleaning, and analysis, which are increasingly valuable in today's data-driven job market.
- **Resource for Future Analysis**: The cleaned dataset can serve as a foundational resource for further analysis or visualization projects related to corporate performance.

## Method

The methodology for this project encompasses several key steps:

1. **Web Scraping**:
   - Utilize Python with the BeautifulSoup library to scrape data from the Wikipedia page listing the largest companies in the USA.
   - Make HTTP GET requests using the `requests` library to fetch the HTML content of the page.

2. **Data Cleaning and Transformation**:
   - Parse the HTML content using BeautifulSoup to navigate the DOM tree and extract relevant information.
   - Structure the scraped data into a pandas DataFrame, addressing any inconsistencies or missing values to ensure a reliable dataset.

3. **Key Information Extraction**:
   - Extract key attributes such as:
     - Company rank
     - Company name
     - Industry
     - Revenue
     - Growth rate
     - Number of employees
     - Headquarters location

4. **Data Export**:
   - Save the cleaned DataFrame to a CSV file using pandas' built-in functionality for easy access and further analysis.

This structured approach ensures that the project meets its objectives while providing valuable insights into the largest companies operating in the USA. By publishing this project on GitHub, it serves as a demonstrable example of technical skills in web scraping, data manipulation, and analysis using Python.