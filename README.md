
# Performance Testing

This project conduct the Performance of the api. 
How much time it took to deliver the responses to the client site from the server side.
## Clone the project

To clonning this project run on cmd

```console
$ git clone https://github.com/ismail-hoque-qa/Performance_Testing.git
```


## Documentation

https://reqres.in/


## Features

- Create Post
- Get Post
- Get specific Post by id


## Performance Testing Tools
This repository includes configuration and setup for the following performance testing tools: 

- **Apache JMeter** 

- **Postman** 


## Downloads Apache JMeter
https://jmeter.apache.org/

How To install
===============
Download
-> unzip 
-> bin 
-> jmeter.bat

Creating JMeter test 
=====================
Start JMeter
->Test plan creation
->Thread group
->Sampler (http)
->Listener
->Run

Add Listener
=============
View Results in Tree
->Aggregate report
->Graph results
->Simple data writer
## Run on Command Prompt for Generate Report

open cmd and execute the command

```console
 jmeter -n -t performance-test-50.jmx -l report\performance-test-50.jtl
```

Then execute command for report
```console
jmeter -g report\performance-test-50.jtl -o report\performance-test-50.html
```
    
    
## Performance Testing Report
![image](https://github.com/user-attachments/assets/fe1d595b-4417-44e3-ad70-dfa90af98ea1)
![image](https://github.com/user-attachments/assets/351910dc-314d-4981-baab-f67604ea40dc)

**Server can handle almost concurrent 25 API call with almost zero (0) error rate.**

![image](https://github.com/user-attachments/assets/bb12c51e-c5d1-4485-8abf-4c3780647fbb)

![image](https://github.com/user-attachments/assets/048d7752-c3fd-48cb-a407-ea2213aa20e6)
![image](https://github.com/user-attachments/assets/9eff6b13-12d9-469b-aea3-81a2be77ca6e)





