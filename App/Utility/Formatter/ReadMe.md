#Formatters
 ### Formatters are request data generators.
 They will act as single source to generate payload objects expected by API end points.
 
 #### Input
 Mostly data generated by presentation component. Container component will call them with data.
 
 #### Output
 Objects corresponding to data expected by API endpoint.
 
 #### Benifit
 We don't have to worry about modification of data while it travels from container-->sagas-->apiCaller
 
 Also the format expected by backend might change, which will result in unnecessary changes in Container component code and makes the whole data path ambiguous.  
