# Lab 5 : REST API spec file

Last week we created a github account. You should know how to clone, add, commit and push files to your own repositories. You were also introduced to a .yaml file, the specification file for defining a REST API.  This week we will create a swaggerhub account [swagger hub](https://app.swaggerhub.com/signup?channel=directWithinApp). A swaggerhub account provides a nice place to create our template for the yaml file/files that we will use the rest of the semester.

# Goal 

1) convert a yaml file it OAS2 to OAS3 from within swagger hub. 

2) Use the service from lab 4 with the updated .yaml file. (changes need to be made to server.py)

3) Create a python defintion that takes two arguments 

4) map the python function to a dynamic endpoint. 


# start

`make docker-all`

now remember in order to stop the service use `make docker-stop` in a seperate terminal. This should work seamless. 

Look in os_pack there are two files. Looks at them. Redfine the operationid in the yaml file to point to the cpu_2020.py file. Add you python defintion to this location.


