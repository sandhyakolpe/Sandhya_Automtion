# Sandhya_Automtion
<p>
Run the Project
first We have to delete the target directory
right click on project or pom.xml file go to the run as option and click on meven clean.

and on commond line 
mvn clean
it is used to run the  test cases 
		- on UI command
				right click on project or pom.xml file go to the run as option and click on meven test.

		- command line
				mvn test

after adding the dependency if any jar files is not downloaded then we can use maven install
		- maven update
		 on UI command
				right click on project or pom.xml file go to the run as option and click on meven install.

		- command line
				mvn install

it is used to validate the source code
		 on UI commandc
				right click on project or pom.xml file go to the run as option and click on build then enter goal as validate and click on run 

		- command line
				mvn validate
</p>

<p>clean install test
#compile validate package verify
mvn clean install
mvn install test
 mvn clean install test</p>

 <p>The strategy you employed for this challenge.

 Sceneario is little beat difficult to understand.
 finding the webelement easy way
 we use relative xpath.

 we need to perform the upcasting concept.
 *we have launch the browser
 *maximize the browser
 *find the Webelement
 *perform the assertion
 *then handle alert popup using selenium
 *add the plugins in pom.xml for maven 
 *download all the jar files into the .m2 folder in  local machines
 *run the application on commond line
 * first clean the maven
 *run the maven  test commond on commond line.
 </p>

