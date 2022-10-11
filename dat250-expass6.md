# Experiment Assignment 6

The goal for this assignment was to make initial experiments front-end technologies for enterprise applications. 

## Experiment 1    
For the first part of the assignment we were asked to complete [this](https://spring.io/guides/gs/serving-web-content/) 
tutorial on serving web content with Spring MVC. No problems encountered with this tutorial, attached is a screenshot of my localhost displaying "Hello Peter" to inidcate that it is up and running.    
<img width="874" alt="Skjermbilde 2022-10-11 kl  12 03 40" src="https://user-images.githubusercontent.com/90247464/195061751-ad611589-cfcb-4338-a15e-ab6866895680.png">


## Experiment 2   
For the second part of the experiment we were asked to build a SPA with Angular that implements the Todo-list made in assignment 4. 
The application should also use the Rest-API developed for Todos and be able to:

    1. Load todos using the Todo-API (HTTP GET),
    2. Display all todos in a table, including a delete button in every row (HTTP DELETE),
    3. Refresh displayed todos by clicking a button (HTTP GET),
    4. Add a todo by giving its description and summary (HTTP POST).

To try this on your computer you must do the following:    

   1. Clone the following [repo](https://github.com/P1T1B0Y98/dat250-sparkjava-counter) into an IDE of your choice. This contains the Todolist 
     operations and the Rest-API for Todos. 
   2. Switch to the test branch and run the TodoAPI found in the src folder. 
   3. Clone and open the following [repo](https://github.com/P1T1B0Y98/Experiment6-SPA) into an IDE of your choice. This is the SPA for the Todos made
     with Angualar. 
   4. Open a new terminal window and find the directory for the SPA application and run 'ng serve'.
   5. Navigate to http://localhost:4200 to see the SPA. 

A few screenshots from the SPA: 

**Initial page:**<br/>    
<img width="1440" alt="Skjermbilde 2022-10-11 kl  12 17 07" src="https://user-images.githubusercontent.com/90247464/195064612-06e8c131-26f5-413d-b38b-3dc2fd0f510c.png">


**Display todos:**<br/>
Click the "todos" button and the SPA displays all curent todos in a table. HTTP GET. Initially there are no todos so we get the following:    
<img width="1440" alt="Skjermbilde 2022-10-11 kl  12 15 38" src="https://user-images.githubusercontent.com/90247464/195065112-a90a7cd1-f076-4884-8b98-8d21b020105d.png">


**Add todos:**<br/>
Fill in the input fields and click add. This adds the todo to the todolist if both "summary" and "description" is filled out. This is an HTTP POST.    
<img width="1440" alt="Skjermbilde 2022-10-11 kl  12 15 55" src="https://user-images.githubusercontent.com/90247464/195065383-fbeb9f3b-6b07-4073-ad1c-b39fcab19411.png">


**Refresh todos:**       
This button should be clicked after adding an todo such that it is displayed in the table. This runs the HTTP GET request.     
<img width="1440" alt="Skjermbilde 2022-10-11 kl  12 16 03" src="https://user-images.githubusercontent.com/90247464/195065567-a29e41f3-65bb-4813-b2b5-41a2508fed90.png">

**Delete todos:**     
This button when clicked deletes a todo from the list and the table.     

## Techincal issues before and after <br/>   
There are currently no technical issues. I spent some time learning Angular by doing an Angular crash course tutorial before doing this assignment to better understand how it works. Therefore, I did not run into a lot of problems.     

## Code

[Link to Todo repo](https://github.com/P1T1B0Y98/dat250-sparkjava-counter). <br/>
[Link to SPA](https://github.com/P1T1B0Y98/Experiment6-SPA). <br/>
[Link to first assignment](https://github.com/P1T1B0Y98/Experiment6.1). <br/> 






