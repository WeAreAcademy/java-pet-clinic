# Java PetClinic Sample Application

## Running petclinic locally
Petclinic is a [Spring Boot](https://spring.io/guides/gs/spring-boot) application built using [Maven](https://spring.io/guides/gs/maven/).

## Run the Application

### Steps:



1) Choose a or b.
   
   a) EITHER Inside IntelliJ IDEA
      Select the File menu, New, and choose Project from version control. Use https://github.com/WeAreAcademy/java-pet-clinic.git as the URL.

   b) OR On the command line run:
   
       ```
       git clone https://github.com/WeAreAcademy/java-pet-clinic.git
       ```
   
3) Inside Intellij a run configuration named `PetClinicApplication` should have been created for you, otherwise, run the application by right-clicking on the `PetClinicApplication` main class and choosing `Run 'PetClinicApplication'`.  _Note that it may take a couple of minutes for this option to be available._

5) Navigate to Petclinic

   Visit [http://localhost:8080](http://localhost:8080) in your browser.


<img width="1042" alt="petclinic-screenshot" src="https://cloud.githubusercontent.com/assets/838318/19727082/2aee6d6c-9b8e-11e6-81fe-e889a5ddfded.png">

Or you can run it from Maven directly using the Spring Boot Maven plugin. If you do this, it will pick up changes that you make in the project immediately (changes to Java source files require a compile as well - most people use an IDE for this):

```
./mvnw spring-boot:run
```

## Prerequisites
The following items should be installed in your system:
* Java 17 or newer (full JDK, not a JRE).
* [git command line tool](https://help.github.com/articles/set-up-git)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/)
