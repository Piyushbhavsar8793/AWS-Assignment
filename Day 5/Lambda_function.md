## LAMBDA function
> + If I made a java application ,if I kept it in the *EC2* then we have to run the *EC2* and have to pay for it.
 > + ***Lambda*** says that you can store the code and I will not pay for it when code will get run then only you have to pay for it.
 > +  But in *EC2* whether you run that code or not it will charge you. When u run code whatever CPU,RAM will require they will multiply it CPU ,RAM TIME And will charge you according to that *scalability* and *parallization.*

***Scalability:*** means if write 1 program that requires 1 gb,1 core -30 sec , If update it that require 2 gb,1 core -10 sec Automatically lambda will calculate it and provide it.\
***Parallelization:*** If I have code which is capable to take code from 10 people When lambda execute ,on each execution If it have 1 million execution request Then it will execute the same lambda 1 million times