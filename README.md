# Single-Channel-Queue-Python

# Group: 6
# Submitted By:

1. Mohammad Abu Kowser Shakil  ( ID : CSE 01205959 )
2. Abdul Aziz ( ID : CSE 01206043 )
3. Tanvir Chowdhury ( ID : CSE 01406370 )
4. Md. Faisal Amin ( ID : CSE 01206014 )
5. Md. Shahriar Parvez ( ID : CSE 01406371 )
6. Md. Rayhan Uddin ( ID : CSE 01406366 )
7. S.M Alauddin  ( ID : CSE 01406367 )



# Discrete Random Variables:
A variable is a quantity whose value changes. 
A discrete variable is a variable whose value is obtained by counting.
   Examples:     
       number of students present
       number of position hexacone
       students’ grade level


# Continuous Random Variables:
A continuous variable is a variable whose value is obtained by measuring.
   Examples:     
        height of students in class   
        weight of students in class
        time it takes to get to school
        number of vehicle cross in a road
                        
                        


# Poisson Distribution

What Is a Poisson Distribution?
In statistics, a Poisson distribution is a probability distribution that can be used to show how many times an event is likely to occur within a specified period of time﻿. In other words, it is a count distribution. Poisson distributions are often used to understand independent events that occur at a constant rate within a given interval of time. It was named after French mathematician Siméon Denis Poisson.

The Poisson distribution is a discrete function, meaning that the variable can only take specific values in a (potentially infinite) list. Put differently, the variable cannot take all values in any continuous range. For the Poisson distribution (a discrete distribution), the variable can only take the values 0, 1, 2, 3, etc., with no fractions or decimals.


The Formula for the Poisson Distribution Is:
![poisson-56a8fa9e3df78cf772a26eb0](https://user-images.githubusercontent.com/42375657/114293352-2c6d8600-9ab7-11eb-9f41-f6b67bb29a06.jpg)



# The single channel queuing model can be fitted in situations where the following seven conditions are fulfilled:

1. The number of arrivals per unit of time is described by poisson distribution. The mean arrival rate is denoted by λ.
2. The service time has exponential distribution. The average service rate is denoted by μ.
3. Arrivals are from infinite population.
4. The queue discipline is FIFO, that is, the customers are served on a first come first serve basis.
5. There is only a single service station.
6. The mean arrival rate is less than the mean service rate i.e. λ < μ.
7. The waiting space available for customers in the queue is infinite.




## Problem Statement
Now, simulate this bank problem having µ=5.6 customers/minute (arrival rate) and λ=5 customers/minute (service rate) for 20 customers. You should use exactly 19 to 20 random variates for generating the random variables(two). You don’t need to consider after precision values of decimal point for service times during simulation for the convenience. You can use any subroutine, object, or any built-in function of any relevant programming language. The average number of customer waiting, the average waiting time of a customer should be your statistical estimators for examining the true characteristics of the system.

[ Note: here I used 'POISSON DISTRIBUTION' for Inter Arrival Time generation & I used 'EXPONENTIAL DISTRIBUTION' for service time generation ]
[Assignment.docx](https://github.com/shakil2510/Single-Channel-Queue-Python-Master/files/6177970/Assignment.docx)
