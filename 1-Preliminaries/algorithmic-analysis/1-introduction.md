# Introduction to Algorithmic Analysis

Topics Covered:

- Introduction: What is an algorithm?
- Abstract Data Types (ADTs)



What is an **Algorithm**? It is a finite, deterministic, effective set of instructions to complete a specific task as a computer program. It is one of the principle studies of computer science, and our topic of discussion. Generally, algorithmic thinking isn't isolated to computer programs. They can be instructional by nature, mathematical even. But for our purpose they will be computer programs. Most algorithms require the organization of data in specific ways. Therefore, **data structures** are the byproduct of algorithms. 

The algorithms we'll discuss help us solve many problems. Some of these problems are small in nature, requiring a few steps. Which algorithms and data structures we use won't be of importance, regardless of the algorithm, the execution will be quick. But further insight is needed in solving larger problems, and the algorithms we select will have an impact on whether we can accomplish the task efficiently, or even complete the task at all.   

This is the first time we've referenced the idea of efficiency, in some sense that is what we care about with our use of computational devices. Speed - how fast or how long a certain task takes. This will be our next discussion.


-------

**Asymptotic analysis** attempts to estimate the resource consumption of an algorithm.

The goal of algorithmic analysis is to provide us with an estimation on the performance of two algorithms. How can we can we compare whether two potential solutions will perform? Which of the two algorithms will require more resources to complete the task?

While we can program the two algorithms, have them run on similar inputs and observe which of the two solutions finish first, this is a suboptimal way to compare algorithms. For many reasons. 

A better way is to use asymptotic analysis to measure the efficiency of an algorithm, as the input becomes large. The resource that we are considering is time. The run time of the algorithm is often our concern, but the associated space require for the data structure cannot be ignored. Therefore, consideration of run time for the algorithm and the associated space for the data strucutre need to be analyzed. 

Now, we will consider how to calculate the run time, and we can accomplish this by the counting the number of **basic operations** needed to process the input of a certain **size**. 

**Size** is the number of items to be processed. If we are iterating through a list containing ***n***, IP addresses, then the size would be ***n*** - the number of IP addresses processed.

**Basic operations** are tasks that do not depend on the size of the input. To add two variables and produce their sum - would be an example. The requirement is that the time to complete the task does not depend on the size of the input. 

The **growth rate** of an algorithm is the rate at which the cost of the algorithms grows as the size of the input grows. 
