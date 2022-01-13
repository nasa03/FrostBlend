![[FrostBlendLogoRaster.png|256]]

## Welcome to the FrostBlend manual.
This manual assumes you have basic knowledge of Blender and 3D rendering techniques.

---
### Games
- Star Wars Battlefront II
	- [[SWBF2 General Information|General Information]]
	- [[UBER|UBER Shader]]
	- [[RSSSAO-RSSSS|RSSSAO/RSSSS Shader]]
	- [[Hair|Hair Shader]]
	- [[Eyes|Eyes Shader]]
	- [[Droid|Droid Shader]]
	- [[Markings Var.1|Markings Var.1 Shader]]
	- [[Markings Var.2|Markings Var.2 Shader]]
	- [[Kylo|Kylo Shader]]

- Star Wars Battlefront
	- WIP(A lot can be set up with SWBF2 shaders)

- Star Wars Squadrons
	- WIP(Mostly uses SWBF2 shaders)

- Battlefield 1
	 - WIP

- Battlefield V
	- WIP

---
### Using the groups
_(This covers basic usage for all games)_

Use of the groups is quite simple.
![[Pasted image 20211231164852.png]]
First go into append and select the blend file for the game you want the setups for.
![[Pasted image 20211231164948.png]]
In this case we go to SWBF2_Materials and select NodeTree when inside it.
![[Pasted image 20211231165038.png]]
Select the groups you wish to append to your current blend file.
The ones not highlighted here are shared and do not need to be appended. Lists of shared groups will change per game and as such will be mentioned in that games general information note.
![[Pasted image 20211231165234.png]]
When appended, you can make a new material for the mesh you want to set up and delete the Principled BSDF it creates. Then follow the screenshot to add one of the main shaders.
Main ones will always be prefixed with the game name.