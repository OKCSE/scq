#  Single Channel Queuing System (Assignment 6)
#  Simulation & Modeling Sessional

##  Group 3 
                       
   1.[ Md Woise Uddin Akbar (CSE-01105875)](https://github.com/OKCSE/)  [Team Leader]
   
   2.[ Hasib Abdullah (CSE-01406316)](https://github.com/hasibctg/)
   
   3.[ Raghib Shahriar (CSE - 01206008)](https://github.com/Raghib6/)
   
   4.[ Joseph Dias (CSE-01406362)](https://github.com/Joseph440G0/)
   
   5.[ Mohammad Azad  (CSE - 01406365)](https://github.com/jrazad10/)

## Course Instructor:
   
   [Mr. Muhtadir Rahman](https://github.com/muhtadir)
   
   Lecturer, Department of CSE
   
   Port City International University

# Single-Channel-Queue-System #

# What is Discrete Variable
Discrete variables are countable in a finite amount of time. For example, While buying any specific amount of stuff we can quickly count whether the the amount is correct.

# What is Continuous Variable
Continuous Variables might take us forever to count. In fact, we would get to “forever” and never finish counting them. For example, we can’t count how much money a person would earn in total amount in his whole career, because we don’t know exactly when the person will die and stop earning.
Time is a continuous variable. Anyone earning money can be turned into a discrete variable and then you could count it. For example: A person’s earning in years or in months.

# What is Probability Distribution
A probability distribution is a function that tells us the prospect of getting the possible values that a random variable can take. In other words, the values of the variable change based on the underlying probability distribution. Poisson Distribution and Exponential Distribution are among the other types of probability distribution.

# What is single channel queuing system
A single channel service system is actually a service facility using queue. In which the possible times of arrival of any entity and the possible service times are discrete and analyzed. A method of estimating the moments of the total service time of units in the system is developed. This total service time is related to the delay caused by the system. When arrivals at different times are assumed to be independent, the values of the resulting process can be calculated. These values lead to information about the transient behavior, autocorrelation function, expected first passage time, and expected extra delay that arises if another unit is inserted into the system. distribution of the total service time of units in the system is fixed. The values obtained for random arrival and service time distributions.

Brief introduction on Poisson Distribution and why it is used
A Poisson distribution is a tool that helps to predict the probability of a specific events from happening and often the number of event has occurred will be known. It gives us the probability of a given number of events happening in a fixed interval of time.

Poisson distributions, valid only for integers on the horizontal axis. λ (also written as μ) is the expected number of event occurrences.
In general, Poison distribution works with a discrete value. As we know inter-arrival time does not occur in sequential manner, it works randomly. Thus poisson distribution are used for that.


# Brief introduction on Exponential Distribution and why it is used 
The exponential distribution is often concerned with the amount of time until some specific event occurs. For example, the amount of time until a big occurence and it has an exponential distribution. Other examples include the length, in minutes of a tournament match, and the amount of time, in months, a phone lasts. A particular object roughly follows an exponential distribution can be depicted as well.

We know that exponential distribution deals with the time between incidents of successive events as we know time is continuous and in this project the starting and  the ending of service can be considered as two successive events.

# The problem and why we are solving it #
Our problem is to simulate a bank problem having µ=5.6 customers/minute (arrival rate) and λ=5 customers/minute (service rate) for 20 customers. We used exactly 19 to 20 random variates for generating the random variables(two). We didn’t consider after precision values of decimal point for service times during simulation for the convenience. We used subroutine, objects and built-in function in python programming language. 

In this project, we have used simulation to analyze the queueing system. There are advantages of a simulation model: A simulation model can be used to investigate a wide verity of “what-if” questions about the real-world system. Actually, we have solved single channel queuing problem. 

It is important to create a simulation of a real-world system before implement it physically. For this we can find out any problem that would be face in future. A simulation helps to understand overall working principle of the system. We have also solved this bank simulation system to find out some specific tasks, 1. Average waiting time of a customers, 2. Average time spend in the system, 3. Probability of a server being idle, 4. Average interarrival time 

