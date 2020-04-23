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
|form            |Generates a form hook state with error and loading included. |
|onChange        |Generates an onChange property with the changeHandler impl.  |
|sfc             |Generates a simple function component with its own type.     |
|imr             |Import the React package in the file.                        |
|iml             |Starts the import line of a css file in the view.            |
|sfr             |Generates a simple function component with redux included.   |
|sfhci           |Generates a function component which inherits props from hook controller.   |
|sfci            |Generates a function component that inherits state and props from its Controller class. |
|reducer         |Generates a reducer with initial state and interfaces.       |
|dao             |Generates a data access object for an API. 				   |
|model           |Generates a model for some API data.						   |
|er              |error={props.error} || error={this.props.error}              |
|eli             |Imports the error and loading interfaces for react hooks.    |
|el              |Generates an error and a loading state, using react hook.    |
|inf             |Generates an interface of some type.						   |
|ss              |Generates a setState function.						       |
|ssc             |Generates a setState function with a callback.			   |
|foo             |Generates a named function with a return type.			   |
|efoo            |Generates an exported and named function with a return type. |
|egfoo           |Generates an exported and named function with a return type and a generic interface param. |
|floor           |Generates a Math.floor() function.            			   |
|ust             |Generates a React.useState instance.            			   |
|usef            |Generates a React.useEffect instance.            			   |
|usefnc          |Generates a React.useEffect instance without comment.        |
|doc             |Generates a javascript documentation.            			   |
|cdm             |Generates a componentDidMount lifecycle method.              |
|cdu             |Generates a componentDidUpdate lifecycle method. 			   |
|deriv           |Generates a static getDerivedStateFromProps method.		   |
|daofoo          |Generates an async function to access an API in the DAO.     |
|mdaofoo         |Generates an modelizing DAO function to load some list.      |
|cd              |Generats a cloneDeep import of lodash                        |
|map             |Generats a map import of lodash                              |
|uniqarr         |Generats a Set with Array.from to create a unique array.     |
|uniqarrobj      |Generates a unique array with Set, Array.from() and .flat()  that have object elements.   |
|for             |Generates a for loop with 'of'                               |
|forin           |Generates a for loop with 'in';                              |

# Repository URLs

**HTTPS**

> https://github.com/Tom-xacademy/xa-snippets.git