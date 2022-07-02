#**WEBFORMEXAMPLE**



##**Description**:

•	We have made a simple webpage using BOOTSTRAP

•	It has a form which has the following labels- “EMPLOYEE ID:”,”EMPLOYEE NAME:”,”EMAIL:”

•	As soon as the user enters the input fields and click saveEmployee() function executes

•	It will run validateAndGetFormData() which will return if the input fields don’t have values else it will create a jsonStrObj and return string form of it with the help of JSON.stringify(jsonStrObj) function.

•	If after validation we don’t get empty result, we will execute createPUTRequest("90939258|-31949286902929458|90939684", jsonStr, "SAMPLE", "EMP-REL") function which has token number, jsonStr, Database name and Relation fields.

•	Then we will execute executeCommandAtGivenBaseUrl(putReqStr, "http://api.login2explore.com:5577", "/api/iml") function that  will identify our base url to put the data on. Before and after this function async has been set as false and true so that the programming does not execute before implementing this function.

•	A resetForm() function is provided so that after saving the details our values gets removed from the input field and we can type new set of values.



##**Benefits**:

 •	It can be used by any software application that needs backend database.
 
 •	It has all RDBMS, DOCUMENT DB and KEY-VALUE DB use cases.
 
 •	It can be used for real time applications for data analytics.
 
 •	It can improve the analytics performance of the application.
 
 •	It minimizes the development cost, time to market and also the cost to ownership.



##**Released on**: 
 3/07/2022

