# jenkins-maven-jenkinsfile
jenkins-maven-jenkinsfile
https://www.javatpoint.com/maven-example

Compile the Maven Java Project:

To compile the project, go to the project directory,

for example: C:\Users\SSS IT\CubeGenerator and write the following command on the command prompt:
mvn clean compile 

Now, you will see a lot of execution on the command prompt. If you check your project directory, target directory is created that contains the class files.

Run the Maven Java Project:
To run the project, go to the project directory\target\classes,

for example: C:\Users\SSS IT\CubeGenerator\target\classes and write the following command on the command prompt:

java com.javatpoint.App  
Now, you will see the output on the command prompt:

Output of the maven example
Hello World!  


How to build the maven project or how to package maven project?
The mvn package command completes the build life cycle of the maven project such as:

validate
compile
test
package
integration-test
verify
install
deploy
Visit this link to know more about build life cycle http://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html

You need to execute the following command on the command prompt to package the maven project:

mvn package  
Now you will see that a jar file is created inside the project/target directory.

You can also run the maven project by the jar file. To do so, go to the maven project directory, for example: C:\Users\SSS IT\CubeGenerator and execute the following command on the cmd:

java -classpath target\CubeGenerator-1.0-SNAPSHOT.jar;.; com.javatpoint.App  
Now you will see the following output:

Hello World!  
