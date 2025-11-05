# Cat's Cradle Coven  
## Repository  
[Link to my repository!](https://github.com/BellaGould/ANGM-2305-Final-Project-bGould)  
## Description
Cat's Cradle Coven is an interactive text-based RPG/management sim where you lead a group of magically-inclined felines to hone their craft and cast ever more powerful spells deep in the woods. Gather resources, conduct rituals, and bond with your fellow coven members as you pursue the root of the power you hold...  
## Features
- **Collect resources!**
  - Players will be able to select 1-3 cats from their list of companions to either hunt or gather herbs each day. Results will depend on the companions' stats, stored in a CSV file.
- **Cast spells!**
  - Resources from hunting/gathering will be added to a list. Players can sacrifice items from the list to use them in spells to upgrade their stats.
- **Random events!**
  - Each day, a random function will pull a number and pass it to a random event function. Events may be good or bad, or require skill checks to get good results. Events will scale with difficulty through the random range being expanded by either the number of companions you have or their total stats (I haven't decided yet.)
- **New cat friends!**
  - Some random events may allow you to recruit new companions by passing a skill check. While in camp, you can talk to your current companions and build friendship with them by picking the correct responses (might unlock new spells through this?)
## Challenges
- Complex stat/inventory management through a combination of lists, dictionaries, and CSV files.
- Building an engaging random event system through the random keyword.
- Creating balanced gameplay that's neither too easy nor too frustrating. Allowing a sense of progression and upgrade without letting players become OP early on.
## Outcomes  
**Ideal Outcome:**
- Hunting/gathering system relates to cats' stats, allowing for greater results the stronger your coven gets.
- Unlock new spells for greater strength boosts.
- At least 10 random events, possibly with some story events worked in on certain in-game days.
- Ability to hold conversations with cat companions to get a greater sense of their personalities. Ideally, reaching maximum friendship would yield some sort of reward - a special scene, a new spell, increased stats, or some other boon.
- A game that is cute, fun, and semi-addictive.
  
**Minimal Viable Outcome:**
- Hunting/gathering system works as described above.
- Instead of unlocking new spells, you could just have them all when the story starts but not be able to cast them without the requisite resources.
- Between 5-10 random events. Story events may be minimal, absent, or replaced entirely with more random events.
- Talking with cat companions yields short dialogue snippets, but has no effect on the gameplay.
- A game that has a functional, complex inventory system and random events. Minimal story, but a good base for building a more polished product around.
## Milestones
- Week 1 (11/4-11/10)
  1. Basic outline of story and required features, plus an execution plan (will be done on Procreate).
  2. Start a code file with if __ name __ = __ main __. Add some pseudocode to get a sense of how I'll organize the code file.
- Week 2 (11/11-11/17)
  1. Code has input functions to allow player to select cats to gather resources. Cat's stats are taken into account when determining result of expedition. 
  2. Collected food/herbs are stored in some sort of inventory - determine what. I like the idea of a dictionary.
  3. Option to cast spell to restore health of injured cats (cats will not be able to lose health yet).
- Week 3 (11/18-11/24)
  1. Main gameplay loop calls a function that returns a random number, then passes that number to a random event function. At least 5 events are functional.
  2. Cats can lose health in random events. At least one event calls cats' stats to determine result.
  3. You can cast spells to increase cats' stats.
- Week 4 (11/25-12/1)
  1. Camp screen has the options to hunt, gather, cast spells, or talk to other cats. Base gameplay elements are set in stone, allowing for further flourishes to be added.
  2. Add another 5 random events. Preferably, all cat recruitment events are added and they affect the range of random events.
  3. If there's extra time this week, add several (2-3?) conversations for each cat. Ability to raise your relationship with them by selecting the correct responses.
- Week 5 (12/2-12/8)
  1. All previous milestones have been implemented. Unfinished/unpolished features are fixed.
  2. More conversations with kitty friends. If they could have little comments when selected for gathering, that'd be cute - if not enough time, no big deal.
  3. Video recorded.
