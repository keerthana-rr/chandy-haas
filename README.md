*CHANDY-MISRA-HAAS DEADLOCK DETECTION ALGORITHM FOR AND MODEL*

***ASSIGNMENT (EC-1) - SSZG526***

***Submitted by Keerthana R. (2021mt13004)***


This java-based program helps to detect deadlock using the Chandy-Misra-Haas algorithm for the AND model.

**Assumptions**

    5 sites are considered for which the transaction wait-for(TWF) graph is given as input. Input is taken from file("inputFile.txt)"
    If site no. 2 initiates, the probe messages travel as
     S2 --> S1     (2,2,1)
     S1 --> S3     (2,1,3)
     S3 --> S2     (2,3,2)
     S2 --> S4     (2,2,4)
    and deadlock is detected on S3 --> S2 since the probe message returned to its initiating process


**Development Environment**

	• Windows 10 Operating System
	• IntelliJ IDEA community edition
	• Java JDK-13.0.2

**How to run**

• Open the src folder in any IDE of your choice

• Make changes to the inputFile.txt to construct transaction wait-for(TWF) graph.

• Open cmd in the src file path and run the following commands or run using the in-built compilers from your IDE

>javac ChandyMisraHaas.java

>java ChandyMisraHaas

