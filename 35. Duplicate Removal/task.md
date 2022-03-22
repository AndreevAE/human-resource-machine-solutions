
# Duplicaate Removal

## Task

Send everything from the `INBOX` to the `OUTBOX`, unless you've seen the same value before. Discard any duplicates.

## Example

INBOX:  
`C` `E` `D` `B` `A` `E` `C` `D` `E` `B`

OUTBOX:  
`C` `E` `D` `B` `A`

## Optimizaiton Challenges

**Size Challenge:** 17  
Measures the number of commands in your program. Fewer is better.

**Speed Challenge:** 167  
Measures the number of commands your program must execute before it finishes, on average. Fewer is better. (Average computed by testing your solution against many deterministically generated input sets.)
