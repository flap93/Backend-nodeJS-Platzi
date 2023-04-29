# Backend-nodeJS-Platzi
A node JS course from Platzi


# Node js Basics 
## Configuration of Enviroment variables:
* Stored sensitive, such as database credentials or API keys
* Never hard coded into your application and must be define in your systems enviroment
* Once are defined you can use them like this : 'process.env.VARIABLE_NAME'
* 'process.env.VARIABLE_NAME || 'felix'' to set up enviroment variables by default
* always in capital letters 
## Call backs:
* It's when we pass fucntions as an arguments to another function 
* It's commonly use for asynchronous programming like making a HTTP request without blocking the main thread 

## Promises:
* is use to handle asynchronous operations.
* are more concise and readable way than traditional call back base approach
* Promises can be chained together with the methos then() and cathc() allowing you to perform a series of 
  asynchronous operations in a more elegant way 
