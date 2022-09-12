# Lab Assignment 2

This is a lab report for lab assignment 2 in DAT250. In the report I am going to discuss and address the following:

 - Technical problems that you encountered during installation and use of Java Persistence Architecture (JPA) and how you resolved

 - A link to your code for experiment 2 above. Make sure the included test case passes!

 - An explanation of how you inspected the database tables and what tables were created. For the latter, you may provide screenshots.

 - Any pending issues with this assignment that you did not manage to solve


## Technical problems

I had some issues downloading and setting up the Apache Derby Database. I tried to download it from the given link first but i had to use Homebrew to get it installed on MacOS. The problems arose when I had to set environment variables on Mac and even though it uses and Unix shell it would not permanently set them when running ```export DERBY_INSTALL = Some_file_path```. However I resolved that issue by permanently setting them in a file .zhrsc that saves them. After that I validated and checked that it was properly downloaded by running the following: 

<img width="720" alt="Skjermbilde 2022-09-09 kl  17 17 24" src="https://user-images.githubusercontent.com/90247464/189384599-50945767-7b4d-4f4d-9749-24d09a59691b.png">

I had to install Intellij and open the skeleton project found [here](https://github.com/selabhvl/dat250public/blob/master/expassignments/expass2.md) as a Maven project. After that it was pretty much smooth sailing with both Apache derby Database, Intellij and JPA. 

## Link to code for assignment 2
My code for assignment 2 can be found [here](https://github.com/P1T1B0Y98/DAT250-Assgnment2).

## Database tables and Tables created

### Assignment 1: Application using JPA 

Only thing I did her was to change the path in the persistence.xml and changed the downloaded version of Derby to 10.16.1.1 in the pom.xml. After that I ran the main.java and got the following databases and tables in Apache Derby. 
![image](https://user-images.githubusercontent.com/90247464/189386029-7ff64467-3b02-4dca-a4c9-44989af7a5ed.png)
![image](https://user-images.githubusercontent.com/90247464/189386093-d3048b9d-af12-4d79-9c98-ab736ab9ad1c.png)

### Assignment 2: Banking application using JPA

I had some trouble getting the test case to run. However after a while I made it work and the following diagram can be seen. 
<img width="904" alt="Skjermbilde 2022-09-09 kl  17 30 38" src="https://user-images.githubusercontent.com/90247464/189387114-facbd59c-f4c3-4fee-9845-bf409d88b656.png">

And here are the tables: 

<img width="824" alt="Skjermbilde 2022-09-09 kl  17 31 57" src="https://user-images.githubusercontent.com/90247464/189705610-e9188ce4-9c16-4529-a4c1-d99f8951191a.png">


## Pending Issues
None that I can find. 
