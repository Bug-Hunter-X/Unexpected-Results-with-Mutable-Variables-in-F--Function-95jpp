# F# Mutable Variable Bug

This repository demonstrates a potential confusion with mutable variables in F# functions.  The `add` function unexpectedly modifies its input variables and produces results different than what one might initially expect.

## Bug Description
The provided F# code uses mutable variables within a function. The unexpected behavior arises from the way the mutable variables are updated within the function and how this impacts the overall function's return value. 

## How to Reproduce
1. Clone this repository.
2. Open `bug.fs` in a F# environment (e.g., Visual Studio, .NET Interactive).
3. Run the code. Observe that the result is not the sum of the initial values of x and y but rather a more complex result due to the mutable updates.

## Solution
The `bugSolution.fs` demonstrates a corrected approach to achieve the intended addition behavior, demonstrating improved clarity and predictability.