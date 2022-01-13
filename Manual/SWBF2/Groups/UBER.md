![[Pasted image 20211231151942.png|350]]
## UBER
The main material used for most assets in the game. Supports just about any texture packing, detail maps and emmision.

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB.
- **Base Specularity**
	- Sets the base specular value on the Principled BSDF inside.
- **Reflectance**
	- This is added on top of the base specularity. Leave at 0.5 if there is no texture present.
- **Emmision Colour**
	- Sets the emmision colour of the material.
- **Emmision Strength**
	- Controls how bright emmision is.
- **Emmision Mask**
	- Masks Emmision. Set to 0 for no emmision, 1 for complete emmisiveness.
- **Emmision Mode**
	- Set to 0 to add the emmision to the base shading, 1 to replace the base shading entirely.
- **Alpha**
	- How opaque the material is.
- **AO**
	- Ambient Occlusion, adds fake shadows.
- **AO Strength**
	- Sets the strength of the AO effect.
- **Slice**
	- Input for a slice texture.
- **Normal X, Y**
	- Sets the X and Y values of the materials normals. If no input is avilable leave at 0.5 on both or shading will break.
- **Metalness**
	- Makes the material more or less metallic in appearance.
- **Mask Samples 1,2,3**
	- Inputs for slice values. Only the green channel is used here for easy use with AOSL textures.
- **Detail 1,2,3**
	- Texture inputs for detail map tiling textures. Leave at 0.5,0.5,0 if no input.
- **Detail Normal Intensity 1,2,3**
	- Sets the strength of the normals added to the base normals by detail textures.
- **Detail Smoothness Intensity 1,2,3**
	- Sets the strength of the smoothness added to the base smoothness by detail textures.

