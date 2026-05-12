Here is my uml diagram that shows how user-webserver-database interact during login process. 
Yaml file is here for describing all processes and responding with responses like 200,201,404,400 and so on.
In the diagram shown:
1. User enters login and password 
2. Request is sent to the Web Server 
3. Web Server queries the Database 
4. Database returns user data 
5. Web Server validates credentials 
6. Web Server returns response: 
○ Success (token/session) 
○ OR Failure (error message)
