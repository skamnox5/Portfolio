![[HammyCover.png |400]]
Project Link - [Itch.io](https://hammylimitedco.itch.io/moons-over-my-hammy)

## Description

In this game you inherit your grandpa's diner but also his debt and need to bring the diner back from disrepair and climb out of debt.

The game features elements of time management with moving around the kitchen and cooking the food before customers get angry and leave. 

It also has decisions that the player can make with the various upgrades the player can purchase that can either make the experience of cooking easier or add options to the menu giving the player the ability to make more money but also increasing the challenge of the game.
## My Role

I designed and implemented the systems relating to the core game loop of cooking and the systems that interact with that such as the upgrades system and its accompanying UI elements.


# Reflection
## Systems Design

### Re scoping
The cooking system for this project initially was planned to be much more complicated but due to time constraints for this project, we realized we had scoped too large with the initial system.

It was going to be more dynamic with each cooking station being able to take in any ingredient and based off of which ingredient combination, it would cook a corresponding food item or prepare that ingredient to be used at a different station for a final dish. 

But since we had to cut back on the amount of ingredients in the game and to automatically provide the ingredients for the player rather than having to obtain the ingredients by foraging or hunting.

We decided to make each of the cooking stations we had at that point be used to cook a specific dish each and we would only have 3 main dishes with unique ingredients per dish with a couple of overlapping ingredients for some.

### Finding the new gameplay loop

This decision did leave a hole in the loop since it was much more simpler now as all ingredients were provided so we tried thinking about how we could make the game engaging.

So we made time management a bit more of the focus in the moment to moment loop, where your ability to get the ingredients and cook them requires you to move efficiently.

The way this was achieved was by making some of the foods that can be made, lock the player down while making the dish while some being a timer that is set. 

This added a little bit of decision making for the player since they would have to balance which foods to focus on first since they could do the foods that have timers first and in the time for that food to finish cooking the can do the other orders.

### Reinforcing the loop

Another way this was addressed that I feel added a lot to the gameplay loop and was a pretty late addition as well was the printing timer on the food printer. The setting allowed us to use a Food Printer which could explain why food can just appear in the hands of the player out of thin air but toward the end of development we felt like there was something missing for making the game more engaging.

So I worked on a timer system for the printer, making it to where each time you want an ingredient you have to wait. This made it to where players would have to try and plan ahead and stock up on certain ingredients so they were prepared to make food as fast as possible.

Then I iterated on this with an upgrade system in two ways. One was storage for ingredients, in the kitchen there are trays that the player can place ingredients and food onto as temporary holding. I made it to where the player can increase the amount of slots they have so they can print food before customers show up and can prep more food giving the player more agency in the beginning.

The second way I iterated on this was with a printer queue, I added an array of items that will be printed and the capacity of the array starts off with 1 but can be upgraded to a max of 4. This printer queue added a lot to the moment to moment gameplay since the player is pushed to take advantage of this and constantly have something in the queue to make sure they have all ingredients they might need.

Ultimately this all contributed to gameplay that, especially in the later levels when the difficulty ramps up, gives the player something they can be doing at any given moment keeping things fast paced and engaging. The upgrade system also gave players some sense of progression that felt impactful to the moment to moment gameplay loop.

## Looking Back

Looking back on this project I think it came out pretty fun even though it was a bit worrying at times. One of the big things that I took from this experience is to be much more careful with scope as this game came out our group just brainstorming a bunch of ideas without much concern for if we could realistically implement these things and us not rapidly prototyping in the beginning to accurately determine how much of this project was feasible. This lack of testing in the beginning is what lead to a major pivot about halfway through the project timeline.