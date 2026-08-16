---
{"dg-publish":true,"permalink":"/portfolio/hunt-showdown-system-analysis/","tags":["portfolio"],"dg-note-properties":{"tags":["portfolio"]}}
---


*12/1/2025: This was a system analysis that I submitted for a NetEase internship in December 2019. I was offered the internship, scheduled for June-August 2020 in Guangzhou. Obviously, I did not get to actually do it* 🙁

# Game Overview
_Hunt: Showdown_ is a horror multiplayer PvEvP first-person-shooter, wherein squads of players compete to find and kill 1-3 boss monsters on a large open map set in 1890’s Louisiana bayou. Squads must find and navigate through points of interest to find clues that will lead them to the boss’ location. Bosses drop bounty tokens when killed, which players must pick up and move to a randomly placed extraction point on the edge of the map. Other squads can kill bounty holders and take the bounties for themselves.

# Progression Systems: Bloodline and Hunter Leveling
![Hunt_Bloodline-1-1024x576.png](/img/user/Images/Hunt_Bloodline-1-1024x576.png)
*Pictured: Bloodline Progress Screen*

In *Hunt: Showdown*, players recruit hunters with random gear and perks to play as. The game features permadeath for hunters, losing all their weapons, perks, and equipment on death. This creates interesting tension when using a veteran hunter with expensive weapons and good perks. There are two forms of experience points (XP) that the player is rewarded with, hunter XP and bloodline XP. Upon completion of a game through extraction (the hunter survived, with or without the bounty), that hunter is granted XP based on their performance. They gain XP for killing monsters, discovering clues, killing other players, and locating the bounty’s lair. This amount of experience is also directly applied to the bloodline. If the player’s squad is wiped out and their hunter dies, they get half of the XP that they gained up to that point in the game applied to their bloodline. The player’s bloodline level unlocks new weapons and equipment in the shop and allows them to recruit higher tier hunters. Hunter XP levels up the hunter, with each level granting a perk point. These are spent on perks for the hunter, with varying costs. Upon reaching level 25, a hunter can be retired, which grants large amounts of bloodline XP (100 per level) at the cost of removing the hunter from the roster. Weapons and equipment are stored and available for use on other hunters.

Not all weapons are unlocked through the bloodline. Usually a base weapon will be unlocked this way. For example, the Vetterli 71 Karabiner is a bolt action rifle unlocked at bloodline rank 6. However, the weapon has two variants, one with a scope and one with a bayonet. These variants are unlocked through earning XP with the base weapon or any variant of it. XP in this case is earned through killing NPC enemies or other players. All variants in the game are unlocked in this way, with the base version being acquired through bloodline rank progression.

![Hunt_Perks-1024x576.png](/img/user/Images/Hunt_Perks-1024x576.png)
*Pictured: Hunter Perks Screen*

# Loadouts and In-Game Economy
*Hunt: Showdown* features a slot-based loadout system, where weapons take either 1, 2, or 3 slots. By default, hunters can carry either 1 3-slot (primary) weapon and 1 1-slot (secondary) weapon or 2 2-slot weapons. There is a perk in the game that allows the hunter to take 1 2-slot weapon alongside a 3-slot weapon. 3-slot weapons include rifles, shotguns, and crossbows. 1-slot weapons include pistols and larger melee weapons like machetes. 2-slot weapons are pistols modified to have large grips for increased range and stability, sawed off shotguns and rifles, and hand crossbows. Hunters are allowed 4 tools, which are items like first aid kits, flashlights, and small melee weapons. They can also carry up to 4 consumables, which are generally grenades, firebombs, and one-time-use quick healing items. The key difference between tools and consumables are that consumables are lost forever on use, whereas all tools are kept between rounds if the hunter successfully extracts.

![Hunt_MyRoster-1024x576.png](/img/user/Images/Hunt_MyRoster-1024x576.png)
*Pictured: Roster and Loadout*

