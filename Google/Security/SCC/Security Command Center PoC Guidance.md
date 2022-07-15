# [[Security Command -  PoC Guidance]]
```toc
```

## Introduction

This article provide guidances on how to perform a sucessful in the proof of concept (PoC) for Security Command Center Premium tier. 

Security Command Center is a Google Cloud's solution for centralized vulnerability and threat reporting service. It is helps to improve your security posture (CSPM - Cloud Security Posture Management) by evaluating your security and data attack surface; providing asset inventory and discovery; identifying misconfigurations, vulnerabilities, and threats; and helping you mitigate and remediate risks. For more details [Security Command Center conceptual overview](</br>https://cloud.google.com/security-command-center/docs/concepts-security-command-center-overview)


![[scc_escope.png]]

Define a plan process to determine the all tasks that must be accomplished in PoC process. Following a example of the timeline of the PoC process using a trial of the 30 days.



## Planning
This step clearly determine the main goals of PoC. To help you with that, we have outlined these general steps to a proof of concept process:

1. **Define the key stekeholders**:  You must have representatives from Security team, and team responsable for Cloud Workloads, in the generally the Cloud Infraestructure team.
2. **Define the Scope:** Defining the scope for your proof of concept is key to getting excelents results, questions like the below it is important:
		1. What the enviroments do you need to validate?
		2. Witch the features you will test?
		3.  
3. **Define Your Success Criteria:** To have accurate proof of concept feasibility measurements, you must have a set of metrics or success criteria. To define the success criteria for your POC process, you can start by interviewing the client, as it is their satisfaction that will determine if the proof of concept is a success.

**

# Potential Success Criteria

1.  Need a certain number of alerts set up based off of PCI DSS requirements
    

1.  Prioritize the most critical alerts 
    

3.  Threat detection enabled 2+ buckets 
    
4.  Test capturing suspicious traffic 
    

1.  Requires setting up a compute engine
    

6.  Vulnerability scan on Machine Imagines 
    

1.  Nice to have – see if this is feasible 
    

8.  SSH Bruteforce detection 
    

1.  Define specific test cases 
    

10.  Custom ETD alerts
    

1.  Specific threat detection – not everything 
    

12.  Create a detection rule specific to Fastly to alert on any untagged resources 
    
13.  Geoblocking / suspicious login / traffic alerts 
    
14.  Posture management 
    
15.  Stale buckets for GCP projects 
    

1.  This will be difficult 
    

17.  Asset management inventory 
    
18.  Discover misconfig vulns 
    
19.  Cloud security misconfigs 
    
20.  Container Security Evaluation – probably overkill for now 
    

1.  Maybe 2023
    



**
5. **Present the results**: After you past the all steps, you need to send a report of your PoC with the results


## Requeriments


## Validation

## Results
