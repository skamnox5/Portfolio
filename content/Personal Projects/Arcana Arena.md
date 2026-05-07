---
tags:
  - Game_Designer
  - Shipped
---

<Carousel>
<img src="Arcana_Arena_Tablet.jpg" alt="Tablet"/>
<img src="Arcana_Arena_Cards.jpg" alt="Cards"/>
<img src="Arcana_Arena_Spells.jpg" alt="Spells"/>
</Carousel>


Game Design Skills: Game Prototyping Boot Camp project

Project Link - [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3678184422)
# Details

- **Genre:** Competitive Spell Crafting 
- **Type:** Proof-of-concept prototype
- **Software:** Tabletop Simulator
- **Duration:** 8 Weeks
- **Iteration#:** 6
- **Playtest#:** 4 
- **Role:** Game Designer (Research and concept, Documentation, UI, prototype, balance)

# Iteration Overview

Prototypes:

<Carousel>
<img src="Arcana_Arena_Miro_Prototype.png" alt="Miro Prototype"/>
<img src="Arcana_Arena_TTS_Prototype.png" alt="TTS Prototype"/>
</Carousel>


# Goal

The goal of making Arcana Arena was to explore designing a dynamic magic system for potential use in a video game that can meet the following key points:

- **Immersion:** Give the player the feeling of someone who had to actually learn the spells in real life just as their character would in game
- **Versatility**: Have magic feel like a multitool where spells can be tailored for most situations and playstyles
- **Power Fantasy:** With all of the trade offs for being able to cast magic it should feel like a worthwhile pay off.

I sought regular feedback from Jeremiah Franczyk(Lord of the Rings Online) who helped with Resonance and Theming.

# Overview & Technique Highlights


## Game Premise
The game is like Bingo with PvP enabled, where players are put to the test against fellow players to see who can best utilize what is available to them to achieve victory.

 Up to 4 players fill out their Tablets or "Bingo Sheets" based off of the drawn cards and then craft spells to either protect themselves or attack opponents, all while trying to also fill their mana bank with excess mana with the aim to be the first to reach the mana cap or be the last one standing.

## Technique Highlight #1: Magical Strategy

Goal:
	I wanted to give players a varied toolbox that allows them to express their skill and play into a power fantasy

Result:
	I Created a list of spells with various effects that play into different playstyles/fantasies

Technique:
- Having multiple spells gives players a multitude of options.
- Giving the different spells varying effects that play into their theme allows for players to lean into a playstyle and power fantasy at the same time.
- The effects of spells and how they might interact with each other adds a layer of strategy to the game


## Technique Highlight #2: Uncertainty 

Goal:
	Enable emergent gameplay to create variety in moment to moment gameplay

Result:
	Added elements of chance/luck to mix up gameplay for players

Technique:
- Using the Bingo like system of cards being called and markers on a card add levels of chance to the game.
- Adding multiple attributes per card adds some level of control and gives the player more options for improvising a strategy based off of available combinations.
- Mana surges add another level of chance/risk to the game and gives players another avenue for attempting to give themselves an edge in the game.


## Technique Highlight #3: Competition

Goal:
	To have a sense of competition in the game where players feel like they are pitted against each other and feel like they need to interact with each other.

Result:
	Balanced the game where engaging with opponents is a viable strategy

Technique:
- Changing certain card effects to directly grief other players
- Increased inherit damage of debuff spells
- Balancing health and mana bank values to where pvp would be the more optimal strategy


# Process Breakdown
## 1: Research Ideation and Theme

The game I want to make is one that evokes the feelings of being a spellcaster that has to think of a spell that best suits the given situation. I also want the game to feel varied each time you play with the many given options available and to have a bit of a friendly competitive feel to it. The purpose of this game is to explore the mechanics of a magic system that delivers the feeling of being a mage in both power fantasy and technical understanding of the magic system.

<Carousel>
<img src="outward_runes.png" alt="outward runes"/>
<img src="recluse_magic.jpg" alt="recluse magic"/>
<img src="loteria.png" alt="loteria pic"/>
</Carousel>

- **Analyzing Games:** One game that very heavily inspired this goal of immersive magic is Outward with its different magic systems that require preparation and understanding of the system itself in order to use its versatile magic. While Outward has multiple types of magic that work differently the main magic system that I drew inspiration from was its Rune Magic. I also thought of Elden Ring: Nightreign's recluse and her magic cocktails for inspiration with the idea of working with what is available to you. I also used Loteria a game similar to Bingo as inspiration for how the game would broadly be played.
- **Researching Real-World References:** This helped with coming up with the structure of crafting spells by giving different effects based on the combination of symbols.
- **Resonant Theming:** The premise of being students in a magic school and learning spells while competing against other students lets players feel more immersed.

