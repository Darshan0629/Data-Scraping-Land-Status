# Dharani Telangana Web Scraping

## Overview
This project utilizes Selenium, a powerful web scraping tool in Python, to extract land status information from the Dharani Telangana website. By providing values such as district, mandal, and village via a Python script, the program retrieves and prints the survey numbers or sub-division numbers from the website.

## Prerequisites
Before running the script, ensure you have the following installed on your system:
- Python 3.x
- Selenium library (`pip install selenium`)
- Chrome WebDriver (or WebDriver corresponding to your browser)

## Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/dharani-telangana-web-scraping.git
   cd dharani-telangana-web-scraping
   ```

2. **Install Dependencies:**
   Make sure you have installed the required dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

3. **Provide Input Values:**
   Open the `main.py` file and provide the values for district, mandal, and village in the respective variables.

4. **Run the Script:**
   Execute the Python script using:
   ```bash
   python main.py
   ```

   This will launch a web browser, navigate to the Dharani Telangana website, input the provided values, and print the survey numbers or sub-division numbers.

## Configuration
If necessary, you can configure the script to use a different web browser or WebDriver. Ensure you update the WebDriver path in the `file.ipynb` file accordingly.
i
## Notes
- The script uses Selenium to interact with the website. Make sure to abide by the website's terms of service and usage policy.
- Handle any exceptions or errors gracefully to ensure smooth execution of the script.

## License
This project is licensed under the MIT License - see the [LICENSE]
