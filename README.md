# Contact Tracing Data Analysis

![IMAGE!](https://github.com/heshamalmosawi/contact-tracing-analysis/assets/151864110/97605133-7888-45bd-8c31-c4298bf6af88)

This project involves parsing COVID-19 contact tracing data from a HTML file named `contacttracing.htm` to extract key demographic information such as age, nationality, gender, and other relevant details. The data extraction process utilizes techniques commonly employed in web scraping, including pattern matching with regular expressions to capture specific information from the HTML file. Subsequently, the data is analyzed to identify patterns and trends related to spread of infections and other relevant insights. Atlast, all data is saved in a JSON file with the runtime day date, to maintain versions of data if any more patients were added to the website.

### Requirements
- Python 3
- Python libraries: 're', 'matplotlib', 'json'

## Usage
1. Install required Python libraries. 
2. Install Jupyter notebook
3. Run the script contacttracer.ipynb

## Notes

- Ensure that the HTML file is named (`contacttracing.htm`) and contains the necessary data for accurate extraction.
- Changing the file or contents may or may not lead to inaccuracies, as the code was written specifically for the Ministry Of Health website HTML page.