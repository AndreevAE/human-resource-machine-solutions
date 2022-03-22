
# Countdown

## Task

For each number in the `INBOX`, send that number to the `OUTBOX`, followed by all numbers down to (or up to) zero. It's a countdown!

You got new commands! They add **ONE** or subtract **ONE** from an item on the floor. The result is given back to you, and for your convenience, also written right back to the floor. `BUMP`!

## Example

INBOX:  
`3` `-3` `0`

OUTBOX:  
`3` `2` `1` `0` `-3` `-2` `-1` `0` `0`

## Optimizaiton Challenges

**Size Challenge:** 10  
Measures the number of commands in your program. Fewer is better.

**Speed Challenge:** 82  
Measures the number of commands your program must execute before it finishes, on average. Fewer is better. (Average computed by testing your solution against many deterministically generated input sets.)
