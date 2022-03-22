
# Scavenger Chain

## Task

Each pair on the floor contains:
1. data
2. the address of another one
of the pairs

A scrambled chain! Each thing in the `INBOX` is an address of one of the pairs. `OUTBOX` the data for that pair, and also the data in all following pairs in the chain. The chain ends when you reach a negative address. Repeat until the `INBOX` is empty.

## Example

INBOX:  
`3`

OUTBOX:  
`C` `A` `P` `E`

## Optimizaiton Challenges

**Size Challenge:** 8  
Measures the number of commands in your program. Fewer is better.

**Speed Challenge:** 63  
Measures the number of commands your program must execute before it finishes, on average. Fewer is better. (Average computed by testing your solution against many deterministically generated input sets.)
