# PalmasBank

This is the Web Application Online System Banking 


## Features

* Create Bank Account
* Deposit & Withdraw Money
* Transfer between accounts
* Bank Account Type Support(Primary Account, Saving Account)
* Report with a date range filter
* Possibility to make an appointment
* Balance
* Extensive use of Spring Framework, Spring MVC, Spring Security, Spring Data (Hibernate)

## Technologies

* Java
* HTML/CSS/JavaScript
* MySQL
* Spring Framework 
* Spring Boot

## Prerequisites

The following items should be installed in your system:

* Java 8 or newer
* git command line tool
* Your preferred IDE


### Steps
1) On the command line
    ```
    git clone https://github.com/Kamylek27/PalmasBank
    ```
2) Inside Eclipse or STS
    ```
    File -> Import -> Maven -> Existing Maven project
    ```

    Then either build on the command line `./mvnw generate-resources` or using the Eclipse launcher (right click on project and `Run As -> Maven install`) to generate the css. Run the application main method by right clicking on it and choosing `Run As -> Java Application`.

3) Inside IntelliJ IDEA
    In the main menu, choose `File -> Open` and select the Petclinic [pom.xml](pom.xml). Click on the `Open` button.

    CSS files are generated from the Maven build. You can either build them on the command line `./mvnw generate-resources` project then `Maven -> Generates sources and Update Folders`.

    A run configuration named `BankPalmasApplication` should have been created for you if you're using a recent Ultimate version. Otherwise, run the application by right clicking on the `BankPalmasApplication` main class and choosing `Run 'BankPalmasApplication'`.

4) Navigate to Petclinic

    Visit [http://localhost:8080](http://localhost:8080) in your browser.
