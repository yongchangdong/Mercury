# Mercury
## a Spring and Hibernate based Shopping and Ordering system

## Structure of this project
![1](https://user-images.githubusercontent.com/63382428/105673642-2e9e4c00-5e9b-11eb-959c-12d83e94864c.PNG)

### Presentation tier

It’s the tier that users can access directly. It provides the application’s user interface. For example, how to register, login, display products, checkout in the browser and how to provide an easy way for users to send requests to the backend.
Language: HTML, CSS, Javascript
For our project, we are using JSP to dynamic rendering html content

### Logic tier
Maintain the business logic of the application, sitting between presentation tier and data tier, receive requests from presentation tier, make correct database operation, and return the final result back to the presentation tier.
Language: Java, Go, Python, …
We are using Spring MVC, Spring security and Spring webflow in our project

### Data tier
 
Mostly we don’t need to create a database system ourselves, we just need to use an existing one like MySQL. What we need to do is tell the database system how to store our data. For example, what does each table look like, what’s the relationship between each other.
Language: SQL
We are using Hibernate framework to operate the database 
## ER Diagram

![2](https://user-images.githubusercontent.com/63382428/105674056-cc921680-5e9b-11eb-85c2-f2817f114564.PNG)
