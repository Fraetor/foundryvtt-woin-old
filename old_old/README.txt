This is a sandbox system and world for the WOIN RPG.

It includes a modified version of the sandbox system, which means it does not work if you use an existing version of sandbox with the world. This should not cause much trouble though, as this version of sandbox should work with any other existing worlds that were created for sandbox on Foundry V9.

The two folders in this zip file should be copied into your foundrydata/Data folder, which is where you put modules, images for your games, and other data you want foundry to have access to. They will match the existinig folder names for modules and worlds, but should not overwrite anything as long as you do not have an existing version of sandbox or a world named woin-template.

Once you have done this, start up foundry and you should be able to use the WOIN Template world immediately, although I recommend that instead you first copy the woin-template folder inside your worlds folder and update the world.json file to match the new name you give it. This allows you to play in a world without affecting the original template, which will make it easy if you need to start a second game in parallel. See the sandbox documentation if you would like help migrating homebrew content made in one of your worlds to another.


The system currently has all the content from the OLD manual, and basic support for all the alternate magic systems presented within that book including elements of magic, rituals, fatigue, and others. It also contains a small subset of the Spell Paths supplement from EONS.

In order to create a character, make an actor and select the _pc_charsheet_template from the dropdown. This will populate the character sheet with an empty character. You can now drop in a race, which will automatically apply the exploits from that race. You must manually add skills and attribute points from races and careers. Careers can also be dropped in. Their exploits are all available in an organized manner in the items panel. In order to set up magic, the GM must navigate to the GM Info tab of the character sheet and select a supernatural type (magic, chi, or psionics) and a magic system from the dropdown. If the character has at least 1 point in the supernatural attribute, an extra tab will appear in their character sheet with information about spellcasting.


To create an NPC, make an actor and select the _npc_charsheet_template from the dropdown. Most values on the sheet can simply be edited manually if you wish.
To use the monster builder rules from the back of the book, simply set the MDP of the creature and then move to the Hidden tab of the NPC. Find the role you want for the NPC from the items side panel and drop it into the character sheet. Select if the character will use the supernatural attribute and what their sentience will be, and then click the book icon which will apply it. Now select some exploits and apply them to the character sheet. You're done!


Homebrew content can be added to the game, but unfortunately the systems used are too complex to explain on short notice. If you become familiar with sandbox you may be able to figure out how to do things, otherwise get into contact with the author of this sandbox system at srasu@srasu.org and I will attempt to help in any way I can.
