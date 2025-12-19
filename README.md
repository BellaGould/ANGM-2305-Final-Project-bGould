# CAT'S CRADLE COVEN

## Demo
Demo video: https://youtu.be/wM3JuiRKiwk

## GitHub Repository
Repository link: https://github.com/BellaGould/ANGM-2305-Final-Project-bGould

## Description
This is a spooky-cute RPG management sim inspired by the Warrior Cats series by Erin Hunter. Collect a coven of adorable feline companions, send them to gather resources, upgrade their stats with spells, and deal with a bevy of random events!
The repository contains the code for the project and a premade save file I left in for easy testing of the save/load function.

**Features:**
- Exploration: you can send any currently available (noninjured) companion out to hunt and gather herbs. Hunting/Gathering results are determined by combining rng with the companion's stats.
Food is consumed by your companions at the start of every day, with health penalties if you run too low to feed everyone. Herbs are used for casting spells that either recover health or raise stats.
- Spellcasting: You can spend herbs to cast spells that permanently upgrade companion stats. Not only is this important for exploration, but several random events have different outcomes depending on
the player and their companion's stats.
- Conversation: You have the option to talk with one companion per day, earning a cute line of dialogue or two and an added friendship points. At higher levels of friendship, talking to a cat can
boost a random stat of theirs by up to 5 points.
- Random Events: The end of every day triggers a random event. Some events are short and simple, while others require player input or stat checks to resolve. Random events can have rewards or consequences depending on your choices.

**Future Considerations OR What I've Learned**
I went into this project with the idea that I could layer many simple functions to make a complicated, fun game, and I found I was right. It's amazing what you can do with a few simple tools. With that said, I tried to add more sophistication
to the project with the CSV-based save/load system and with very clean menus and instructions. One of the biggest struggles I had while making the game was balance - every variable affected another, and I played through the
game several times just tweaking them to make the game neither ridiculously easy nor frustratingly difficult. I think I got the balance of herbs/spells right, but I'm still not completely happy with the role of food.
If I started again or kept working on the game, I might make hunting and gathering separate functions instead of the same thing. I might also take away healing spells (or make them more expensive) and make food the main source of healing.

I actually plan to continue developing the game after the semester ends, at least to add in all the content I originally planned. I would like to put in all the companion recruitment scenes and more random events. In the beginning,
I'd thought to have 20 events per companion - that wasn't possible for me in this time frame, but I think it would add a lot of fun. Additionally, I've considered porting my code to Ren'Py, the visual novel maker,
which makes it easy to add graphics, text boxes, and backgrounds. If I did that, I could make my own images for the characters.

I'm proud of what I did, but I also see lots of room for further development. I'm excited to see where I can take this project in the future.
