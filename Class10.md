# Error Handling & Debugging In JS :
To find the source of an error, it helps to know how scripts are processed. 
 **execution contexts**

There is one global execution context; plus, each function creates a new
new execution context. 

Each time a script enters a new execution context, there are two phases
of activity: 
1. PREPARE

• The new scope is created

• Variables, functions, and arguments are created

• The value of the this keyword is determined 

2. EXECUTE

• Now it can assign values to variables

• Reference functions and run their code

### UNDERSTANDING SCOPE

In the interpreter, each execution context has its own variables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's variables object. 

### UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code. 

### ERROR OBJECTS

Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 

#### 
there are two things you can do with the errors. 
1. DEBUG THE SCRIPT TO FIX ERRORS 

2. HANDLE ERRORS GRACEFULLY 
 ## Consol Log
* The JavaScript console will tell you when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be.
 
* The JavaScript console is just one of several developer tools that are
found in all modern browsers. 
* You can also just type code into the console
and it will show you a result.
#### BREAKPOINTS 

You can pause the execution of a script on any
line using breakpoints. Then you can check the
values stored in variables at that point in time. 


#### STEPPING THROUGH CODE 

If you set multiple breakpoints, you can step
through them one-by-one to see where values
change and a problem might occur. 

#### CONDITIONAL
BREAKPOINTS 
You can indicate that a breakpoint should be
triggered only if a condition that you specify is
met. The condition can use existing variables. 


#### HANDLING EXCEPTIONS

If you know your code might fail, use try, catch, and finally.
Each one is given its own code block. 
**TRY, CATCH, FINALLY**