## 2: Design Document - Rulebook

![[Arcana-Arena-Rulebook-V2.pdf]]
 
 **Premise:** 
	I wanted to have an immersive spell casting game system and to do this I outlined a modular spell crafting system that allows players to mix and match different aspects to create an appropriate spell for the current situation.

**Theme:** 
	Because of the system being about creating spells I thought that the setting being mock battles in a magic school was apt, since the feeling of players learning the spell system can play into that fantasy.

## 3. Paper Prototyping



![[Arcana_Arena_Miro_Prototype.png]]


**Result:** 
	The interplay of the spell casting system was honed in a bit more than the initial concept to allow for players to try to counter different playstyles. This was done by filling out the list of possible spells and having some spells able to counter certain actions other players can take.

**Goal:**
	To plan out a magic system that can allow for emergent and reactive gameplay while also supporting the ability to play into certain playstyles like defensive, healer, offensive, etc.

**Solution:** 
- I created spells with the idea that they can potentially counter other spells/playstyles
- I also ensured that each tablet has each possible attribute so that, unless someone is extremely unlucky, they should be able to cast any kind of spell possible at some point in the game.
- By structuring the gameplay similarly to Bingo it makes for an easier onboarding experience, but also adds variance in what spells are accessible for each player in a round which makes players have to play reactively to the potential spells they or other players gain access to.


## 4. The First Interactable



**Result:**
	Removed the requirement of a pattern match for casting spells and removed minimum mark requirement for depositing in bank.

**Goal:**
	Have a playable version of this game to properly test out spell dynamics and overall flow of the game.

**Implementation:**
- Mechanic Synergy 1: Pattern match bonuses add an element of luck to the game that can provide a meaningful boost and make gameplay more exciting and adds a factor outside of skill to the game.
- Mechanic Synergy 2: Attribute Extraction from marked cards limits the possible spells that can be crafted each round, but still gives player multiple options for what can be done that round allowing for strategy and skill expression for players who know the possible spells and thinks ahead.
- Narrative Synergy: The setting for the game is students in a mock battle to test out a mage in training's ability to strategize and improvise both of which the player will need to do while playing the game. 

## 5. Playtests and Key Iterations

### Playtest #1 Highlight


**Results:**
	Players enjoyed the theme of the game and the concept of crafting spells

**Feedback & Problems:**
	Most players were not able to get a pattern match which in turn resulted in the inability to cast spells meaning players were left not being able to actively participate in the game.

**Solutions:** 
	I removed the condition of needing a pattern match to cast a spell. Now only 3 placed mana marks are required.

### Playtest #2 Highlight


**Results:**
	Players enjoyed crafting spells and the idea of competing against each other.

**Feedback & Problems:**
	Pattern matching should have a bonus and offensive play lacked incentive compared to defensive play.

**Solutions:** 
	I added several bonuses for getting a pattern match and implemented a new way of deciding turn order because of the requirements of spell casting changing. I buffed offensive spells to be more incentivizing for players.

### Playtest #3 Highlight


**Results:**
	Players enjoyed the overall structure of the game and gameplay dynamics.

**Feedback & Problems:**
	The various spells can be a bit confusing with their descriptions as to how they interact with each other.

**Solutions:** 
	I worked on making spell descriptions easier to understand/clarify things a bit more.

## 6. Polished Portfolio Piece

<Carousel>
<img src="Arcana_Arena_Cards.jpg" alt="Cards"/>
<img src="Arcana_Arena_Tablet.jpg" alt="Tablet"/>
<img src="Arcana_Arena_Spells.jpg" alt="Spells"/>
</Carousel>

**Results:** 
	Made a playable game that features spell crafting/casting on Tabletop simulator.

**Goal:**
	To make a dynamic game that allows for varying strategies and playstyles themed around spell casting.



**Execution:**
- **Magic:** Gave players many potential options for approaching various situations with the variety of spells effects that can be casted.
- **Uncertainty:** Adding elements of luck/chance with what cards are drawn each round means that players will have to adjust their strategy each round.
- **Competition:** Having to go up against other players means you have to take the actions of others into consideration, adding more variance to each game.


