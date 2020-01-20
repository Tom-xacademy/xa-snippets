# Warning

This extension was created based on the folder and component structure we're using.
Hence, the imports are most likely going to point to non-existent files for others.

Sadly, Microsoft still doesn't support private extensions so here it is...

# Commands

|PREFIX          |DESCRIPTION                                                  |
|----------------|-------------------------------------------------------------|
|cc				 |Generates a class based typescript component.                |
|ccr             |Same as cc but with redux state and dispatch included.       |
|ctx             |Generates a react context with some type and a default value.|
|redux           |Generates the mapDispatchToProps and StateToProps functions. |
|mstp            |Generates a mapStateToProps function in the component.       |
|mdtp            |Generates a mapDispatchToProps function in the component.    |
|conn            |Imports the react-redux connect function from the module.    |
|sfc             |Generates a simple function component with its own type.     |
|imr             |Import the React package in the file.                        |
|iml             |Starts the import line of a css file in the view.            |
|sfr             |Generates a simple function component with redux included.   |
|sfhci           |Generates a function component which inherits props from hook controller.   |
|sfci            |Generates a function component that inherits state and props from its Controller class. |
|reducer         |Generates a reducer with initial state and interfaces.       |
|dao             |Generates a data access object for an API. 				   |
|cdao            |Generates a data access object for an API in a component.    |
|model           |Generates a model for some API data.						   |
|er              |error={props.error} || error={this.props.error}              |
|e               |Generates an error and a loading state, using react hook.    |
|inf             |Generates an interface of some type.						   |
|ss              |Generates a setState function.						       |
|ssc             |Generates a setState function with a callback.			   |
|fnc             |Generates a named function with a return type.			   |
|efnc            |Generates an exported and named function with a return type. |
|floor           |Generates a Math.floor() function.            			   |
|ust             |Generates a React.useState instance.            			   |
|usef            |Generates a React.useEffect instance.            			   |
|doc             |Generates a javascript documentation.            			   |
|cdm             |Generates a componentDidMount lifecycle method.              |
|cdu             |Generates a componentDidUpdate lifecycle method. 			   |
|deriv           |Generates a static getDerivedStateFromProps method.		   |
|daofoo          |Generates an async function to access an API in the DAO.     |

# Repository URLs

**HTTPS**

> https://github.com/Tom-xacademy/xa-snippets.git