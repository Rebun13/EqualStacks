# EqualStacks

## Description

You have three stacks of cylinders where each cylinder has the same diameter, but they may vary in height. You can change the height of a stack by removing and discarding its topmost cylinder any number of times.

Find the maximum possible height of the stacks such that all of the stacks are exactly the same height. This means you must remove zero or more cylinders from the top of zero or more of the three stacks until they are all the same height, then return the height. 

## Returns

- int: the height of the stacks when they are equalized

## Input

- The first line contains three space-separated integers _n1_, _n2_ and _n3_, the numbers of cylinders in stacks _1_, _2_, and _3_. The subsequent lines describe the respective heights of each cylinder in a stack from top to bottom:

- The second line contains _n1_ space-separated integers, the cylinder heights in stack _1_. The first element is the top cylinder of the stack.
- The third line contains _n2_ space-separated integers, the cylinder heights in stack _2_. The first element is the top cylinder of the stack.
- The fourth line contains _n3_ space-separated integers, the cylinder heights in stack _3_. The first element is the top cylinder of the stack. 