When a new hunter is recruited, they come equipped with two weapons, up to 2 tools, up to 2 consumables, and up to 3 perks, depending on their tier. There are 3 tiers of hunters, with tiers 2 and 3 only being available for recruitment once certain bloodline level requirements are met. The higher tier the hunter is, the wider range of weaponry they can come with, the more tools and consumables they have, and the more perks they have. However, the more expensive their equipment is, the more “hunt dollars” it costs to recruit them. Hunt dollars are the game’s basic currency that is unlocked by playing. Since the game features permadeath, purchasing an expensive character comes with the risk of them being killed before they can make back their cost. An interesting thing about the recruitment system is that hunters can come equipped with weapons and items that the player cannot yet purchase in the store. This has a huge benefit of enticing players to try new weapons more often than they normally would, as well as letting them try out weapons that would otherwise take several hours of gameplay to unlock. This keeps rolling new hunters interesting and fits well into the narrative of recruiting a hunter.

![Hunt_Recruitment-1024x576.png](/img/user/Images/Hunt_Recruitment-1024x576.png)
*Pictured: Recruitment Tab*

# Gameplay Systems
*Hunt: Showdown* is a slow-paced FPS. This slow pace naturally occurs from the importance of audio in the game. Gunshots can be heard from hundreds of meters away and allow players to pinpoint the locations of the shooters. Even running is loud enough to heard from a few dozen meters. The AI enemies in the game are also attracted to noise, which can direct observant squads to careless players’ positions. This naturally encourages a slow and steady approach to gameplay, as well as the use of ambush tactics. The movement through the map to find clues and the boss’ lair before the other players is what keeps the game moving.

![Hunt_GunStats.png](/img/user/Images/Hunt_GunStats.png)
*Pictured: Weapon Stats Comparison*

The game uses weaponry that would be available in the late 19th century. The most common weapons available to players are lever action rifles, primitive bolt-action rifles, revolvers, top-loaded rifles, single-barrel shotguns, and double-barrel shotguns. These weapons all have very slow fire rates or are single-shot weapons. There are exceptions, such as the Bornheim No.3, which is a semi-automatic pistol. Weapons have a multitude of stats with which they are balanced with, these being: Slots (size), cost to purchase, ammo capacity (loaded and unloaded), ammo type, damage, damage type, effective range, rate of fire, handling, reload speed, muzzle velocity, melee damage, and heavy melee damage. There are 5 types of ammo that weapons can use: compact (generally for small arms and lever action rifles), medium (bolt action rifles), long (more powerful bolt-action rifles and top loaded rifles), shotgun, and special (anything else, such as crossbows, a harpoon gun, or guns that take huge rounds). Ammo is refilled by finding either small boxes that are color coded for each ammo type, or by interacting with large ammo crates that can be found around points of interest. Special ammo has the distinction of not being refilled by ammo crates. This has a balancing effect on the powerful weapons that use special ammo (crossbows being something of an exception since you can retrieve bolts). The Nitro Express Rifle, Dolce 96, and Bomb Lance (explosive tipped harpoon gun) are extremely powerful guns that use special ammo. However, their ammo capacity is very low and special ammo is particularly difficult to acquire. This makes these weapons bad for either drawn out combat or quick strings of combat encounters, despite their raw damage. The Dolce 96 and Nitro Express Rifle are also notoriously expensive to equip, making them very high risk, high reward weapons.

![Hunt_Med_Ammo.png](/img/user/Images/Hunt_Med_Ammo.png)
*Pictured: Medium Ammo Box*

There are two different damage types featured in the game, **Rending** and **Blunt**. All guns and crossbows, as well as melee weapons such as axes and knives deal rending damage. Melee weapons such as brass knuckles and sledge hammers, as well as using the melee of most guns deals blunt damage. AI enemies in the game are more vulnerable to one kind of damage or the other. Sledge hammers (blunt) and axes (rending) are scattered around the game. This ensures that players always can temporarily deal one kind of damage or the other in melee form, which is considerably quieter than shooting, provided they are paying attention to their surroundings. Depending on the loadout of the hunter used, melee weapons found in the world are more useful against boss monsters or other AI enemies than anything in their loadout. This is especially true for the spider, which is weak to blunt. There isn’t anything that players can equip in their loadout that deals as much blunt damage as the sledgehammer. The most interesting instance in which blunt vs rending damage comes into play is when dealing with an Immolator, which is a special type of enemy that appears in the world and is characterized by being a burning zombie. Immolators are weak to blunt damage, but when they receive rending damage, they explode into a large ball of fire, become hyper aggressive, and set anything they touch on fire. They are the only enemy in the game that has a special reaction to a specific damage type, and it has very interesting gameplay implications. For instance, if a player spots an Immolator near an enemy hunter, they can shoot the Immolator, which will then charge very quickly at the nearby hunter. It is a great way of taking out enemy hunters without direct line of sight.

