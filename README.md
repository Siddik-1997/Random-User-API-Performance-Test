# Random-User-API-Performance-Test

## What is Performance Testing:

 **Performance Testing is defined as a type of software testing to ensure that software applications will perform well under their expected workload.**
 - It focuses on certain factors of a Software Program such as: 
   - **Speed** – It Checks whether the response of the application is fast.
   - **Scalability** – It determines the maximum user load.
   - **Stability** – It checks if the application is stable under varying loads.

## Technology used: Apache JMeter

 **I used it for these characteristics:** 

  - **Open source application** – Apache JMeter is an openly available free tool & it facilitates users or developers to use the code for other development or modification purpose.
  - **Platform independent** – It can run on any platform & also it is capable enough to check the load & performance of any server requests.
  - **User friendly GUI** – Its user-friendly, simple & easy to understand.
  - **Installation** – It’s easy to install on different OS. 
  - **Record & Run**: JMeter provides the facility to record the steps by using Blaze master add-on & run with any number of threads & listeners.

## Server URL:

- I used this server for Performance Test.
- Link: https://random-data-api.com/api/v2/users

##  What I have done?
- I have done performance testing including **Load Testing** and **Stress Testing**.

- **Load Testing:** This testing is used to check the extreme load of a system that can be aimed to handle. 

  I started with 834 requests in 300 seconds and finally I executed with 4167 requests in 1500 seconds. I got the expected TPS (2.7) for every test iteration.
  
  ![Load Testing](https://user-images.githubusercontent.com/123433625/215355129-6ab79022-9784-468c-aeb7-18b08b559816.jpg)
    
- **Stress Test:**  This test tries to break the system by crushing its resources.

  I checked it in 25 minutes (1500 seconds) considreing 4167, 4500, 4700, 5000 requests. This server successfully run with these requests except 5000 requests in 1500 seconds. It shows an error 1% that is called as bottleneck point.
  
  ![Stress Testing](https://user-images.githubusercontent.com/123433625/215355113-c75f31f5-3afc-4807-8d4a-8c907ccab444.jpg)
 
## Report: 
 - Report file is available in this repository (resource folder).
 - Excel sheet has two tabs: one is for Load test and another one for Stress test. 

