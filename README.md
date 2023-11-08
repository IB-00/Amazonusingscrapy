# Amazonusingscrapy
i have scraped amazon kitchen products using python library scrapy. It helps me to understand how a popular website keep their user products record and all the websites ins and out. A small begineer friendly project.
The main goal in scraping is to extract structured data from unstructured sources, typically, web pages. Spiders may return the extracted data as items, Python objects that define key-value pairs.

# Creating Virtual Environment
cd path/to/my_scrapy_project
python -m venv myenv(For Windows)
pip install scrapy

# Activate the virtual Envionment
1)Environment Activation and Deactivation:
Activate:
D:\Scraping projects\part1>venv\Scripts\activate.bat
(venv) D:\Scraping projects\part1>

# After activating 
you can first check the website and do alot of stuff ins scrapy shell
scrapy shell "https://example.com"(Name of the website)
response.text
response.headers
etc
Deactivate:
(venv) D:\Scraping projects\part1>venv\Scripts\deactivate.bat
D:\Scraping projects\part1>