![Hunt_shootImmolator.jpg](/img/user/Images/Hunt_shootImmolator.jpg)
*Pictured: Hunter shooting an Immolator enemy*

The game features a stamina system that works a little bit differently than traditional FPS stamina systems. Sprinting does not deplete stamina. The main cost of sprinting in *Hunt: Showdown* is really the noise generated from it rather than stamina. Although, continuous sprinting causes movement speed to gradually decrease until the player takes a rest. The stamina bar in the game is only depleted by using melee attacks. Each weapon, including guns, have a light and heavy melee attack. These are triggered by left clicking and holding left click respectively. Stamina begins to slowly regenerate after a few seconds if the player doesn’t sprint, jump, or melee attack again. While sprinting doesn’t directly decrease stamina, it does keep it from regenerating. The stamina system serves to restrict players from taking on too many enemies on at once with just melee skills. The AI enemies are persistent enough in chasing players such that it is nearly impossible to regenerate stamina while fighting them. This forces the player to either sprint away or fire a gun, which will both reveal their position.

The health system in *Hunt: Showdown* also has some interesting system quirks. Each hunter has either 3 or 4 health bars of varying sizes that total 100 points. Health regenerates up to fill whatever bar it is currently in. However, fully depleted bars can only be refilled by using first aid kits, vitality syringes (both are brought in the hunter’s loadout), or by interacting with med stations found around the map. Health points lost due to burn damage take extra time to be regenerated and cannot be regenerated using normal methods during this time. Another thing to note is that no health can be regenerated while poisoned, which can occur by taking damage from a poison crossbow, a hive enemy, or being near a damaged poison barrel.

![Hunt_2BarsDepleted.jpg](/img/user/Images/Hunt_2BarsDepleted.jpg)
*Pictured: 3 segment health bar with 2 small segments depleted*

![Hunt_BurntHealth.png](/img/user/Images/Hunt_BurntHealth.png)
*Pictured: Burn damage and burnt health segment*

![Hunt_PoisonDMG.jpg](/img/user/Images/Hunt_PoisonDMG.jpg)
*Pictured: Health bar when poisoned*

*Hunt: Showdown* features many interactable objects in the environment that can be used by players for a tactical advantage. There are 3 types of destructible barrels around the map: yellow barrels, red barrels, and green barrels. Yellow barrels are full of oil, and usually surrounded by a pool of oil. Shooting these ignites the oil into an inferno that burns for several seconds. This can be used to block off entranceways and chokepoints. Red barrels are explosive and deal a large amount of explosive damage over a wide radius. These are basically like the standard red barrels that FPS games are known for and are great for taking out enemies in cover who aren’t paying attention to their surroundings. Lastly are the green barrels that explode into a field of poisonous gas. This is especially useful since, while lacking the immediate damage of red barrels, it stops victims from healing and attracts nearby AI monsters to their location. There are also lanterns located around the map, both hanging in the environment and loose on the ground. The ones hanging around the environment cannot be picked up by players, but loose ones can. Hanging lanterns can be shot or hit with a melee weapon, causing an explosion of fire. Picked up lanterns can be thrown for the same effect. Hanging lanterns are often found indoors near doorways, so are a good way of temporarily sealing off entrance routes and otherwise confusing attackers when defending a building. Bear traps are also available within points of interest and can be set down on any suitably flat surface. Bear traps cause a small amount of damage and apply a bleed status effect. Keep in mind that all traps can be activated by the trap setter and their squad mates as well as enemies. Lastly, all major points of interest contain objects that make loud noises, such as self-playing pianos, gramophones, generators, and bells. These are used to both mask position-identifying footsteps and to distract the AI enemies.

