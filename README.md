# Single-Channel-Queue-Python

# Course Instractor:

SUBMITTED  BY _	 
Mohammad Abu Kowser Shakil  ( ID : CSE 01205959 )
Abdul Aziz ( ID : CSE 01206043 )
Tanvir Chowdhury ( ID : CSE 01406370 )
Md. Faisal Amin ( ID : CSE 01206014 )
Md. Shahriar Parvez ( ID : CSE 01406371 )
Md. Rayhan Uddin ( ID : CSE 01406366 )
S.M Alauddin  ( ID : CSE 01406367 )



Discrete and Continuous Random Variables:

 

A variable is a quantity whose value changes. 

 

A discrete variable is a variable whose value is obtained by counting.

 

Examples:     number of students present

                                    number of red marbles in a jar

                                    number of heads when flipping three coins

                                    students’ grade level

 

A continuous variable is a variable whose value is obtained by measuring.

 

Examples:     height of students in class

                        weight of students in class

                        time it takes to get to school

                        distance traveled between classes

 

A random variable is a variable whose value is a numerical outcome of a random phenomenon.

 

▪         A random variable is denoted with a capital letter

▪         The probability distribution of a random variable X tells what the possible values of X are and how probabilities are assigned to those values

▪         A random variable can be discrete or continuous



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
[Assignment 06.docx](https://github.com/shakil2510/Single-Channel-Queue-Python-Master/files/6177970/Assignment.06.docx)
