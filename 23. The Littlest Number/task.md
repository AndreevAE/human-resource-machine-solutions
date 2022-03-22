
# The Littlest Number

## Task

For each zero terminated string in the `INBOX`, send to the `OUTBOX` only the **SMALLEST** number you've seen in that string. You will never be given an empty string. Reset and repeat for each string.

What's a "zero terminated string"? Go ask your boss on the previous floor!

## Example

INBOX:  
`3` `13` `2` `0` `11` `12` `7` `1` `0` `27` `32` `27` `86`

OUTBOX:  
`2` `1` `27`

## Optimizaiton Challenges

**Size Challenge:** 13  
Measures the number of commands in your program. Fewer is better.

**Speed Challenge:** 75  
Measures the number of commands your program must execute before it finishes, on average. Fewer is better. (Average computed by testing your solution against many deterministically generated input sets.)