The game features various status effects, many of which have already been mentioned. There are 2 forms of damage over time, burning and bleeding. Both require the player to hold ‘F’ to remove the status, and movement is slowed greatly during this process. The key differences between them are that burning restricts healing the burned section of health for a period of time and can be spread to other players and AI enemies via contact. There is also poison, which blurs vision and does not allow healing while in effect. Lastly there is a stamina shot that players can administer to themselves or their squad mates. This keeps stamina from decreasing for 60 seconds.

The last major mechanic available to players in known as “dark sight”. By holding ‘E’, players enter a mode that allows them to see the locations of clues, boss monsters (once all clues for them have been gathered), and bounty-holding players. Clues and boss lairs appear as a blue mist that grows in size and in brightness the closer the player is to their location. Bounty-holding players appear as streaks of lightning in the sky. If a player is holding a bounty, they gain a limited use ability that allows them to see nearby players while in dark sight. These players will appear as orange streaks at in the direction they are from the user. This ability is consumed during the next 5 seconds of dark sight use, so bounty-holding players must begin using dark sight sparingly for maximum benefit.

![Hunt_Clue.jpg](/img/user/Images/Hunt_Clue.jpg)
*A hunter interacting with a clue. When taken, the center of a clue is changed to a dark hole that signifies to other hunters that the clue has already been visited.*

![Hunt_DarkSight.jpg](/img/user/Images/Hunt_DarkSight.jpg)
*Dark sight being used*

![Hunt_BountyHolderDarkSight-1024x576.jpg](/img/user/Images/Hunt_BountyHolderDarkSight-1024x576.jpg)
*Seeing a bounty-holding player in dark sight*

![Hunt_EnhancedDarkSight.jpg](/img/user/Images/Hunt_EnhancedDarkSight.jpg)
*Enhanced Dark Sight for a bounty-holding player. Another player is visible through a wall.*

# Anti-Camping Systems
The developers of *Hunt: Showdown* have described camping as an issue in this game. The weapons and clue system certainly encourage players to use ambush tactics and wait for other squads to come to them, rather than fighting targets which can leave them vulnerable and make it difficult to hear approaching enemies. This can cause long periods of waiting for these squads, which is not particularly engaging, especially after having played several rounds. For clues, the particles that stream from the clue will turn dark red and a loud ominous sound will be emitted when two opposing squads are close enough to it at the same time. At points of interest where a target is located, players will hear whispering upon entering. There are two circles that are centered in the middle of the boss’ lair, one with a radius of 40 meters and another with a radius of 80 meters. When a squad enters the 80m circle, they will hear calm whispering. If there is a hostile squad within the 40-meter circle, the squad within 80m will hear aggressive whispering and receive a red ping on their screen. Squads within 40m always hear aggressive whispering and receive a red ping. This mechanic is intended to stop squads from camping entrance-ways into boss lairs, since a 40m radius from the center of the lair will extend to just beyond the walls of the lair.

# Enemy Types
There are multiple different enemy types in *Hunt: Showdown*, each able to kill a player who is not paying attention. AI enemies can also be utilized to detect enemy hunters’ positions and can even be alerted into pursuing enemy hunters. All non-boss enemies except for the immolator and meathead are weak to fire.

## Grunts
Grunts are the basic enemy type in hunt. They can be found either unarmed or armed with bladed weapons or torches. They can be found in all areas of the map, either shambling around or mimicking dead bodies. They respond to sound and to direct line of sight and will pursue targets until they are outside of a limited range. Their maximum movement speed ranges from slightly slower to equal to a hunter’s sprint speed. Unarmed attacks from them deal blunt damage, when armed with blades they deal rending damage and apply bleed, and when armed with torches they deal blunt damage and apply burning. Grunts are weak to rending attacks and can be dispatched with one heavy melee attack from the basic knife.

![Hunt_Grunt-1024x530.jpg](/img/user/Images/Hunt_Grunt-1024x530.jpg)
*Grunt Enemy*

