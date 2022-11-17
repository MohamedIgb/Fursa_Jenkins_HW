  # DevOps Jenkins Task  
######In this task I created a java application managed by Maven, and a Jenkins CI/CD pipeline Job to Build and Deploy (Run) the application on a new instance.
	- Reads the “Breaking News” from YNet new service "http://www.ynet.co.il/Integration/StoryRss2.xml".  
	- Presenting an html file that runs on localhost 8080.  
	- Creates a Jar artifact and archives it.  
	- Sending a slack.   
------------  
### To run this app:
1. Download [Java 17](https://www.oracle.com/java/technologies/downloads/#jdk17-mac "Java 17"). 
2. Clone the [repository](https://github.com/MohamedIgb/Fursa_Jenkins_HW.git "repository"). 
3. ######In your terminal:  
```sh  
$ mvn clean package  
$ java -jar target/*.jar  
```  

------------
###Jenkins stage view:
![Jenkins](https://user-images.githubusercontent.com/92742400/202436150-4f08f2c2-e463-4663-a311-d5d70c4de789.jpeg)



------------    
### Slack message: 
> Slack message can be changed at [jenkinsfile](https://github.com/MohamedIgb/Fursa_Jenkins_HW/blob/main/jenkinsfile "jenkinsfile") line 19.

<img width="1037" alt="Screen Shot 2022-11-17 at 13 29 29" src="https://user-images.githubusercontent.com/92742400/202434961-69b72085-8afb-4cd8-8ea8-2d32ddd0a72b.png">


  
  

