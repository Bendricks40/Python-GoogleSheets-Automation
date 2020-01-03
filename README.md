# Python-GoogleSheets-Automation
Playing around with AWS, Python, and the Google API's to automate expense tracking


This is a helpful article I read to get started: https://www.twilio.com/blog/2017/02/an-easy-way-to-read-and-write-to-a-google-spreadsheet-in-python.html

The end goal of this project is to automate my personal budget spreadsheet. Currently, whenever a purchase is made on our credit card, I have an email alert that fires with date/merchant/amount any time a charge is run. I then manually add this to the family budget spreadsheet to track our expenses each month. This project will ultimately replace all the manual steps--the email alert will be sent to AWS, which will then invoke a lambda so that my python code can parse the email and add the data to my spreadsheet automatically. 
