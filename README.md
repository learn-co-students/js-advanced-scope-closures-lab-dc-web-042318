# Closures Lab

## Objectives
+ Use closures to customize functions
+ Use closures as a mechanism of encapsulations

## Instructions

In the lab that follows, practice using closures to construct functions that have reference to variables that the execution scope does not.  

Create the following functions:

  + produceDrivingRange() - Returns a function that then calculates whether blocks are for a specific range.  For example, `produceDrivingRange(10)` returns a function that we can then pass a starting and ending block to.  If the starting anding blocks are further than 10 blocks away, our returned function will tell us.   
  + produceTipCalculator() - Returns a function that then calculates a tip.  For example, `produceTipCalculator(.10)` returns a function that calculates ten percent tip on a fare.  `produceTipCalculator(.20)` returns a function that calculates twenty percent tip on a fare.
  + `createDriver` returns a function that returns a class that produces a Driver class.  The class has reference to a driverId that is incremented each time a new driver is created.  The rest of the code base does not have access to driverId.  

The functions should make use of closures to achieve the specified goals.

<p class='util--hide'>View <a href='https://learn.co/lessons/js-advanced-scope-closures-lab' title='Advanced Scope Closures Lab'>Advanced Scope Closures Lab</a> on Learn.co and start learning to code for free.</p>
