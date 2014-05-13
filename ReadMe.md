## What is this about ?

This is a very basic coding test.

You have :

 - an implementation class where you must fill the blanks
 - a JUnit Test class that tells you what is the expected behavior

## How code and run the tests

### Using Maven

If you have maven installed you can simply type 

    mvn install

This will run the build and the tests.

You can edit the implementation with whatever tool you want.

### Using Eclipse and Maven

If you have maven installed, but prefer to use Eclipse IDE :

generate the Eclipse project :

    mvn eclipse:eclipse

Import the maven project inside Eclipse

    Import > Existing Project into Workspace > select the directory of the project 

### Using Eclipse without Maven

If for some reasons, you dont want to use Maven :

 - create a Java project
 - add JUnit inside your class path
 - import the 2 source files (implementation + tests)

## Rules and expected result 

The goal is to have all unit tests passing.

 - Time  : this is not a race, but it is clear that implementation should not take hours !
 - Implementation : of course, having a rather clean implementation does matter.
 - Dependencies : you should not need to add any specific dependencies
 - Java version : test is aligned on Java 7, but you should be able to use whatever you want

