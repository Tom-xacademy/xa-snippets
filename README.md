# Warning

This extension was created based on the folder and component structure we're using.
Hence, the imports are most likely going to point to non-existent files for others.

If you're interested in it, we have a Components, Store, and Interfaces folder.
In the Components, we use Controllers (containing the brain part of our react code), Views,
which contain the JSX stuff, and Models. DAOs are used to access APIs and modelize the responses.

# Commands

|PREFIX          |DESCRIPTION                                                  |
|----------------|-------------------------------------------------------------|
|cc				 |Generates a class based typescript component.                |
|ccr             |Same as cc but with redux state and dispatch included.       |
|redux           |Generates the mapDispatchToProps and StateToProps functions. |
|conn            |Imports the react-redux connect function from the module.    |
|sfc             |Generates a simple function component with its own type.     |
|sfci            |Generates a function component that inherits state and props from its Controller class. |
|reducer         |Generates a reducer with initial state and interfaces.       |
|dao             |Generates a data access object for an API. 				   |
|cdao            |Generates a data access object for an API in a component.    |
|model           |Generates a model for some API data.						   |
|mf              |Generates a model factory for some model instance.		   |
|inf             |Generates an interface of some type.						   |
|ss              |Generates a setState function.						       |
|ssc             |Generates a setState function with a callback.			   |
|fnc             |Generates a named function with a return type.			   |
|efnc            |Generates an exported and named function with a return type. |
|floor           |Generates a Math.floor() function.            			   |
|ust             |Generates a React.useState instance.            			   |
|usef            |Generates a React.useEffect instance.            			   |

# Repository URLs

**HTTPS**

> https://github.com/Tom-xacademy/xa-snippets.git

**SSH**

> git@github.com:Tom-xacademy/xa-snippets.git
