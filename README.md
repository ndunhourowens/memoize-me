We are going to be building an in-memory cache to improve performance and extend the getElementById() and querySelector() functions of the DOM. Querying the DOM for elements can be an inefficient operation and if we are finding elements in the DOM repeatedly we would like to improve performance but we also don't want to clutter our codebase with many variables to hold references to the various elements we will use and to keep things a bit more dynamic.


