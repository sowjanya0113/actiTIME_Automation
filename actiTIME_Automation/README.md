## **Pytest Automation Framework**

This is an automation framework developed on Selenium, Python, and Pytest.
Sample test side used in this project is - https://online.actitime.com/test3/login.do

Page Object Model is followed in this framework

**pages** folder contains the elements and corresponding actions of the pages

**configuration** directory contains the configuration files

**requirements.txt** file contains all the python packages needed to run this framework

**reports** directory contains the html files generated with pytest-html reports



### **Commands to run the tests**

**To run the test with html report genaration**
pytest -s -v -m "login" --log-file=./Logs/automation.log --html=./Reports/report.html --self-contained-html --capture sys -rP  --disable-warnings testCases/test_login.py --browser chrome

