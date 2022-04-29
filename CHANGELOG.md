### v2.13.0

-   Updated model generation with created_at and updated_at as they always exist anyway...
-   Updated dao generation by remowing the 'base' because the url always comes from the root dao
-   Change the dao methods request/response typings so they no longer import stuff from axios library and use its generics instead.

### v2.12.0

-   Renamed udmt to umwt and udat to uatc to better reflect the first letters of each word.
-   Added ps, pss, prop, strprop, and boolprop commands to populate prop interfaces quickly.
-   Removed the r17settings key

### v2.11.0

-   Added udm, udmev, udmt, udat snippets for the various custom hook usages.

### v2.10.3

-   Added json snippet \_nn to generate a comma, new line, and then key-value pair on next line.
-   Updated multiple function component exports to use simple export instead of export default.
-   Added new cursor positons to daofoofull and a few other snippets.

### v2.10.1 - v2.10.2

-   Removed 'export' before model MData interface because it's more of an internal type-safety measure anyway, though it can be used in useForms and such.

### v2.10.0

-   Removed export for the createContext line as they shouldn't be used anywhere. Use the 'useExampleContext' exported member instead.
-   Removed React import line from cc an ccr snippets, though I don't use those at all.
-   Changed the 'form' snippet snake case to camel case.
-   Removed extra line above 'sfc'
-   Added **sfcg** snippet, which generates a function component that takes a generic as its type parameter. Useful for multi-purpose, highly reusable components.
-   Added **sfcs** snippet, which generates a stateful function component (this includes a loading and error interface import and state, which is good for controller components.)

### v2.9.3

-   Just release-script related change, nothing to see here...

### v2.9.2

-   Fixed the useContext function comma bug at the EOL and changed it to arrow function
-   Changed the ContextXWrapper component default name to ContextXProvider (X is the context name)

### v2.9.1

-   Added a use[ContextName] method to the context generator snippet.
-   Removed the Context.Consumer usage under the providers since they can cause unnecessary re-renders in the children.

### v2.9.0

-   Added **t_1** and **t_2** snippets that generate a t() function with ILang interface passed to it.
-   Added **utrans** snippet that generates a line of useTranslation() destructuring to {t} function.

### v2.8.1 - 2.8.3

-   Fixed missing 'Model' word ending in model raw data inferring interface. (whoops?)
-   Fixed missing IDynamicObject import...
-   Updated **model** to generate a raw data interface which is inferred from the model values. (You can still use Omit<> on it if you want to exclude (for example) class methods...)

### v2.8.0

-   Added **daofoofull** snippet to generate four dao methods at once.
-   Fixed **daofoodelete** snippet by removing the leftover closing bracket '}' in the url behind 'id'.
-   Removed 'import React from "react" due to react 17 not needing it any longer.
-   Added a two json snippets, one for new key-value pair, and one for generating a whole react17 configuration. (You need ts version to be >=4.1.2).

### v2.7.0

-   Added new **ccfoo** snippet to generate an arrow function in react classes.
-   Added new **per** snippet to generate two lines that passes the local error and loading states (from useState).
-   Fixed description of **mstp**, **mdtp**, and **redux** snippets.

### v2.6.2

-   Fixed the **daofooget** promise return type not defaulting to array.
-   Changed the **usefnc** default function starting name from 'load' to 'init'. (It's used more often.)

### v2.6.1

-   Fixed the '\${id}' in daofoo methods not defaulting to 'id' string.

### v2.6.0

-   Added new **daofoopost** snippet for POST requests.
-   Added new **daofoopatch** snippet for PATCH requests.
-   Added new **daofoodelete** snippet for DELETE requests.
-   Added new **daofooget** snippet for GET requests.
-   Added new **daofoogetone** snippet for GET request that loads one item.
-   Added new **daofoobatch** snippet for requests implementing Promise.all() and an id list parameter.

### v2.5.6

-   Fixed number of cursors for ctx and ctxwc because 2,3, and 4 was basically '\${1}', just with some affix/suffix.
-   Added **sfcv** script which inherits every prop from the parent view (not from the controller like _sfhci_).
-   Removed unnecessary space in front of **iel** snippet.
-   Added missing 'export' in front of **tfoo** snippet.
-   Extended **usefnc** with the load section.
-   Fixed description of **daofoo** snippet.
-   Increment the last cursor count in the **model** which was incorrectly equal to the second.

### v2.5.4

-   Added documentation to uniquarrobj snippet.
-   Fixed **iel** script to do what was the original intention.
-   Fixed warning text in documentation to better explain/reflect my standpoint.
-   Removed _export default_ from **dao** script.

### v2.5.3

-   Fixed broken cursor position for 'uniqarr' snippet.

### v2.5.0

-   Added **sfcnie**, **pfcnie**, **pfc** component snippets.
