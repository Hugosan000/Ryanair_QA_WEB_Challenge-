# Ryanair_QA_WEB_Challenge-
About This repository was created for the purpose of performing the requested WEB QA test. This test consists of performing 1 test cases for the Ryanair Site on the https://www.ryanair.com/ie/en website and automating them using Robot Framework and Python/Selenium

Automation was created using Python 3.11.2 with Robot Framework 6.0.2 and Selenium Library.

Links to the tools used and their documentation.

Python

ChromeDriver

Google Chrome

Robot Framework:

pip install robotframework
Selenium Library:

pip install robotframework-seleniumlibrary
After cloning the repository, open it in your desired text editor, in my case I will be using VScode.

With the repository downloaded and the libraries installed, take the ChromeDriver downloaded earlier and place it in the root folder of your Python, it will probably be on disk C:, by doing this Selenium will find the file and run the automation. image

Now inside VSCode, when opening the terminal we can run our automation in 3 ways. Using the command

robot -d Results .\Test\ryanair_test.robot
It will start the automation of the test, automatically open the chrome pages and run the entire process of the automated test flow, and finally after 1-2 minutes it will finish the process and run the simple report in the terminal itself and on the Results folder that the program created.

image

It will cause the script inside the Resources folder file avenuecode_automation.resource to run, running the 1 test scenario which is:

✔Test Case 01 - Search a flight and login

The test scenario will be inside the test folder in the file bdds.features where they will be referenced and it is also possible to see all the bdds and their steps in full.

image

Also in the Resources folder, we can also see the code referenced in the main test that is avenuecode_automation.resource file where we will create the custom commands to be used for each BDD in the main automation sheet.

image

After finishing the automation process, you will see that the Results folder is populated with prints and XML files, allowing for a report of the automation and prints of when the step is finished.

image

Having accomplished all this process, your automation will already be functional and with reports available on the log on Results folder and with the scripts oriented to BDD, step for step. if you have any questions I'll be available! 😁

image
