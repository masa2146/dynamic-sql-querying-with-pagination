# Codebase for the blog post Dynamic SQL Querying & Pagination with Querydsl and Spring Data JPA
---
Steps to run this project:

Visit the following endpoint within your browser or a REST client (e.g. Postman): http://localhost:8080/persons
Play around with the filtering criterias and the requested page and its size e.g.:
 - http://localhost:8080/persons?firstname=Max&page=0&size=5
 - http://localhost:8080/persons?firstname=Max&lastname=Schmid&page=0&size=5
 - http://localhost:8080/persons?firstname=Duke&lastname=Schmid&page=0&size=50
 - http://localhost:8080/persons?firstname=Duke&lastname=Schmid&budget=1337&page=0&size=50
 - http://localhost:8080/persons?firstname=Duke&lastname=Schmid&budget=1337&page=0&size=50
 - http://localhost:8080/persons?firstname=Duke&lastname=Schmid&budget=1337&dobLimit=976579200&page=0&size=50
 - http://localhost:8080/persons?page=42&size=42

 - http://localhost:8080/persons/simplified?lastname=Lewis&page=1&size=4
 - http://localhost:8080/persons/simplified?firstname=Max&lastname=Harris
 - http://localhost:8080/persons/simplified?budget=8686