## Armored
Armored are large zombies characterized by crystalized armor plating. They are incredibly strong against all firearms, but only take a few hits to be killed with melee weapons. They are extremely weak to fire and die in a few seconds once burned. They deal high melee damage and will charge at a speed equal to hunter’s max sprint speed when alerted. A notable ability of armored is that they are the only enemy type that will break down doors to pursue players.

![Hunt_Armored.jpg](/img/user/Images/Hunt_Armored.jpg)
*Armored enemy type*

## Hive
Hives are zombies characterized by the ability to sent out a swarm of insects when alerted that poison targets and deal constant damage while the hive remains alive. Upon the hive’s death, the swarm dissipates, but the poison status remains for a few more seconds. The hive emits loud, distinctive shrieks that alerts careful players to its location before it is within range. Unlike other enemies in the game, the hive’s head is located to the side of her body, which makes aiming for critical headshots slightly more difficult. They are a particularly dangerous enemy due to the ability to send their swarms through cracks in walls and over cover. They also have the distinction of being the only ranged common enemy type, and thus are the only enemy type that can attack hunters at different elevations than themselves.

![Hunt_Hive.png](/img/user/Images/Hunt_Hive.png)
*Hive enemy type*

## Meathead
Meatheads are a huge enemy with probably the most interesting AI in the game. They are blind due to a lack of a head, but they ‘sense’ hunters with 3 monstrous leeches that they send out from their body. Once these leeches detect a hunter, the meathead charges at them and deals massive damage on hit. While their sensory range is short, they will also be attracted at greater distances to poisoned hunters. This offers the game’s most interesting interplay between AI enemy types. Hive enemies can become much more deadly when paired with a meathead, since the poison applied from their attacks will attract the meathead to their victim’s position. The meathead can sense the hunter while they remain poisoned, so it becomes much more difficult to shake them off. They are weak to slashing damage (rending melee), although it is very dangerous to be within melee range of a meathead due their high damage output and charge. They are more resistant to fire damage than other AI enemies, and will actively avoid inflamed areas after touching fire. The only way to quickly dispatch them is using explosives, which have the cost of being incredibly loud. Guns are also more ineffectual due to their being no critical point, since the meathead lacks a head (despite the name suggesting otherwise). Unlike the other non-boss enemy types, meatheads are only found in or immediately around points of interest.

![Hunt_MeatHead.jpg](/img/user/Images/Hunt_MeatHead.jpg)
*Meathead enemy type*

## Immolator
I’ve discussed the main points of the immolator in the damage types section of this analysis, so I won’t go in depth into them again.

![Hunt_Immolator.jpg](/img/user/Images/Hunt_Immolator.jpg)
*Immolator enemy type*

## Hellhounds
Hellhounds are one of two non-humanoid basic enemies in the game. They are large canines that are generally found in pacts of up to 5 around the world map and outside of points of interest. Their spawning is somewhat special in that they are never found inside of compounds. They are much faster than players, and thus cannot be outrun. Some of them wear armored collars that can deflect a melee strike, which the only instance of AI attack deflection that I have come across in the game. Hellhounds charge and jump at targets to bite them, causing large chunks of damage and applying bleed.

![Hunt_Hellhounds.png](/img/user/Images/Hunt_Hellhounds.png)
*Hellhound enemy type*

## Water Devils
According to dev blogs, during beta testing of the game pond areas of the game were deemed too safe. Despite greatly slowing movement speed and offering little in the way of cover, the respite from all AI enemies (except for nearby hives) decreased the tension too much. To rectify this situation water devils were added. Water devils are a mass of tentacles and spikes that will charge at any hunter (or ground dwelling AI enemy) that wanders within their range. They deal intermittent damage while a hunter is within their damage range and apply bleed. When shot they disperse, allowing safe passage across their waters, but will return after a few seconds.

![Hunt_WaterDevil-1024x646.jpg](/img/user/Images/Hunt_WaterDevil-1024x646.jpg)
*Water Devil enemy type*

