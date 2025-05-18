# learning-fastapi
Learnings from various tutorials and courses (including projects)

### wHY fastapi is fast to code ? 
1. Automatic input validation --> using Pydantic 
2. Auto-Generated interactive Documentation
3. Seamless Integration with Mordern Ecosystem (ML/DL libraries OAuth , JWT, SQL-Alchemy, Docker, Kubernetes etc)


### HTTP methods 
- Software can be divided into:
1. Static - No user interactions, e.g. calender
2. Dynamic - Very interactive software, two way communication, MS excel 

when interacting with dynamic software, we can do 4 type of operations: CRUD
- C: Create 
- R: Retrieve 
- U: Update 
- D: Delete
 
Even website is kind of an software, installed in different machine (server) and access through different machine called client. 
There is a two way communication between client and server, that happens through a protocol called HTTP 

Static Website: Very less interaction, blog, govt website
Dynamic Website: Instagram (very high interactions) -- CRUD operations only. 

#### Whichever operation we are performing needs to be updated via HTTP 
- for e.g. we want to get own-profile from the website, then we will use VERB inside the HTTP called GET 
- pass some information via form etc. then we create verb  as POST  
- for update (VERB - PUT) 
- for delete (VERB - DELETE)

***These verbs are 4 methods for HTTP: GET POST PUT DELETE***


### Path Parameters: 
Path parameters are dynamic segments of a URL path used to identify a specific resource.
for e.g. http://127.0.0.1:8000/docs#/default/view_view_get/{5} --> 5 can be changed dynamically here, it `locates a specific resource` 
- helps in retrieval/update/delete of particular operations 

 

