# HoneyPot
Attempt at making a container-like honeypot (running in kubernetes)

## Introduction
### Background
Honeypots are are a type of technology that can be used for detecting and analyzing attacks (both on systems and networks).  
A honeypot is designed to simulate a system or network resource which has been misconfigured/left due to either negligence or ignorance.  

### Note
A honeypot **does not improve security** of the **actual** system or network.  
It is merely used to gain insight into the types of attacks that are being attempted in or on the system/network.  

### Risk Analysis and security considerations
Risk analysis based on probablity (P) and impact (I) of misconfiguration of this project:
**Risk = P * I** where P and I are values between 0 and 5.  
|N°|Risk|Probability|Impact|**Risk**|Mitigation|
|:-:|:--|:---------:|:----:|:--:|---------:|
|1  |Container Escape|3|5|**15**|Closely monitor the containers, monitoring container behavior|
|2  |Network Breach|2|5|**10**|Run the testing environment in isolated network environment|
> Work in progress

## Outline
I'm not entirely sure how to structure this project yet, but for now it will follow this structure:  
1. Introduction (Short intro, background, risk analysis, goal, Success criteria ...) 
2. Overview of the project (Network and System topology, tools, security measures, considerations, ...)
3. In-depth explanation of the project (Specific installation procedures, resources, logging, ...)
4. Testing and validation (How to test the honeypot, what to look for, ...)
5. Logs and results (Log analysis, statistical results, geographical comparisons, ... )
6. Summary + reflection