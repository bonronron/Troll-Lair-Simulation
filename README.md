# Troll-Liar-Simulation
The project has been developed using Unity [NPBehave library](https://assetstore.unity.com/packages/tools/ai/npbehave-event-driven-code-based-behaviour-trees-75884) and [UnityMovementAI](https://github.com/sturdyspoon/unity-movement-ai) system. 
There are 2 main components to simulation. 

 1. Procedural Generation of Caves using Cellular Automata.
 2. Interactive Agents using Behaviour Trees and Utility States.

## Troll Chief
The Troll Chief agents are a lousy agent who wander around the map or sleep or places down a torch here and there. They do not work much but rather are a point for their minion Trolls to bring and hoard their loot to. (Inspiration was Jabba the Hutt)
## Troll
The Troll agents are worker trolls who wander the caves scavenging for gems, when they have a direct line of sight of a gem, they go to pick it up and bring it back to their Chief.
## Thief
The Thief agents are afraid of trolls and will try to avoid them, they try to stay in the dark and will try to avoid any torches placed as well. They steal gems from a troll chief and then hide it next to the nearest other gem lying around they find.

# Buttons Explanations
|Button Name|Use  |
|--|--|
|Reset  |Resets automata to make a new cave system  |
|Evolve Caves| Evolves current map according to generation rules|
|Add Gem| Randomly places a gem in the open space of the word|
|Add Chief| Adds a Troll Chief agent to the map|
|Add Troll| Adds 10 Troll agents to the map|
|Add Thief| Adds 10 Thief agents to the map|

# Notes

 1. Trolls and Thieves will only assign to one of the existing chiefs in the world randomly. New Chiefs spawned after creating trolls and thieves will not have any assigned to him, you will need to spawn new Trolls and Thieves to have any assigned to it.
 2. The Reset button currently does not reset the agents, gems and torches, and they may glitch off the map if reset.

Current running version of simulation: [https://ronbonb0n.github.io/Troll-Liar-Simulation/TrollLairBuild/](https://ronbonb0n.github.io/Troll-Liar-Simulation/TrollLairBuild/)
