# Warning

This extension was created based on the folder and component structure we're using
at the company, so some of the snippets may contain imports that will point
to non-existent files for you.

This is still released this way (instead of vsce packaging) because I didn't want to bother with copy-pasting and Microsoft still doesn't support private extensions, unfortunately. Regardless, you may find most of these useful but you can also feel free to fork it and create your own version, or just create an issue on GitHub and I'll see if I can fix/change what you need.

# Commands

| PREFIX       | DESCRIPTION                                                                                |
| ------------ | ------------------------------------------------------------------------------------------ |
| cc           | Generates a class based typescript component.                                              |
| ccr          | Same as cc but with redux state and dispatch included.                                     |
| ctx          | Generates a react context with some type and a default value.                              |
| redux        | Generates the mapDispatchToProps and StateToProps functions.                               |
| mstp         | Generates a mapStateToProps function in the component.                                     |
| mdtp         | Generates a mapDispatchToProps function in the component.                                  |
| conn         | Imports the react-redux connect function from the module.                                  |
| form         | Generates a form hook state with error and loading included.                               |
| onChange     | Generates an onChange property with the changeHandler impl.                                |
| sfc          | Generates a simple function component with its own type.                                   |
| pfc          | Generates a simple function component without props.                                       |
| sfcg         | Generates a simple function component which takes a generic as its type.                   |
| sfcs         | Generates a simple function component which also has a loading and error state.            |
| imr          | Import the React package in the file.                                                      |
| iml          | Starts the import line of a css file in the view.                                          |
| ims          | Starts the import line of a css file in the view.                                          |
| sfr          | Generates a simple function component with redux included.                                 |
| sfhci        | Generates a function component which inherits props from hook controller.                  |
| sfci         | Generates a function component that inherits state and props from its Controller class.    |
| sfcv         | Generates a function component that inherits every prop from the parent view.              |
| reducer      | Generates a reducer with initial state and interfaces.                                     |
| dao          | Generates a data access object for an API.                                                 |
| model        | Generates a model for some API data.                                                       |
| er           | error={props.error}                                                                        |
| eli          | Imports the error and loading interfaces for react hooks.                                  |
| iel          | Adds the error and loading props to the interface.                                         |
| el           | Generates an error and a loading state, using react hook.                                  |
| inf          | Generates an interface of some type.                                                       |
| ss           | Generates a setState function.                                                             |
| ssc          | Generates a setState function with a callback.                                             |
| foo          | Generates a named function with a return type.                                             |
| efoo         | Generates an exported and named function with a return type.                               |
| egfoo        | Generates an exported and named function with a return type and a generic interface param. |
| floor        | Generates a Math.floor() function.                                                         |
| ust          | Generates a React.useState instance.                                                       |
| usef         | Generates a React.useEffect instance.                                                      |
| usefnc       | Generates a React.useEffect instance without comment.                                      |
| doc          | Generates a javascript documentation.                                                      |
| cdm          | Generates a componentDidMount lifecycle method.                                            |
| cdu          | Generates a componentDidUpdate lifecycle method.                                           |
| deriv        | Generates a static getDerivedStateFromProps method.                                        |
| daofoo       | Generates an async function to access an API in the DAO.                                   |
| daofoofull   | Generates four DAO functions for each request type (POST/PATCH/GET/DELETE).                |
| daofoopost   | Generates a POST-type async function in the DAO.                                           |
| daofoopatch  | Generates a PATCH-type async function to access an API in the DAO.                         |
| daofoodelete | Generates a DELETE-type async function to access an API in the DAO.                        |
| daofooget    | Generates a GET-type async function to access an API in the DAO.                           |
| daofoogetone | Generates a GET-type async function to access an API in the DAO. (This loads one item).    |
| daofoobatch  | Generates a DAO call by impelmenting Promise.all() and an idList param for batch requests  |
| mdaofoo      | Generates an modelizing DAO function to load some list.                                    |
| cd           | Generats a cloneDeep import of lodash                                                      |
| map          | Generats a map import of lodash                                                            |
| uniqarr      | Generats a Set with Array.from to create a unique array.                                   |
| uniqarrobj   | Generates a unique array with Set, Array.from() and .flat() that have object elements.     |
| for          | Generates a for loop with 'of'                                                             |
| forin        | Generates a for loop with 'in';                                                            |
| sfcnie       | Generates a simple function component without import and export in the file.               |
| pfcnie       | Generates a propless function component without import and export in the file.             |
| cfoo         | Generate an arrow function in react classes.                                               |
| per          | Generate two lines that passes the local error and loading states (from useState).         |
| \_n          | Generate new key-value pair in json files.                                                 |
| utrans       | Add a line of useTranslation and its {t} function import.                                  |
| t_1          | Add a line of t() function (type 1) [Object brackets {} and string key].                   |
| t_2          | Add a line of t() function (type 2) [No object {} brackets and variable as key].           |
| t_3          | Add a line of t() function (type 3) [Object brackets {} and variable as key].              |
| t_4          | Add a line of t() function (type 4) [No object {} brackets and string key].                |
| udm          | Generates a useDidMount custom hook from the xa-generics package.                          |
| udmev        | Generates a useDidMount custom hook with window event listener.                            |
| udwt         | Generates a useMountWithTriggers custom hook from the xa-generics package.                 |
| udtc         | Generates a useAfterTriggerChanged custom hook from the xa-generics package.               |
| ps           | Generates a quick prop interface element for a state setter.                               |
| pss          | Generates a quick prop interface element with setter included.                             |
| prop         | A key-value pair for prop interfaces.                                                      |
| strprop      | Generates a quick string prop with setter.                                                 |
| boolprop     | Generates a quick boolean prop with setter.                                                |

# Repository URLs

**HTTPS**

> https://github.com/Tom-xacademy/xa-snippets.git
