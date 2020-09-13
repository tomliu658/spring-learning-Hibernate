# spring-learning-Hibernate

## Hibernate CRUD Apps

## What is Hibernate ?
A framework for persisting / saving Java objects in a database

view more on [here](http://hibernate.org/)

## Benefits of Hibernate

* Hibernate handles all of the low-level SQL

* Minimizes the amount of JDBC code you have to develop

* Hibernate provides the Object-to-Relational Mapping (ORM)

### ORM
The developer defines mapping between Java class and database table, ex:

```
// create Java object
Student theStudent = new Student("John", "Doe", "John@gmail.com");

// save it to database
int theId = (Integer) session.save(theStudent); 

// retrieve from database using primary key
Student myStudent = session.get(Student.class, theId);

```