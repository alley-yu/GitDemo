ReadMe file for Python Framework From Udemy Training

- PageObjects: Store all classes for each page
	- CheckoutPage.py
	- ConfirmPage.py
	- HomePage.py

- Report: Store all testing report html files

- TestData: Store test data related files, including excel file and python class
	- HomePageData.py
	- TestData.xlsx

- Tests: Real place to store all test cases
	- conftest.py: this may be put in Utility package, including web driver setup.. 
	- logfile.log: this may be put in a Log package.
	- test_e2e.py: Test whole scenario case.
	***  Form Submission ***
	- test_HomePage.py: Using fixture parameters (hard coding data sets, retrieving data sets from excel)
	- test_HomePage1.py: Retrieving data sets from excel and put them into a list. Use the list to send data.
	- test_HomePage2.py: Using fixture parameters, similar with test_HomePage.py, but can run specific case by specifying case number.

- Utilities: Store all common methods
	- BaseClass.py


Add something by GitDemo 10:52am

Add something by GitStuff1 11:12am
	
