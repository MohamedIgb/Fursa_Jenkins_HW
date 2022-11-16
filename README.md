# Fursa_Jenkins_HW

* in this task I created a java application managed by Maven that:
- Reads the “Breaking News” from YNet new service "http://www.ynet.co.il/Integration/StoryRss2.xml"
- presenting an html file that runs on localhost 8080

* Create a Jenkins CI/CD pipeline Job to Build and Deploy (Run) the application on a new
instance.
-Creates a Jar artifact and archives it.

to run the code:

  mvn clean package
  java -jar target/*.jar
  
  
