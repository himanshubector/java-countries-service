**Step 1 - Cloning the repository**

Clone the below application repository from the version control system (GitHub) 

Repository url : https://github.com/himanshubector/java-countries-service

You can use the below git command to clone the repository -
git clone https://github.com/himanshubector/java-countries-service


Following will be the structure of the cloned repository in your local system -

<img width="623" alt="assignment_1" src="https://github.com/himanshubector/java-countries-assignment/assets/107288435/bfaac4c6-7984-4900-a1e5-a1740b5385ce">



**Step 2 - Importing the project in IntelliJ IDE**

Open IntelliJ IDE and import the project by following the below steps :

a. Import the project by clicking File -> New -> Project From Existing Sources

<img width="535" alt="assignment_2" src="https://github.com/himanshubector/java-countries-assignment/assets/107288435/75fb9546-f0f9-465e-8689-b38cb06c5c04">



b. A pop-up window will open, navigate to the cloned repository path and select pom.xml which is present under country-service

<img width="792" alt="assignment_3" src="https://github.com/himanshubector/java-countries-assignment/assets/107288435/ed78a1e8-63f3-4f3d-b638-c48ac6ec6315">




**Step 3 - Build the application**


Build the application using Maven in IntelliJ IDE

Or 

You can also execute this below maven command : mvn clean install



**Step 4 - Run the application**

Right click on the Main class file and select “Run CountryServiceApplication”. ‘CountryServiceApplication’ is the main class name here.

IntelliJ IDEA will start the Spring Boot application.

OR

To run the Spring Boot application using ‘java -jar’ command :

Build the JAR file first using ‘mvn clean install’ command. The JAR file will be created under the ‘target’ directory.
After the build process is complete, navigate to the directory where the JAR file is located.
Open the terminal or command prompt in that directory.

Use the ‘ java -jar’ command to execute the JAR file as below : java -jar <application_name.jar>




**Step 5 - Run the JUnit tests**

a. Navigate to the Test class (CountryServiceImplTest) contaiining the JUnit tests that are to be run.
b. Right click and select ‘Run CountryServiceImplTest’ with Coverage c. IntelliJ IDEA will display the results in the “Run” tool window.

OR

We can also run the JUnit tests from the command line using the Maven build tool. For example, with Maven, we can run the command ‘mvn test’ to execute all the tests in our project.



**Step 6 - Test the application using POSTMAN client**

Below are the 2 endpoints that have been created :

a. http://localhost:8080/api/v1/countries/getByPopulationDensity (GET api) 
This endpoint will fetch the sorted list of countries in descending order.


b. http://localhost:8080/api/v1/countries/getAsianCountryWithMostNonAsianBorders (GET api)
This endpoint will fetch the details of the asian country which has the most non-asian border countries.



Dockerization of the Application and Deploying the Application to the local Kubernetes Cluster :

<img width="872" alt="Screenshot 2024-02-23 at 3 22 38 PM" src="https://github.com/himanshubector/java-countries-assignment/assets/107288435/35c90561-cccc-4fe8-acfc-630442f09bc6">


<img width="916" alt="Screenshot 2024-02-23 at 3 23 06 PM" src="https://github.com/himanshubector/java-countries-assignment/assets/107288435/230a5ea9-d5c5-44d7-87ec-d1ea0171a7c0">