# Targets (Bosses)
Targets are the main objective of the bounty hunt game mode in _Hunt: Showdown_. All squads compete to locate and defeat a target first, defend the body during the banishing phase, retrieve the bounty tokens from the banished body and extract off the map. There are 3 different targets, and 1 or 2 can spawn when playing in 2-man squads. Up to 3 can spawn when playing with 3-man squads.

## The Spider
The spider is a target characterized by extremely quick, erratic movements, and powerful poison attacks. It is weak to blunt damage, so players are encouraged to take it out with sledgehammers for the best sound / damage per second ratio. The spider has very special movement, since it can run on walls and ceilings, making it difficult to track during combat. Fire is also effective against it, since it takes no special action to avoid fire, and its quick movement often has it run through inflamed areas multiple times before the flames dissipate. The spider also enters a frenzy mode when it is below half health, increasing its movement speed and damage.

![Hunt_Spider.jpg](/img/user/Images/Hunt_Spider.jpg)
*The Spider Target*

## The Assassin
The Assassin is characterized as a tall slender figure that can dissipate into a cloud of insects and reform as locations of its choosing. It will also create clones of itself to confuse players. The assassin has a ranged ability that splashes around it’s point of impact and can poison targets. While the assassin can deal poison damage, it is also weak to poison (as well as fire). Players can throw poison bombs, which create a cloud of poison that lasts for 5 minutes to passively damage it. Unlike other humanoid enemies in the game, it is alluded to that the Assassin’s critical point is its chest rather than its head.

![Hunt_Assassin-1024x576.jpg](/img/user/Images/Hunt_Assassin-1024x576.jpg)
*The Assassin Target*

## The Butcher
The final target currently in the game is The Butcher. The Butcher is a monstrous humanoid with the head of a pig and a flaming meat hook. He can swing his hook at a distance and in melee range, both dealing huge amounts of damage and applying fire. His head can be shot off, which puts him in a frenzy mode, increasing his speed to that of a hunter’s maximum sprint speed. In this mode, he leaves patches of fire behind him as well, making melee attacks more difficult to land against him. He is weak to rending damage and explosives.

![Hunt_Butcher.jpg](/img/user/Images/Hunt_Butcher.jpg)
*The Butcher Target*

# My Ideas for Improvements
I think that there is an issue of players exploiting the ability to extract early in order to power level hunters with little risk. It is not entirely uncommon to have games where almost no gunshots are heard (most guns can be heard even from the furthest possible point from their origin), and the targets are uncontested. During games like this, I have even found clues that have been taken. So, what is happening? There is a chance that players are killed by AI enemies, but it is unlikely for both members of a squad to be killed by AI enemies, and the revival mechanic offers mercy for a single player having a slip up. I hypothesize that the permadeath mechanic encourages certain types of players to simply try to kill a few AI enemies for the hunter XP, take 1 or 2 clues (again, for the XP they offer) and then quickly extract before any risk comes to them. I think in order to introduce appropriate to this playstyle, there should be a minimum amount of time that must pass before the extraction points become available. On top of this, I think that there should be an action that must be taken that occupies a player. The extraction points have narrative flavor, such as a boat in a harbor, or a horse and carriage on a road. It could create more tension if a squad member had interacted with these objects, like starting the boat or readying the carriage for the extraction to occur. These interactions could also generate noise, which gives a final alert to nearby squads that somebody is extracting. As it exists right now, squad members are just required to both stand within a range of the point and wait for a timer to tick down.

As another possible improvement to the game, I think a world enemy that can scale walls and/or ladders should be introduced. Currently, only the hive enemy type has the possibility of threatening hunters at different elevations. High points, such as roofs and ledges feel incredibly safe compared to most other places in the game. There are enough areas in compounds that are only accessible via ladder, that I think a wall/ladder scaling enemy would add some much-needed extra tension to sniper’s nests.

Lastly, I think that basic enemies should be able to move through broken windows at ground level, if not be able to break windows themselves. Players shooting from buildings at distances that cause enemy aggro will have enemies gather near the windows and just stare at them. I feel like this is downright immersion breaking considering the levels of aggression the enemies will show otherwise. A simple wooden door or small ledge of a window offers respite from the AI enemies (with the exception of the armored who can break doors and the hive who can send swarms through windows and cracks in walls).