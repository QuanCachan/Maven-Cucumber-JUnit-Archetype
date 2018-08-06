"# Maven-Cucumber-Junit-Archetype" 

Introduction
============

This archetype generates a Maven project with Cucumber and Junit Test embedded.

To install the archetype in your local repo:

	git clone https://github.com/QuanCachan/Maven-Cucumber-Junit-Archetype.git
	cd Maven-Cucumber-Junit-Archetype
	mvn install

Now, from the workspace that you want to create your Maven project using this archetype, follow these steps:
    
    First, ensure that there's no pom.xml file in your workspace directory.

    Then, type:

        mvn archetype:generate -DarchetypeGroupId=fr.henix.squash -DarchetypeArtifactId=maven-cucumber-junit-archetype -DarchetypeVersion=0.0.1-SNAPSHOT -DgroupId=myGroupId -DartifactId=myArtifactId
    						 
where *myGroupId* : group id of the project to be created; *myArtifactId* : artifact id of the project to be created

This archetype uses Java bindings for Cucumber version 3.0.2 and Junit version 4.12.

Project Structure
-----------------------------------

The project follows the standard Maven structure, so all the tests go in the *src/test/java* folder.  

JUnit
------
For more info around JUnit 4, go to https://github.com/junit-team/junit4/wiki.

Further Notes
-------
The project is just a starting point, feel free to modify it according to your needs. 

Credits
-------
The Maven-Cucumber-Junit-Archetype project is an open source project licensed under the Apache License 2.0.