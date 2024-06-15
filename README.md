# Endless Legend Civilizations
An Endless Legend inspired Unciv mod.

### Possible Roadmap (most likely in that order)
Adding unique gameplay elements to factions

Further balancing

Finding icons

Endless Legend minor factions as city states

Auriga custom map

# Credits
Faction icons and Setseke icon come from Endless Legend

# Changelog
### v0.6 Funding Science
Forgotten and their "Science Phobic" trait is done. Similar to Broken Lords, they don't generate science at all. Instead they can buy technologies with gold. Or more preferably, steal from other civilizations as they start with 1 Spy from the game start. Every source of Science (except for trade agreements and City States) is converted to Gold for them. This also means those science buildings can give obscene amount of gold due to their relative bonuses (so expect relevant changes later on)

Forgotten:
- Unique Ability revamped.
- Buyable technology buildings added
- Predatore removed
- Myst is now a scout replacement that is fast, invisible, has extra sight and ignores enemy borders. Gotta find that capital fast for your spy!
- Oxford University replaced with Caudata Sanctuary, which gives another spy and makes spies start with 1 extra level.

Broken Lords
- Conditionals on uniques changed a bit

### v0.5 Shifting Uniques
Inspiration came while working on the Forgotten. This is the result.

Allayi now has a brand new "Shifting" mechanic. They start the game in Light Season, which gives them small growth, culture and gold bonus. Each turn, they also gain one Aurigan Pearl.
When they have at least 5 pearls, can enter a Dark Season which consumes their Aurigan Pearls every turn. During Dark Season, they lose the Light Season bonuses but gain production bonus, military strength and movement speed. They can prematurely end the Dark Season or keep it going until they run out of pearls. By using the Dark Season in a timely manner, you can move settlers faster or speed up wonder construction or buff your armies for war.

AI ignores the pearl mechanic and enters Dark Season when at war. This can make them kinda dangerous at warfare but declaring war also removes their culture and growth bonus, which they will benefit a lot for their culture victory.

Allayi:
- Unique Ability revamped. Now has two different sets of bonuses for Light and Dark Season
- Shift between seasons by spending Allayi exclusive resource, Aurigan Pearls
- Garth of Allayi now doubles the bonuses of Light Season in the city
- Skyfin gains extra sight (Its a giant flying manta ray thingie)

### v0.4.2
A generic bugfix

Necrophages:
- Cadaver units should properly upgrade only when you have the required tech now
- Feeding the Hive should only be available if you have enough Cadavers now

Forgotten:
- some preliminary work on their upcoming update. You should be able to play in Ancient and Classical era with little problem

### v0.4.1 unshackling the AI
After an epiphany, I realised I can use a bunch of conditionals so certain mechanics would impact human and AI players different. This ensures players will play with the intended mechanics while AI will play them more like a normal civ. This also opens up forced single city empires.

Broken Lords:
- AI no longer has the mechanics related to growth nullification. They no longer build/buy populations.
- Most gold bonuses are only for human players now

Necrophages:
- AI automatically uses Cadavers to buy a population in a random city.

### v0.4 Still Hungry
This update takes a look at the bug boys and gives them their "necromancy" mechanic.

Necrophages have a new unique resource, Cadavers, which is only available to them (seriously, other civs wont even know it exists). They gain one Cadaver for every unit they kill. They can use this Cadavers for two cool things. First is creating a population in a city just like in Endless Legend. Second is to buy Cadaver units, which is like having Battleborns in Endless Legend. They also get "Demanding Gods" action, which is a temporary building you can buy by sacrificing a population and negate unhappiness from population in that city for 10 turns. Now you can be the wild warmongerer from the getgo if you know how to feed.

Necrodrone is replaced with Proliferator, as a ranged unit synergizes with the Cadaver units better. As with the previous update AI has no idea how to use the Cadavers (I've seen him sit on 70+ cadavers on a winning game) but afaik it doesn't kill all its cities with Demanding Gods too so faction uniques are player oriented with this one too.

- We now have a Preview image!
  
Necrophages:
- New unique resource called Cadavers, only available and visible for Necrophages
- Gain Cadavers by killing military units
- Spend 4 Cadavers to buy warrior line of units. Cadaver units have half maintenance cost and upgrade for free.
- Spend 4 Cadavers to create a population in a city - Feed the Hive
- Can Sacrifice a population to negate population unhappiness of a city for 10 turns - Demanding Gods
- Generic strength bonus at war is removed.
- Proliferate promotion is removed from ranged units
- All military units start with Recycler promotion, which gives some flanking bonus (and make the Cadaver mechanic possible)
- Feeding Pits also has Culture cost reduction natural border growth now.
- Necrodrones removed.
- Made Proliferators a replacement for Composite Bowman.
  
Vaulters:
- Dawn Officer rejects being French and becoems Vaulter instead.


### v0.3 "Broken" Lords
Main change in this version is the implementation of Broken Lords "buy your population" mechanic. 

Broken Lords no longer gain any food at all. They won't have any natural growth or starvation. Instead, every source of food (execpt for maritime city-states) have been turned into gold with nation unique. They have buildings that gives 1 pop to the city they are build. These buildings have increasing cost based on existing population of the city and autodelete themself so any source of pop loss (nukes or conquered city) is taken into account.

Two issues with the mechanic: first is that AI in no way knows what to do so it will sit on 1 population cities and have abyssmal yields all around. Second is that putting an extra set of buildings to build in every city slows down your normal production queues, which is crucial in early game. To combat that a bit, first 10 population costs are lower than they would normally be. Expect balancing on that later on, with increased costs for later populations.

Broken Lords:
- Unique Ability replaced.
- Buildable population mechanic added
- Altar of Channeling removed (just more gold is boring)
- Stalwarts added as Spearman replacement

### v0.2.1
Some prefered victory types are changed

Necrophage:
- Removed food buff/debuff from Necrophage as they didn't add a lot to their gameplay.
- Increased Necrophage at war bonus to 15%.
- Removed annexed city restriction form Feeding Pits.
- Made Necrodrone a replacement for Pikemen instead of Scout.
  
Ardent Mages:
- Gains 3 great persons when entering different eras now.
- 10% strength within 2 tiles of great improvement added.
- Added Ateshi Zealot as Canon replacement.
- Nonmechanical changes to reduce pillar related stuff showing up on nation screen.
  
Roving Clans:
- Setseke slightly cheaper and gives 1 pop to random city.
  
Kapaku:
- Added Geomancer as Gatling Gun replacement.

### v0.2    re-release
mod returns after 2 years!

Unique Abilities, Units and Buildings are changed a bit.

### v0.1.1	
fixed Vaulter UA name

city names match official map now

### v0.1	initial release