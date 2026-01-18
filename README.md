Login

This project demonstrates automated web testing using Python.
It automates a login system and shopping card functionality on "SauceDemo" website.With screenshot capture in case of failure
and HTML report.The framework captures screenshots whenever a test fails and generates an HTML report for easy test result analysis.

🛠️ Tools used:
  -Python
  -Selenium
  -Pytest
  -WebDriverWait
  
🧪 What happen in the code:
- Successful login with valid credentials
- Add product to cart
- Screenshot capture on test failure
- HTML test report generation

How to run the code👇🏻

 Install dependencies:

pip install -r requirements.txt

Clone the repository:

```bash
git clone https://github.com/GabrielBenford/Login.git
cd Login
```
HTML report:

pytest --html=report.html --self-contained-html
