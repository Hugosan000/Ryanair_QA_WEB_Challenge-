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

With the repository downloaded and the libraries installed, take the ChromeDriver downloaded earlier and place it in the root folder of your Python, it will probably be on disk C:, by doing this Selenium will find the file and run the automation. 
![image](https://user-images.githubusercontent.com/61331185/229642584-83f3e99a-ca14-4bee-a14b-e4aab947b2d2.png)


Now inside VSCode, when opening the terminal we can run our automation in 3 ways. Using the command

robot -d Results .\Test\ryanair_test.robot
It will start the automation of the test, automatically open the chrome pages and run the entire process of the automated test flow, and finally after 1-2 minutes it will finish the process and run the simple report in the terminal itself and on the Results folder that the program created.

![image](https://user-images.githubusercontent.com/61331185/229642611-8f8580ac-69b1-4485-a9c3-f84ef7ae556e.png)


It will cause the script inside the Resources folder file avenuecode_automation.resource to run, running the 1 test scenario which is:

✔Test Case 01 - Search a flight and login

The test scenario will be inside the test folder in the file bdds.features where they will be referenced and it is also possible to see all the bdds and their steps in full.

![image](https://user-images.githubusercontent.com/61331185/229642643-475a768c-42cb-4d95-8433-eb7fa1da0ce5.png)


Also in the Resources folder, we can also see the code referenced in the main test that is avenuecode_automation.resource file where we will create the custom commands to be used for each BDD in the main automation sheet.

![image](https://user-images.githubusercontent.com/61331185/229642663-b6864bc4-aafb-4945-9316-dee06fb1b69e.png)


After finishing the automation process, you will see that the Results folder is populated with prints and XML files, allowing for a report of the automation and prints of when the step is finished.

![image](https://user-images.githubusercontent.com/61331185/229642692-bdc6badc-d935-4109-b784-5fe7ac85e661.png)


Having accomplished all this process, your automation will already be functional and with reports available on the log on Results folder and with the scripts oriented to BDD, step for step. if you have any questions I'll be available! 😁

![image](https://user-images.githubusercontent.com/61331185/229642708-9c427b86-0575-43a8-bc79-33b60243d8ad.png)
