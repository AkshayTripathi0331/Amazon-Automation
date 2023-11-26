# Amazon Shopping Cart Automation with Selenium

## Overview

This Python script utilizes Selenium to automate the process of adding a product to the Amazon shopping cart. The script is designed to search for a specific product on the Amazon website, click on the first result, and add the selected product to the shopping cart.

## Author

- **Author:** Akshay Tripathi
- **Version:** 3.10.6
- **Date:** 16-Aug-2023

## Prerequisites

Make sure you have the following installed before running the script:

- [ChromeDriver](https://sites.google.com/chromium.org/driver/) - Ensure that the path to ChromeDriver is correctly set in the script.


## now in the main directory create virtual environment and activate it and install the dependencies

for windows:
Steps to Create Virtual environment in Windows:
1.	Create : python -m venv venv
2.	Activate : venv\Scripts\activate
3.	Installing package: pip install package_name
4.	Deactivate: deactivate


## Dependencies

- [Selenium](https://www.selenium.dev/documentation/en/) - A Python library for browser automation.
- pip install selenium

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/AmazonAutomation.git
   cd AmazonAutomation
   ```

2. Install the required dependencies:

   ```bash
   pip install selenium
   ```

3. Update the `chromedriver_path` variable in the script with the correct path to your ChromeDriver executable.

## Usage

Run the script using the following command:

```bash
python amazon_cart_automation.py
```

Make sure to customize the `product_name` variable in the `search_and_add_to_cart` method to specify the product you want to add to the cart.

## Features

- **Search and Add to Cart:** The script performs a search on the Amazon website, clicks on the first result, and adds the selected product to the shopping cart.

## Disclaimer

This script is provided as-is and is meant for educational purposes only. Use it responsibly and at your own risk.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Copy and paste the above content into your `README.md` file. Feel free to customize it further if needed.