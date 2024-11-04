# SQL-SCANNER
# SQL Injection Scanner

This SQL Injection Scanner is a simple Python-based tool designed to detect potential SQL injection vulnerabilities in web applications. It automates the process of identifying vulnerable forms by sending crafted input data and analyzing the responses for common SQL error messages. The scanner works by first retrieving all HTML forms from a specified URL, collecting their action URLs, methods, and input fields. For each form, it sends test data that includes characters often exploited in SQL injections, such as single and double quotes. After submitting the forms, the scanner checks the responses for common SQL error messages that indicate a vulnerability, thereby reporting any detected vulnerabilities.

To get started, ensure you have Python 3.x installed, along with the required libraries: `requests` and `BeautifulSoup` (part of `bs4`). You can install these libraries using pip. To install the scanner, clone the repository from GitHub and navigate to the project directory. Running the script is straightforward; simply execute it in your terminal, and it will start scanning the default URL, which is set to `https://cnn.com`. You can modify this URL in the script to target any specific web application you have permission to test.

It's important to note that this tool is intended for educational purposes only. You should only use it on applications that you own or have explicit permission to test, as unauthorized scanning can lead to legal consequences and is considered unethical. This project is licensed under the MIT License, and you can contribute to it or raise issues if you encounter any bugs or have suggestions for improvements.

Happy scanning!
