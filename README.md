# Icarus_Mods

9/20/22

Added Water_Wheel mod. Allows you to craft in character a Water wheel to generate electricity. Just need water.


9/18/22 Updated mods

New mods added.
Durability Increases Items Durability
Camera_Distance increases the distance you can go in camera mode. Great for those far away shots.
The rest should be self explanatory.

9/4/22 Added new mods:
Have been working in blender to customize the 3d models in game.

Custom_Puck_Lights

These are new Items I created that are LED Lights and require no power. They are custom edited Models and BP. Contains a Wall Puck light, Ceiling light and a floor light. I changed these to a Workshop Item instead of craftable. It replaces the Meta Oxygen Gel with a Crate of 4 of each lights and a usable crate. Sometimes its nice to just put a light on things :)

Mini_Generator

This is a modded version of the biofuel generator in game. Converts it to the size of a regular honda type generator and is now stackable So you can place it right on top of the item it is going to power or stack them in the corner for more power on the grid.

Large_Statues

I edited the 3d models of the stone statues in the game(Elephant, deer, Wooden Deer, Caveworm,and a Life sized caveworm) and created custom Icons, and items to craft them. the stone ones are 50 stone and 100 for the lifesized caveworm. The wooden one is 50 wood.


7/4/22 Description of mods:

The following are all UASSET file mods so they are compatible with all other mods:

Deer_Statue_Large_Mod: This changed the little deer statue into a very large statue. Will still be small until actualy placed.

Building_Height_Mod: This adds more stability to concrete, stone, iron, wood. Allowing you to build higher without it crumbling down.

50_Seconds_OutofBounds: Changed the timer from 20 seconds to 50 seconds when going out of bounds

700_Jump: Changes the character jump height to 700. This allows you to jump from first floor to second floor.

800_Jump: Changes jump to 800 for those that want a little more height.

900_Jump: Changes height for more extreme needs. Does make it hard to jump into doors ect.

MiningSpeed: Speeds up the time to mine things to 1 second.

CompoundBow_Kryptic_Camo: Adds green Kryptic camo to the compound bow.

Workshop_Armor_Kryptic_Camo: Adds Green Kryptic Camo to first set of Workshop Armor.

These Mods moddify UASSET files but also contain Json files so compatibility may change.

Weapons_Mod: This gives you 2 new handguns, 3 assault rifles and a sniper rifle. Also the sniper rifle takes a larger bullet. They are all tier 4 so require the Fabricator bench to craft. The sniper rifle does about 2x the damage of other rifles and is the only one that requires composites to craft. 

Easy_Cave: Prevents worms from spawning and automaticly give your the Dehumidifier buff in all caves.
This mod modifies the following files:
D_AISetup.json
D_ModifierStates.json

Easy_Lights: This is a must have. Changed lights,heater,airconditioner to not require power! Also allows lights to be placed on top of other placed items. Changed wall light mesh to be half the size once placed. This is for placing it under cabinets ect.. Also looks better when placed on wall at base to give floor lighting.
This Mod modifies the following file:
D_DeployableSetup.json

ThorHammer: allows access to thors hammer to fly around making travel much quicker. The right mouse button will hold you in air at current height. This is so helpfull when building tall bridges to get the supports right.
This mod modifies the following file:
D_ItemsStatic.json

============ Older mods I no longer update, Left for people to see how they were done ==============

Backpack_Kryptic_Camo: They removed this backpack and added thier own camo pack.

Low_Gravity Mods: These Change the gravity in Icarus. They are fun to mess around but useless to try and play the game so I have not updated them.

Friendly_Wolf: Adds a large Black wolf to the game that is friendly to the player but runs around killing all other animals.

Explosive_Arrows: Adds explosive tip to all types of arrows. Stopped updating as they added explosive arrows to the game.


6/11/22 Updated mod to week 27.

5/28/22 Removed Test version of weapons mod. Updated Mods to week 25

5/23/22 Added a test version of weapons mods so you can test them out without grinding to tier 4 and getting composites. Also includes Thor's hammer to help get around. 

5/22/22 Updated mods to week 24. Added new weapons mod. This mod adds 2 new handguns,3 assault rifles, and a sniper rifle. They are all tier 4 items. The weapons mod uses D_ProcessorRecipes, D_ItemsStatic, D_ItemTemplate, D_AmmoTypes, D_FirearmData, D_Actionable, D_Ballistic, D_Itemable, D_Meshable. So unfortunately will prob be incompatible with other mods. If another mod creator wishes to add all or one of these weapons to their mod  they are free to do so. Enjoy

-No custom animations so I had to get creative with polishing them and getting them to reload/aim the right way. 

-Sniper and 1 assault rifle use custom overlay for the binoc to resemble looking through a scope. Works nicely.

-Hand guns use same ammo as pistol doing same damage but are semi-auto with 10 round mag. Reloads the 10 rounds in one animation. 

-2 assault rifles use iron sights and all 3 rifles use 10 round mag but have to be loaded 1 round at a time as there are no mag reload animations for rifles.

-Sniper rifle uses sniper ammo that does more damage than any other round but also is more difficult to craft. 1 shot then reload.

5/6/22  Updated Mods to latest game data. Added More variety for the jump mods. The default jump height is 525. My old high jump was 900 so you now have options.

4/28/22 Uploaded new mods. Use gravity/jump mods with caution as a fall from high may kill! Also added Friendly wolf mod. They will attack and kill anything in the wild. They have been bread to be friendly with humans but dont attack or they will turn!

4/14/22 Updated explosive Arrows for week 19.

4/8/22 Updated Explosive Arrows for week 18. Kryptic camo mod does not need any update.

4/6/22 Added New Kryptic camo mod. 
This new camo mod should be compatible with all other mods unless the mod changes these same item textures. I dont think any other mods change textures so you should be fine. Also this mod DOES NOT CHANGE the gameplay in any way. It only changes the look of the workshop armor, Compound Bow, Recurve bow, and the Archers Backpack.
Just select the Kryptic_Camo_Mod_V1_P.pak file for the items you want to be camo from the files section and place in mods folder:
\Program Files (x86)\Steam\steamapps\common\Icarus\Icarus\Content\Paks\mods
if that folder doesnt exist, just create it. You can add all of them if you wish. I had to break them up do to file size limits.


Explosive Arrows MOD. This Mod allows you to take any arrow above stone and craft it into an explosive arrow. The base damage is the same as the arrow you start with. The explosion does damage depending on how close to the target it explodes. Any animal that is not killed will become slowed from the explosion. KillCam is disabled with these new arrows as wounds are inflicted from the explosion. All base stats of each arrow remain the same as the original.

To craft an explosive arrow you must have an arrow to start with. The minimum is bone arrow. Items needed to craft are the original arrow plus 1 leather, 4 gunpowder, and 2 epoxy. You craft these in your character crafting near bottom of your list of craftable items. In order to craft an explosive version you must have the original version unlocked in blueprints. Once crafted you will see the same type arrow but with and explosion displayed next to the arrow icon. This same Icon is used in the arrow select screen when using your bow. It also says in the description that the arrow is explosive. These arrows are new items so they will not stack with regular arrows.

To install just add the PAK file to your mods folder in your Icarus installation directory.

I have included the source folders for adding these arrows to other mods. They are 6 all new arrows so they will not effect any changes you have made to existing ones, or any changes to other items. You will just have to insert the json to your json files and add the additional BP and Assets folders and files before compiling to PAK file.
