![[Pasted image 20211231161410.png]]
## Kylo
Used for meshes using the shader `Shaders/Presets/SS_CharactersPreset_WalrusCreature`

---
## Inputs

- **CS Colour**
	- CS texture colour input.
- **CS Alpha**
	- CS texture alpha input.
- **NM**
	- NM texture input.
- **NM Alpha**
	- NM texture alpha input.
- **AO Strength**
	- Sets the strength of the AO effect.
- **DMS Colour**
	- DMS texture colour input.
- **DMS Alpha**
	- DMS texture alpha input
- **Subsurface Radius**
	- How far rays of light will travel through the object. This works as an RGB value ie. 1,0,0 will allow only red light to pass through far through the object.
- **Subsurface Colour**
	- Colour to overlay on top of the base colour for Subsurface.
- **Detail 1,2**
	- Texture inputs for detail map tiling textures. Leave at 0.5,0.5,0 if no input.
- **Detail Normal Intensity 1,2**
	- Sets the strength of the normals added to the base normals by detail textures.
- **Detail Smoothness Intensity 1,2**
	- Sets the strength of the smoothness added to the base smoothness by detail textures.
