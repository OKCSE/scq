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

# Single-Channel-Queue-System

# What is Discrete Variable?

**Discrete variables** are countable in a finite amount of time. For example, we can count the change in our pocket. we can count the money in your bank account. we could also count the amount of money in everyone’s bank accounts. It might take us a long time to count that last item, but it’s still countable.

![Discrete Variable on a Scatter Plot](https://www.statisticshowto.com/wp-content/uploads/2013/09/scatter-plot-2.jpg)

*Fig: Discrete Variable on a Scatter Plot*

# What is Continuous Variable #

* Continuous Variables would take forever to count. In fact, you would get to “forever” and never finish counting them. For example, take age. You can’t count “age”. Why not? Because it would literally take forever. For example, you could be:
25 years, 10 months, 2 days, 5 hours, 4 seconds, 4 milliseconds, 8 nanoseconds, 99 picosends and so on.
* Time is a continuous variable. Anyone's age can be turned into a discrete variable and then you could count it. For example:
A person’s age in years.
A baby’s age in months.

# What is Probability Distribution #

A probability distribution is a function that describes the likelihood of obtaining the possible values that a random variable can assume. In other words, the values of the variable vary based on the underlying probability distribution. Poisson Distribution and Exponential Distribution are among the other types of probability distribuiton.

# What is a Single Channel Queuing System #

A single-channel service system consisting of a service facility and queue, in which the possible times of arrival of units and the possible service times are discrete, is analyzed. A method of calculating the moments of the total service time of units in the system is developed. This total service time is related to the delay caused by the system. When arrivals at different times are assumed to be independent, the “values” of the resulting Markov process can be calculated. These values lead to information about the transient behavior, autocorrelation function, expected first passage time, and expected extra delay that arises if another unit is inserted into the system. An expression for the geometric transform or moment generating function of the probability distribution of the total service time of units in the system is determined. The results are derived for arbitrary arrival and service time distributions.

# Brief Introduction to Poisson Distribution and why it used #

A Poisson distribution is a tool that helps to predict the probability of certain events from happening when you know how often the event has occurred. It gives us the probability of a given number of events happening in a fixed interval of time.

![Poisson Distribution](https://user-images.githubusercontent.com/34852930/113517414-9eb70580-95a1-11eb-85b2-4a6b75ad5bc6.png)

Poisson distributions, valid only for integers on the horizontal axis. λ (also written as μ) is the expected number of event occurrences.
If we want to calculate the poisson Distribution 

pmf is: P(x; μ) = (e-μ * μx) / x!

Where:
•	The symbol “!” is a factorial.
•	μ (the expected number of occurrences) is sometimes written as λ. Sometimes called the event rate or rate parameter.

In general, Poison distribution works with a discrete value. As we know inter-arrival time does not occur in sequential manner, it works randomly. Thus poisson distribution are used for that.


# Brief Introduction to Exponential Distribution and why it used #

The exponential distribution is often concerned with the amount of time until some specific event occurs. For example, the amount of time (beginning now) until an earthquake occurs has an exponential distribution. Other examples include the length, in minutes, of long distance business telephone calls, and the amount of time, in months, a car battery lasts. It can be shown, too, that the value of the change that you have in your pocket or purse approximately follows an exponential distribution.

Exponential Distribution deals with the time between occurrences of successive events as we know time flows continuously and in this project the starting and  the ending of service can be considered as two successive events.

# The problem and why we are solving it #
Our problem is to simulate a bank problem having µ=5.6 customers/minute (arrival rate) and λ=5 customers/minute (service rate) for 20 customers. We used exactly 19 to 20 random variates for generating the random variables(two). We didn’t consider after precision values of decimal point for service times during simulation for the convenience. We used subroutine, objects and built-in function in python programming language. 

In this project, we have used simulation to analyze the queueing system. There are advantages of a simulation model: A simulation model can be used to investigate a wide verity of “what-if” questions about the real-world system. Actually, we have solved single channel queuing problem. 

It is important to create a simulation of a real-world system before implement it physically. For this we can find out any problem that would be face in future. A simulation helps to understand overall working principle of the system. We have also solved this bank simulation system to find out some specific tasks, 1. Average waiting time of a customers, 2. Average time spend in the system, 3. Probability of a server being idle, 4. Average interarrival time 

