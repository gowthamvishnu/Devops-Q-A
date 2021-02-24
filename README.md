# Devops-Q-A
1)agile methodology?
A)AGILE methodology is a practice that promotes continuous iteration(repitition) of development and testing throughout the software development lifecycle(SDLC) of the project. In the Agile model, both development and testing activities are concurrent(at the same time /continously), unlike the Waterfall model.
 
2)What Is the Waterfall Model?
A) The waterfall model is a linear project management approach, where stakeholder(may be client) and customer requirements are gathered at the beginning of the project, and then a sequential project plan is created to accommodate/fulfill those requirements/ execute the plan in a sequential manner.

3)what is devops?
A) Devops is a software development approch which involves Continous development,continous testing,continous integration,continous deployment,continous monitoring  of the software throughtout it's development lifecycle.

4)difference between agile and devops?
A)        Agile                        Devops
  Feedback from customers           Feedback from itself
  Smaller relese cycles             Smaller relese cycles,imeediate feedback
  Focus on speed                    Focus on speed and automation
  Not the best for business         Best for the business

5)explain about the devops lifecycle?
A)Devops lifecycle involves in  different stages.they are
  * Continuous Development
  * Continuous integration
  * Continuous testing
  * Continuous Deployment
  * Continuous monitoring

6)Explain Continous integration?
* This is the stage where the code functionality is integrated with the existing code. since there is continuous  development of software.
* The updated code needs to be integrated continuously  as well as smoothly with  the systems to reflect changes to the end user.
* The changed code should also ensure that there are no errors in the runtime environment. allowing 
  us to test the changes and check how it reacts with other changes.
  EX: Jenkins

7)Explain Continous deployment?
* It is the stage where the code is deployed to the production environment.
* Here we ensure that the code is correctly deployed on all the servers.
* If any addition of new feature ( or) functionality is introduced then one should be ready to welcome greater website traffic.
* So it is also the responsibility of the system admin to scale up the server to host more users.
* Since new code is continuously deployed on continuous  basis. configuration management tools play an important role for executing task quickly and frequently.

8)exain about continous development?
* This is the stage in the devops lifecycle where the software is developed continously unlike the waterfall model. 
* The software deliverables are broken into multiple sprints of short development cycles.Developed and delivered in a  very short time.
* This stage involves the coding and building phases and makes use of tools such as git and svn for maintaing the different versions of the code.
* Tools like anr/maven/gradle for building/package the code into executable file that can be forwaded to the "QA" for testing.

9)wht is jar file?
A)A JAR (Java Archive) is a package file format typically used to aggregate(collection) many Java class files and associated metadata and resources (text, images, etc.) into one file to distribute application software or libraries on the Java platform.

10)what is WAR file?
A)In software engineering, a WAR file (Web Application Resource or Web application ARchive) is a file used to distribute a collection of JAR-files, JavaServer Pages, Java Servlets, Java classes, XML files, tag libraries, static web pages (HTML and related files) and other resources that together constitute a web ...

11)what is EAR file?
A)EAR (Enterprise Application aRchive) is a file format used by Java EE for packaging one or more modules into a single archive so that the deployment of the various modules onto an application server happens simultaneously and coherently. ... Ant, Maven, or Gradle can be used to build EAR files.
  
12)explain about continous testing in Devops lifecycle?
A)* This is the stage where developed code is continuously tested for bugs.
  * For continous testing automation tools like "Junit,seleniu,TestNG are used.
  * These tools allows the QA's to test multiple codebases throuhly in parllel to ensure that there is no flaws in the funtionality.
  * once the code is tested it is continuously integrated with the existing code.
   CheckStyle for  coding standard” in Java. Using it will allow you to define and enforce good coding practices for a project.
   PMD is a cross-language tool that “finds common programming flaws like unused variables, empty catch blocks, unnecessary object creation, and so forth”.
   Using FindBugs allows teams to “inspect Java bytecode for occurrences of bug patterns”.

13)explain about continous deployment in Devops lifecycle?
A)* It is the satge where the code is deployed on all the servers.
  * Here we ensure that the code is correctly deployed on all the servers.
  * If there is addition of new feature or funtionality is introduced then one should be ready to welcome greater website traffic.
  * So it is also the responsibility of the systemadmin to scaleup the server to host more users.
  * since new code is continously deployed on continous basis,configuration tools play an important role for executing task quickly and frequently.
  * Containirazation tools also pla an important role in the deployment stage.
  * Docker and vagrant are the popular tools which help produce consistency across development,test,staging and production environments
  * they also helps in scaling up and scaling down of instances easily.

14) explain about continous monitoring in Devops lifecycle?
A)* This is very crucial stage in devops lifecycle.
  * which is aimed at improving the quality of the software by monitoring it's performence.
  * This practice involves the participation of the operations team who will monitor the users activity for bugs/any improper behavior of the system.
  * This can also be achieved by making use of dedicated monitoring tools which will continously monitor the application performence and highlight the issues.
  * Tool:spluck,ELK stack,Nagios,etc
  * This tools help you monitor the application and the servers closely to check the health of the system productively.
  * They can also improve the productivity and increase the realibility of systems,reducing IT support costs.
  * Any major issues found could be reported to the development team so that it can be fixed in the continous development phase.
  
