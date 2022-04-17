# EU4-The-Colleges
My first attempt at modding Europa Universalis IV. We are going to try to add T20 colleges as Great Projects (Monuments) in the game.

## Resources
1. Modding in general
	1. Initializing the mod -- https://eu4.paradoxwikis.com/Mod_structure#.mod_file
		1. Put the folder in the relevant location
			```
			Windows: Documents\Paradox Interactive\Europa Universalis IV\mod
			Linux: ~/.local/share/Paradox Interactive/Europa Universalis IV/mod
			Mac OS: ~/Documents/Paradox Interactive/Europa Universalis IV/mod
			```
		2. Create a .mod file in the same root directory as the mod. Insert the following boiler:
			```
			name = "name"
			path = "mod/folder_name"
			supported_version = "latest_version (ex: 1.33)"
			```
		3. You can also add optional tags if uploading to steam with the following addendums in the same file
			```
			picture = "picture.jpg"
			tags = {
				"tag1"
				"tag2"
			}
			```
			- Note that '''picture.jpg''' should be located in the '''mod/folder_name''' directory.
				- I HAVE NOT GOT THIS TO WORK YET
		4. Create a '''descriptor.mod''' file in '''mod/folder_name''' with the same contents as the mod file created in step 2, minus the '''path=""'''.
		5.
2. Modding Monuments
	1. https://eu4.paradoxwikis.com/Great_project_modding

## University Specific Resources
1. MIT
	1. Build Date -- 1861-04-10: https://libraries.mit.edu/mithistory/mit-facts/
	2. Build Time -- 48 Months: https://libraries.mit.edu/mithistory/mit-facts/ | From the fact classes began 4 years after chartering.
	3.

## Misc Resources
1. Markdown Guide -- https://www.markdownguide.org/basic-syntax/
