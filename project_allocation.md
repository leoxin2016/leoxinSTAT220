# Subject: Summary of Initial Team Discussion for the Concert Project.

## Objective: To kick off the project by domain model design, tasks allocation, and a communication workflow establishment.

### During the Week 6 lab session, we had an in-depth discussion to initiate the Concert project as follows:
1. We discussed the domain models with their class name (`Booking`, `Concert`, `Performer`, `Seat` and `User`), associated ORM with their primary key and Foreign key, entity or embeddable object, cascade types, the fields and methods of each class.
2. To minimize the chance of concurrency errors, we are using an `Optimistic Lock` with `@Version` in the `User` class and a `PESSIMISTIC_WRITE` Lock in the `Seat` class. 
3. We use **Discord** as a communication tool.
4. After committing and pushing to Github or merging to the `main` branch on `Github`, each member should send a message in **Discord** summarizing what the commit includes. 

### Task Assignment
- **Haoran Xin (hxin189)** is responsible for creating the 5 domain models(`Booking`, `Concert`, `Performer`, `Seat` and `User`) associated with their annotations, as well as development and integration testing for the `GET` method for **Concert enquiry** and the `POST` method for **login**.  
- **Joshua Daniel (jdan433)** is responsible for development and integration testing for **performer enquiry, booking a specific concert with seats, booking enquiry and authentication**. 
- **Chenghong Sai (csai446)** is responsible for development and integration testing for the whole `Publish/Subscribe` and pushing to the `submission branch`. 

### Schedule:
By week 6: Complete the team meeting to confirm the domain model class features.
By week 7: Each member completes his tasks of development and integration testing.
By week 8: Conduct Code review and perform client web application testing, try to open the application via the hyperlink http://localhost:10000/concert-webapp/.
By week 9: Push the final code to the `submission branch`.  
