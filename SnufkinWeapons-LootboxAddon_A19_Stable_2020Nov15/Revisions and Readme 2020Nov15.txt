===================================================================
15th of November 2020 - Snufkin Weapons Lootbox Addon (A19 - Stable)
===================================================================

Here are a few changes which update functionality of the A18 build by replacing old values with their latest equivelant where possible.

-----------------
1. Railgun Ticket
-----------------
- items.xml
item name="Railgun Ticket"

Commented out the following property to a new value as the previous value has become obsolete and will not present an icon.

From
<!--property name="CustomIcon" value="gunMR10"/-->
To
<property name="CustomIcon" value="gunRifleT2MarksmanRifle"/>

The Railgun shares a model with the Marksman Rifle and offers a similar function.
----------------------
2. Hyperblaster Ticket
----------------------
- items.xml
item name="Hyperblaster Ticket"

Commented out the following property to a new value as the previous value has been updated.

From
<!--property name="CustomIcon" value="gunBlunderbuss"/-->
To
<property name="CustomIcon" value="gunShotgunT0Blunderbuss"/>

============
INSTALLATION
============
For players and server hosts who have never installed a mod before.
If you've never installed a mod before it is necessary to create a mod folder in the main directory or in an area suggested by your server host if they have modified the installation. Simply make a new folder called Mods (with a capital M to reflect standard nomenclature). If you drag the mod folder directly out of the zipped file it can be placed directly into the Mods folder and the game will look in there as you launch your World. If you allow your unzip function to extract the folder, it may make another unnecessary folder and place the mod inside it. This will not be recognised by the game/server if you place it in the Mods folder like this. Please take it out of the extra folder level. The top layer will be a single folder and in the second layer you will see a ModInfo.xml file with or without additional folders depending on the mod. This will become elementary once you've launched a few mods.

Does this Mod need to be installed in the server/client host? = YES
Do players also need to install this Mod? = NO

The magic of this mod is that is only needs to be installed in the server/person who has launched the main environment that others join. It is a technical work of art. Enjoy.

=======
CREDITS
=======
Apart from Snufkin who created this mod, Slawa, oakraven, ShoudenKalferas have been supporting the base mod updates in the background. In addition, players and server hosts have been fundamental to development with their testing and feedback.

https://community.7daystodie.com/topic/18229-snufkins-server-side-weapons/