# Curiosity
A game of Nomic.
## Current rules
### Basics
`2.` Players submit rule proposals by posting final drafts in the ⁠#curiosity-voting channel.

`5.` For a poll that changes the ruleset to pass, the total weight of 'yes' votes must be greater than the sum of the total weight of 'no' votes plus the Cohesion Score at the time the poll concludes: Total 'yes' weight > (Total 'no' weight + Cohesion Score).

`6.` To create a valid poll, only the bracketed section of the following command may be edited before posting:
`/timepoll question:` [Proposal full text] `time: 48 hours answer-1: Yes answer-2: No answer-3: Abstain answer-4: Yes weight 2 answer-5: No weight 2`  

`19.` The Cohesion Score is a value with a minimum of 0.  

`20.` Each day at 00:00 UTC, the Cohesion Score decreases by 1.   

`21.` Whenever a poll that changes the ruleset passes, the Cohesion Score increases by 1.5 .

`22.` The cost to cast a vote of weight n is n^2 credits (e.g., 1 credit = weight 1; 4 credits = weight 2).  

`23.` Abstaining costs 0 credits.  

`24.` Players are limited to a maximum balance of 5 credits.  

`25.` Credits are calculated at the conclusion of a poll:  
  a. Every participant first receives 2 credits.  
  b. Credits for the selected weight are then subtracted from their balance.   
  c. If a player has an insufficient number of credits for their chosen weight, a lower weight is automatically selected.  

### Awards

`9.` The Elegance Award recognizes players whose rule proposals streamline the game for newcomers while maintaining or refining core mechanics.  

`11.` each new player starts with 10 Experience Awards. Existing players also have 10 Experience Awards effective at the enactment of this rule. Returning players are  given 10 Experience Awards at their first ever return, but not for subsequent returns. 

A new player role, the Awarder, is created. The role consists in counting Awards and transfer them in between players.

`12.` Players may record major rewards in their profile.  

`13.` A reward may be proposed alongside any rule change.  

`14.` Every three months, a Nomic Comedy Award shall be granted to the author of the most humorous contribution. 

`15.` Players earn one dopamine, one serotonin, one oxytocin and one endorphin for every minor improvement.  

`16.` The quarterly Insight Award recognizes a player whose gameplay inadvertently demonstrates a new, practical, real-world concept to the voting player.  

`17.` The Counteragent Star may be awarded by vote to any player who identifies a systemic vulnerability and enacts rules to mitigate it.

`18.` A player can become the Awarder by proposal. If the player specified to become the Awarder votes against on said proposal, the proposal automatically fails. 

### Subgames
`30.` There is a 32x32 grid of ASCII characters maintained by the Artist, a new player role.  

`31.` A player can spend a serotonin to change any location on the grid to any character.

### Details 1
`101.` Any poll displaying "Edited" next to the Poll ID is rejected.   

`102.` Edited proposals are rejected.

`103.` Rules should be short.  

`104.` The rules should always, by player action, be able to be changed in part.  

`105.` Game play continues after a win.  

`106.` There are 3 text channels for this game: one for general chat and proposal discussion, the second where all proposals are written to vote on them, and a third one solely for currently active rules, copied exactly as written in the proposals.  

`107.` To create a valid poll by reference, an unambiguous reference to the immediately preceding message block must be provided, specifying the number of rule changes therein. Only the bracketed section of the following command may be edited before posting:
`/timepoll question:` ["The X rule change(s) immediately above"] `time: 48 hours answer-1: Yes answer-2: No answer-3: Abstain answer-4: Yes weight 2 answer-5: No weight 2`  

### Details 2
## Rules administration
These rules are also at [github.com/cieok/curiosity](<https://github.com/cieok/curiosity>). Pull requests are very welcome and entirely optional.    

Change log is at [github.com/cieok/curiosity/commits/main](<https://github.com/cieok/curiosity/commits/main/>)

Last change is at [github.com/cieok/curiosity/commit/main](<https://github.com/cieok/curiosity/commit/main>)
