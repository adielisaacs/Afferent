Assignment Test plan
Requirements
The assignment / project is compressed into a zip file .
To run the application in your IDE do the following:
•	Unzip the project on your local drive   
•	Import the project into you IDE of choice 
•	To run the application navigate to the following package co.za.afferent.processor.AfferentExecution.java

•	run the following class and the outcome would print into the console
o	To run the UnitTests navigate to the following package
 co.za.afferent.test. AfferentTest.java

o	run the following class in your IDE as a UNIT Test
To run the application via command line do the following:
•	Unzip the project on your local drive   
•	Open your command line console
•	Navigate to the Unzipped project on your local drive 
•	1st run the application Tests with following command :
java -cp Afferent.jar;junit-4.12.jar;hamcrest-all-1.3.jar org.junit.runner.JUnitCore co.za.afferent.test.AfferentTest 
•	2nd run the application Execution with following command :
java -jar Afferent.jar
