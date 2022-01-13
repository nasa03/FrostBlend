![[Pasted image 20211231160400.png]]
## Markings Var.2
Used for meshes using the shaders `SS_CharactersPreset_CloneTrooperMarkings_T41` and `SS_CharactersPreset_CloneTrooperMarkings_02`

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **Armour Colour**
	- Sets the colour of whatever is masked on the blue channel of AOSL.
- **Marking Mask 1**
	- Mask for marking layer 1.
- **Marking Col 1**
	- Colour of marking layer 1.
- **Marking Mask 2**
	- Mask for marking layer 2. Added on top of 1.
- **Marking Col 2**
	- Colour of marking layer 2.
- **Grunge Mask**
	- Texture input for a greyscale tiled weathering texture to add scratches to the markings. Set to 1 if no input.
- **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB.
- **Invert Smoothness**
	- Set to 1 to use the blue channel of NM as a mask for a matte grey material(Var.1 Behavior) or 0 to use the blue channel as metalness. Both apply on top of markings and armour colour.
- **Base Specularity**
	- Sets the base specular value on the Principled BSDF inside.
- **Reflectance**
	- This is added on top of the base specularity. Leave at 0.5 if there is no texture present.
 - **AOSL**
	- AOSL texture input.
- **AO Strength**
	- Sets the strength of the AO effect.
- **NM**
	- NM texture input.
- **Mask Samples 1,2,3**
	- Inputs for slice values. Only the green channel is used here for easy use with AOSL textures.
- **Detail 1,2,3**
	- Texture inputs for detail map tiling textures. Leave at 0.5,0.5,0 if no input.
- **Detail Normal Intensity 1,2,3**
	- Sets the strength of the normals added to the base normals by detail textures.
- **Detail Smoothness Intensity 1,2,3**
	- Sets the strength of the smoothness added to the base smoothness by detail textures.
