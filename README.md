# Closures Lab

## Objectives

- Use closures to customize functions
- Use closures as a mechanism of encapsulations

## Instructions

In the lab that follows, practice using closures to construct functions that have reference to variables that the execution scope does not.

Create the following functions:

- `produceDrivingRange()` - Calculates whether a
  given trip is within range.  For example, `produceDrivingRange(10)` returns a
  function that will take two strings as arguments and returns a message stating
  whether the trip is in range. If `foo = produceDrivingRange(10)`, then
  `foo('12th', '15th')` would return `"within range by 7"` and `foo('12th',
  '30th')` would return `"8 blocks out of range"`. We recommend referencing the
  `test/indexTest.js` for more details.

- `produceTipCalculator()` - Returns a function that then calculates a tip. For
  example, `produceTipCalculator(.10)` returns a function that calculates ten
  percent tip on a fare. `produceTipCalculator(.20)` returns a function that
  calculates twenty percent tip on a fare.

- `createDriver` is a function that returns a `Driver` class. The class has
  reference to a `driverId` that is incremented each time a new driver is created.
  The rest of the code base does not have access to `driverId`.

The functions should make use of closures to achieve the specified goals.

<p class='util--hide'>View <a href='https://learn.co/lessons/js-advanced-scope-closures-lab' title='Advanced Scope Closures Lab'>Advanced Scope Closures Lab</a> on Learn.co and start learning to code for free.</p>
