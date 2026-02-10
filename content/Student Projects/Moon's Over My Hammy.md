---
tags:
  - Game_Designer
  - Programmer
  - Systems_Designer
  - Shipped
---


<Carousel>
<img src="https://www.youtube.com/watch?v=m1HcnOsnbc4" alt="MOMH Trailer"/>
<img src="MOMH_01.jpg" alt="Screenshot 1"/>
<img src="MOMH_02.jpg" alt="Screenshot 2"/>
<img src="MOMH_03.jpg" alt="Screenshot 3"/>
<img src="MOMH_04.jpg" alt="Screenshot 4"/>
<img src="MOMH_05.jpg" alt="Screenshot 5"/>
<img src="MOMH_06.jpg" alt="Screenshot 6"/>
</Carousel>

University Capstone Project

Project Link - [Itch.io](https://hammylimitedco.itch.io/moons-over-my-hammy)

# Details
- **Genre:** Arcade Cooking Sim 
- **Type:** Full Game
- **Software:** UE5
- **Duration:** 8 Months
- **Iteration#:** 5
- **Playtest#:** 5
- **Role:** Systems Designer

# Goal

The goal of this game was to give the players the feeling of playing a chef in a fast paced diner with a futuristic/space themed world.

This was done with 3 key points in the game
- **Pacing:** With a short length of days and frequency of customers, the player feels a sense of overwhelming work as a busy diner worker would have.
- **Aesthetic:** The aesthetic of the level, stations and NPCs have a good blend of an everyday diner with elements of futurism.
- **Mechanics:** The various game systems of printing and upgrading add to the chaotic balance of running a diner.
# Systems Designer

My responsibility for this project was to develop the underlying systems for the cooking and diner upgrade mechanics using UE5 Blueprints.

The main systems I was responsible for were
- **Cooking** Dishes
- **Printing** food Ingredients
- Diner **Upgrading**
## Cooking

For cooking dishes there are 4 stations, each with a designated food recipe. Players need to place the appropriate ingredients for a recipe on its associated station and interact with the station to prepare the dish.

### Iteration #1
Initially the cooking system was going to feature minigames and some sort of UI for each station and the game generally was planned to be a slower paced game.

**Feedback:**
- It felt clunky having to open a menu
- Having to memorize the right ingredients and where they went also slowed the game down especially if a mistake was made

**Solution:**
- Remove menus for cooking stations and scrap minigame idea
- Add condition to where ingredients can only be placed down onto a station that needs that ingredient

These changes were done to reduce the cognitive load on players and to help speed up the moment to moment gameplay.
### Iteration #2

The game felt a lot more responsive and smoother to play than before but certain actions felt lacking in feedback and a bit too same-y.

**Feedback:**
- Confusing as to what a station needs
- The process of cooking wasn't exciting

**Solution:**
- Added meshes of placed ingredients on stations
- Added progress bars for cooking
- Made some stations require player to hold cook button and some stations have a timer

The goal was to make things more clear to players for what ingredients are still needed on a station for a dish and once again reduce the cognitive load so they don't have to memorize this part of the process.

Then by having some stations be based on a timer that is started by the player and some dishes being made by the player holding the interact button, the game would have some level of time management and require the player to plan which ingredients to source first and when to initiate certain dishes.

### Iteration #3

At this point the core systems for the cooking portion of the gameplay loop was finished and just needed slight balancing and more feedback to the player such as SFX and VFX and to have these things properly toggled. 

**Feedback:**
- More clear feedback for what is happening
- Clarify what is interactable
- Some recipes didn't yield enough money for the work put in

**Solution:**
- Play SFX, VFX and animations for when stations are being used
- Added glowing dynamic material for when stations are interactable/enabled
- Rebalanced the currency return values for recipes
- Added coffee station for more potential money gain as bonus orders

All of this was done to help show the player that things are actually happening due to their inputs and overall improving the feeling and ambiance of the game. 

The coffee station allows the player to make coffee which is a simple recipe that customers have a chance of ordering after their main order providing bonus money.

## Printing

In the future sourcing ingredients has advanced to the point where you can just 3d print your groceries. This is how players can acquire any ingredient they need and however much they need.

### Iteration #1

Initially the game was going to feature a hunting/gathering phase where players collect their ingredients before opening up shop and preparing dishes with a limited number of ingredients.

**Feedback:**
- Managing ingredients added complexity without depth and felt unnecessary 

**Solution:**
- Added an unlimited number of each ingredient in the fridge

### Iteration #2

Now that the ingredients were infinite there was a bit of dissonance with the idea with a bottomless fridge, so this station was changed to a 3d printer which also played into the futuristic themes of the game.

**Feedback:**
- A bottomless fridge feels dissonant with theme or at least doesn't play into it

**Solution:**
- Changed fridge to 3d printer
- Adding a "print time" in between the player selecting an ingredient and being given the ingredient
- Changed the way food is given to player by instead of directly dropping into the players hands it prints food onto a tray that players can then retrieve the ingredient from

These changes were made to play into the new station from fridge to printer while also adding a bit of pressure to the player to plan ahead since ingredients are no longer on demand.

### Iteration #3

Printing ingredients added a new layer to the cooking system but wasn't really fleshed out and felt like purely like a hinderance without much depth.

**Feedback:**
- Having to wait for ingredients feels kind of bad
- Seems like needless friction for the player

**Solution:**
- Added a printer queue where players can have a buffer of multiple ingredients that are automatically printed in order.

This adds a benefit to the player by allowing them to set multiple ingredients to print and then work on other tasks in the meantime. It also adds more depth to the system by making players more considerate as to what they print and in what order. 

This also increases the chaotic nature of the diner by having players going back and forth quickly between stations and the printer and topping off the queue.
## Upgrading

The idea was to have an upgrade system that was used to repair a run down family owned diner and some upgrades that  allow the players to make more money as the main appeal of upgrading.

### Iteration #1

The upgrade system was initially the way to progress through the game by slowly restoring the run down diner and unlocking more recipes that yielded more money.
 

**Feedback:**
- Upgrades didn't feel impactful to the gameplay
- Upgrades didn't feel worth the cost

**Solution:**
- Added Kitchen Tray slots upgrade(Spots that food can be placed onto)
- Re balanced upgrade costs and money gain from associated recipes

This functionally acted as expanding the players inventory since they can pre print or pre prepare dishes and store them for when a customer arrives and orders something. Allowing for more strategic play and depth to the gameplay loop.

### Iteration #2

The trays added proved to be beneficial to players so this iteration we leaned more into that style of upgrade and added a new station to help address the money issues.

**Feedback:**
- A way to make more money would be nice
- There needs to be more upgrades that aren't just stations

**Solution:**
- Added Coffee station for extra income
- Added Blender upgrade

The Coffee station allows the player to sell coffee, which is a simple recipe, that customers have a chance of ordering before leaving which provides potential bonus income.

The blender upgrade automatically chops ingredients upon being placed which saves a lot of time and is useful for busy days.

### Iteration #3

At this point in development the Printing Queue system was implemented, so to round out the upgrade system I added an upgrade for extending the queue limit.

**Feedback:**
- printing capacity felt limiting

Solution:
- Added the ability to expand the printing queue from base(1) to a max of 3

The ability to expand the printing queue helped alleviate the downsides of having a print time and even became a very helpful upgrade when fully leveled up.