![[Pasted image 20211231155243.png]]
## Markings Var.1
Used for meshes using the shader `SS_CharactersPreset_CloneTrooperMarkings`

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **Marking Mask 1**
	- Mask for marking layer 1.
- **Marking Col 1**
	- Colour of marking layer 1.
- **Marking Mask 2**
	- Mask for marking layer 2. Added on top of 1.
- **Marking Col 2**
	- Colour of marking layer 2.
- **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB.
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
