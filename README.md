# Python

Python is a high level interpreted language used for writing scripts, wrangling data, making machine learning models and much more. It's dynamically typed(It checks varibales during runtime and it doesn't force you to declare the type of your variable) and garbage collected. Python emphaises code readability.

# Data Structures
Data structres and algorithms combine together to form programs. Data structures in particular help us with organizing our data such that it is easy to compute. Dta structures can be braodly divided into:

- Arrays
- Hash Tables
- Linked Lists
- Stacks & Queues
- Trees
- Graphs

Before one tries to implement these data structures it is neccessary to understand the difference between a good & a bad program. How do we know that?

## BigO
Suppose you own a car. You are then interested in finding the mileage it gives in different situations. Say it gives a mileage of 12km/ltr in traffic, 26km/ltr in normal city conditions and 20kn/ltr on the highway.
Considering these three factors, the highway seems to be the best case for your car and pocket, normal city conditions seem to be moderate and traffic seems to be the worst. 
This is similar to the logic we use in finding out whether our program is in its best or worst form. In computational terms we would refer to it as the notations used for runtime analysis of algorithms. Theta notation gives you the best case complexity(highway), Theta gives you average case complexity (normal city) and Omega gives you worst case complexity.
We will, for most part of writing programs focus on the worst case scenarios for our programs.

Now, BigO notations can be represented in several ways. Here's an image from [BigO CheatSheet](bigocheatsheet.com) to put things into perspective.
[BigO CheatSheet](url).

We see that the complexities are as follows ranging from best to worst :
O(1) > O(n) > O(n log n) > O(n^2) > O(2^n) > O(n!).

Let's write that again .
- O(1)
- O(n)
- O(n log n)
- O(n^2)
- O(2^n)
- O(n!)
