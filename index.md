# Ulthuan - WIP

## How this plays

This is a set  of rules for an epic digital warhammer multiplayer campaign. The battles are played in Total War Warhammer II, but everything else takes place outside the computer game. It’s inspired by the blood in the badlands campaign for the tabletop game, but played 100% online.

***What do you need?***
- Some friends. Either so close you are absolutely sure your friendship will survive this, or someone you might be willing to sacrifice for a good backstab... We played with 6, but some more should also work if you adapt the rules accordingly.
- Time, something like 3-6 months depending on how committed you are. A phase of lookdown during a global pandemic has proven to be fitting.
- The computer game Warhammer tw2 for every player. We didn’t go for wh tw3 due to the (current) lack of playable fractions. 
- Ways of communicating: a signal or whatsapp messenger group is sufficient 
- A shared shared Google doc presentation for keeping track of everything: the map, diplomacy, army setups etc - an example is here: TODO
- a way of randomizing things, we went with a fancy custom dicerolling bot for our signal group but there are also [simple free webistes](https://www.rolldicewithfriends.com/) available for that task.

## Introduction
*Father NUrgle has released his masterpiece on the Elves of Ulthuan: The most infectous of diseases has spread like wildfire through the island and left whole cities and provinces deserted. The weakened elves struggle to keep a few strongholds, but most of the land is deserted. Treasure Hunters, Adventurers and settlers are flocking to the harbours of the old world; to catch a ship to the land of unlimited riches and opprtunities. "Humanitiarian Expeditions" and worse are mustered. Noone seems to be bothered by the fact that the plague is still around...*

## Overview
Like in any decent strategy game, there is a strategic map where you move your armies, build cities and infrastructure etc. with a limited amount of Action Points (AP). When armies end their turn on the same province, a battle is fought in Warhammer Total War and the winner usually gets the province. For winning battles and various other things you get victory points (VP). Depending on the victory point progress various special events are triggered. And there still is the plague, that might get out of control if you don't collectivly establish some basic hygiene rules...

## The Map
![The Map](https://github.com/childerich/ulthuan/blob/gh-pages/maps/ulthuan_final.JPG)
You find a map of Ulthuan separated in 36 provinces in the maps folder. It's made by hand with more love than skill, so feel free to modify or make up your own if you prefer. If you are lazy copy this map as the first page of our google doc-presentation, steal some coloured icons (armies, cities, control etc.) from the internet that can be copied&pasted and moved around and you are ready to go.

## Turn Sequence
Every turn represents a month in Ulthuan. We tried to play one turn every real time week, with a set appointment of a game night every tuesday when all the battles are fought and the bookkeeping for the next turn is done - but use whatever fits for your group. Every Turn consists of the following steps:

1. ***Plague of NUrgle***: Roll a D3 and move the [Plague Bar](#plague) down by the amount, to a minimum of -10. Then increase it by one for every action point the players have invested into hygiene measures in the previous turn. For every hygiene measure, the player can now declare himself immune against a single effect of the plague of Nurgle for this turn. Then activate all the effects of the plague, starting at 0 and ending at the effect with the current marker
2. ***Production***: All mines, harbours and shrines of all players produce now. Owners of sanctuaries have to decide if they produce AP or VP. Then check if all the players can still pay the upkeep of their armies or have to disband armies.
3. ***Random Events***: In current Turn order, roll a D66 for every player and evaluate the [Random Event](#events)
4. ***Trade***: Prisoners of war can be exchanged, freed or executed, Magic Items traded. If you want to relocate your capital, now is the time.
5. ***Action Phase***: Every player starts with 3 AP (Action Points) by default. The 1st player in the Turn order uses all his or her AP, then the 2nd etc. The Turn order will stay the same for most of the campaign, but the starting player rotates every turn, meaning that who went 1st goes last next turn, who went 2nd goes 1st etc. 
6. ***Battles***: All battles are preferably fought on the game night together. If you can't make it, you can always nominate another player as replacement or let the AI fight (difficulty hard)

## Victory Points and special Events
*You should define for yourself what VP represent for your faction, what are you actually looking for in Ulthuan? Treasure, Elven artifacts, warpstone, shimmering garbage - there is enough for everyone*
Whenever the first player reaches a specific amount of VP, a special event is triggered at the end of the turn:
- 6 VP: Lothern
- 13 VP: Shrine of Khaine
- 21 VP: Vaults Anvil
- 30 VP Gaean Vale
- 40 VP: [Isle of the dead / the Final battle](#special5)

## Actions
Per default, every player has 3 AP (Action Points) per Turn. 1AP can be spent for:
- ***Move***: Move one of your armies or the army of a friendly (relations >0) creep nation. Movement normally goes for up to 3 fields.
- ***Recruit***: Create a new army on a field you control. If you would have too many armies afterwards, you have to disband one
- ***Build***: Once per army and turn: if you own the field you are standing on, and there is no unfriendly army: either create a new building if the field is empty, or upgrade the existing building.
- ***Demolish***: Remove or downgrade the building on an own field with an own army
- ***Hygiene Measures***: Improve the Plague Bar by 1 next turn, buy temporal immunity against one plague effect
- ***Poison a well***: Lower the Plague Bar by 1 next turn
- ***Diplomacy***: Either improve your own relation with a creep nation of your choice by 1 (and gift them gold if you like to) or lower the relations of another player with a creep nation of your choice by 1 

## Movement
The following movement rules apply to all movements, independant if its your own or a creep army and if the movement is triggered my an action or by an event.
- You can move up to three connected map fields far, but all the movement has to be spend on one army
- Mountains cannot be crossed
- An army can only be moved once per turn
- There is no limit to the number of armies allowed on one field
- Water fields can only be entered from a friendly harbour field. 
- Movement cannot be ended on a water field
- If you move on a field with another fortress, city or army (not garrison): If any of the owners wishes, your movement is over and the army stays there. If the owner is creep, they will stop you unless you have friendly relations.

## Armies
Newly trained armies have a value of 10000 gold. Their exact composition is undefined until they fight their 1st battle, afterwards the composition may not be changed and has to be made public to all players. Armies have to abide the unit caps for balanced play. RoR (Regiments of Renown) Units and named charakters may be used, but are only allowed in a single army (of one player) at a time. Gold can be spent at any time to buy adtional units or upgrades for an army. 
Every player can support one army, +1 per city under their control. Consequently, in the beginning every player can support two armies. If a player recruits although beeing at the upkeep limit, she or he has to immedeately disband another army. If a player has too many armies for another reason (eg loosing a city) in the production phase, they have to disband armies until the upkeep limit is reached.
Armies with undefined composition are affected differently by negative effects: If the leader dies they get -500 points, if they have to roll on the defeat table they loose 250 gold instead.


## Buildings
Only one building is usually allowed per field.
- ***Fortress***: You can always defend that field with a garrison (10k random army of your faction). If you defend a field with a garrison with your own army, this army gets temporarily +1000 Gold. Blocks enemy movents as described in the movement rules.
	- can be upgraded to a ***City***: As a fortress but the garrison is 11k gold and a defending army gets +2000 gold. Allows you to support an additional army
- ***Shrine***: Produces 1 VP per turn.
	- can be upgraded to a ***Sanctuary***: owner can decide to produce 1 AP instead of 1 VP
- ***Harbour***: Can only be built on coast (fields touching a water field). Allows entering water fields from this field. Produces 100g per turn
	- can be upgraded to a ***Shipyard***: Produces 200g instead, moving armies on water fields from here doesn't count as moving a field.
- ***Mine***: Can only be built inland (fields touching a mountain). Produces 1D6 x 100 gold per turn. If the modified roll is 1 or less, the building gets destroyed instead.
	- can be upgraded to a ***Mining Town***: you may reroll the D6 once per turn but have to accept the 2nd result. 

## Battles


## Creep
### Creep Factions
There is no such thing as an unoccupied field in Ulthuan, every field that doesn't belong to a player belongs to a "creep faction". Creep factions can own (multiple) fields but only act very limited unless influenced by a human player. For every creep nation you need to keep track of the following things (we've put a matrix-table in our google presentation for this):
- the warhammer faction
- their gold reserves - 0 for new factions
- their diplomatic relations with all human players - 0 for new factions

### Diplomacy
Diplomatic relations per player can be improved and lowered (also below 0) by random events and by investing AP. They are also automaticly lowered by 1 per battle a player fights against a creep faction in a field owned by that faction. If relations are >0, they are considered friendly which allows a player to move their armies, use their infrastructure and only fight them on his own will. All creep nations are considered to have relations 0 with each other.

### Battles agains creep
Creep always fights with randomly generated armies. Controlled either by a hard AI, or by a volonteer player - if several players want to fight, the player with the best diplomatic relations gets to go. The player controlling the creep is *bound by honour* to try to win the battle for the creep - if this concept doesn't work for your group, pick a different one (or, new friends). The Creep army has 10k gold +/- the current gold reserves of the faction. But never less than 9k gold and never more than 1000 gold more than the opponent.
If a creep army looses a battle, they don't roll for defeat&spoils of war but get -500 / +500 gold reserves instead - even when fighting with a garrison. They don't roll for defeat but their army marker is immedeatly destroyed when it looses a battle. Creep can defend every field with a garrison (this does not block movement) independant of the position of their army marker. Creep can support 1 army, if a creep faction with at least 1 field has no army marker in the production phase of a turn, a new one is spawnded at a randomly determined field they own. 

### Creep Buildings
Buildings controlled by creep have slightly different effects. To represent their primitive nature, they treat all upgraded buildings as their base version.
- ***Fortress***: +1000 gold for defending this field. Blocks unfriendly movents as described in the movement rules.
- ***Shrine***: Produces 1 VP per turn. This is accumulated on the field and is collected by the next human player to control the field in the production phase. 
- ***Harbour***: Allows entering water fields from this field. Produces 50g per turn. This is accumulated on the field and is collected by the next human player to control the field in the production phase. 
- ***Mine***: Produces 200 gold per turn. This is accumulated on the field and is collected by the next human player to control the field in the production phase. 





## Prisoners

## Game Setup
The map has 36 normal fields(the islands are closed in the beginning) an should be initially populated by 12 factions with 3 fields each. All slots not taken by human players are taken by creep factions. Randomly bring all human players in an order - this is the order of play and should be noted down prominently. Now the first player announces her faction, places his capital, an army marker and a control marker on an empty field of their choice. Then she puts a control marker on 2 other empty fields next to the capital. Repeat this process for all human players in turn order. 
When thr last player placed her capital, she creates a creep faction of her liking by placing a fortress, an army and a control marker on an empty field. 2 more control markers have to be put on empty fields; next to an existing one if possible but as the map might be quite fractured at that point it, freely pick an empty field if neccessary. Then repeat this in reverse turn order until all 36 fields are taken.


## Restart
The campaign is intended to be fought until the bitter end with all players - there is no way to knock a player out of the game permanently. As this process might take a long while, players annoyed or simply bored with their faction choice also need a chance to try something new. If you prefer to play hardcore, simply ignore this chapter but this might not balance well...
At the beginning of their turn, a player can decide to abandon their current faction and restart. This can only be done if the player doesn't have a capital
 any more or didn't pull of a restart in the last 5 turns. The restart uses all the AP of the player for this turn and can be executed in two different ways. Pick one:
 - *political marriage* take over an existing creep faction with their fields, their buildings and a fresh 10k point army at the position of their army marker.
 - *invasion* pick a new faction that is more to your liking. Pick a normal coastal field without a capital. Remove all buildings and control markers from this field, add your own control marker, your capital and 2 fresh 10k gold armies. 

The player looses all his current gold, but keeps his VP and position in the turn order. Then roll a D6, the player looses that many VP. Then multiply the result by 400, the player gains that many gold. The old faction of the player now forms a new creep faction controlling all the fields and buildings but loosing all their armies. The diplomatic relations of the new creep faction with all players as well as the relations of the player with all creep factions are set to 0. 

## The Capital

## Misc rules

## The Plague Bar {#plague}



## Random Events {#events}

## Spoils of war (1D6)
1. *Glorious Victory*: You get +D3 VP
2. *Rich Bounty*: You get +D6 x 100 gold
3. *Veteran Troops*: One unit in your army my be promoted to max experience level.
4. *Living Heroes*: You may replace one unit in your army with their RoR aequivalent (if that exists, ignore equipment options)
5. *My kingdom for a dragon*: The Leader of the army or any hero may freely pick a ability, spell or magic item from the equipment options. They can also choose the cheapest mount instead or replace their current mount by the next more expensice option.
6. *Too many options*: pick freely from the options 1-5

## Defeat! (1D6)
1. *Eternal Shame *: You loose 1 VP
2. *Severe Losses*: The next battle this army fights, you have tp leave one unit of your choice at home.
3. *Green Troops*: All units in this army loose all their promotions.
4. *Massacre*: You permanently loose one unit of your choice from this army
5. *Curse of Bukephalos*: The Leader of the army looses an abilty, spell or magic item of your choice or the mount is replaced by the next cheaper option.
6. *Learn from your mistakes*: The army composition is considered as undefined and can be changed freely until the next battle (with same gold value of course)

## Retreat (1D6)
1. *Armageddon*: The army is disbanded. The general is dead.
2. *Shameful surrender*: Retreat 1 field. The General is taken prisoner by the victor
3. *Deep wounds*: Retreat 1 field. The General is injured an misses the next battle
4. *Huh?*: Retreat 1 field. 
5. *Huh?*: Retreat 1 field. 
6. *Part of a bigger plan*: Immideatly make a normal movement with this army as if this was your turn.


## 1st Special: Lothern {#special1}
### Mode of play
### Bounty

## 2nd Special: Altar of Khaine {#special2}
### Mode of play
### Bounty

## 3rd Special: Vaults Anvil {#special3}
### Mode of play
### Bounty

## 4th Special: Gaean Vale {#special4}
### Mode of play
### Bounty

## The Final Battle: Isle of the Dead {#special5}
The battle of the isle of the dead is the final of the campaign and determines the glorious winner. It’s triggered at the end of the turn in which any player reaches or exceeds 40VP. Alternatively, if you want to or have to end the campaign early, just fight it at any point in the campaign - if all players agree of course. 
### Fluff
insert fluff here
### Mode of play
It happens in the following steps:
1. *Muster your forces*: all players pick their favourite army. Remaining gold and magic items can be traded and invested for the last time.
2. Rank all players by their current VP decending.
3. Now play a normal pitched battle between the last and the second last player. Calculate the difference in VP between the two players. For every point difference, roll a D6 and multiply the result by 100 - the higher ranking player can now buy temporary reinforcements using that many gold. The reinforcements disappear after the battle. Note that the 75% rule still applies.
4. If the lower ranking player wins the battle, ***the VP of the two players are switched***. The campaign is now over for the loosing player. 
5. The winner now plays a battle against the next player in the ranking exactly as desribed at (3) - potentially using their newly achieved VP when the strength difference of the higher ranking player is calculated.
6. Repeat 3&4 until every player has played at least one battle
7. The player with the most VP now is in control of the maelstorm and wins the campaign. 
