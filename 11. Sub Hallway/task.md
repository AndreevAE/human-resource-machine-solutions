
# Sub Hallway

## Task

For each two things in the `INBOX`, first subtract the 1st from the 2nd and put the result in the `OUTBOX`. **AND THEN**, subtract the 2nd from the 1st and put the result in the `OUTBOX`. Repeat.

You got a new command! `SUB`tracts the contents of a tile on the floor **FROM** whatever value you're currently holding.

## Example

INBOX:  
`2` `5` `6` `4` `-6` `-6` `3` `-1`

OUTBOX:  
`3` `-3` `-2` `2` `0` `0` `-4` `4`

## Optimizaiton Challenges

**Size Challenge:** 10  
Measures the number of commands in your program. Fewer is better.

**Speed Challenge:** 40  
Measures the number of commands your program must execute before it finishes, on average. Fewer is better. (Average computed by testing your solution against many deterministically generated input sets.)
