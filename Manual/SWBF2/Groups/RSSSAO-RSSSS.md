![[Pasted image 20211231153958.png]]
## RSSSAO/RSSSS
Primarily used for skin materials.

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **RSSSAO**
	- RSSSAO texture input.
- **RSSSS**
	- RSSSS texture input.
- **Subsurface Colour**
	- Colour to overlay on top of the base colour for Subsurface.
- **Subsurface Radius**
	- How far rays of light will travel through the object. This works as an RGB value ie. 1,0,0 will allow only red light to pass through far through the object.
- **Base Specular**
	- Sets the base specular value on the Principled BSDF inside.
- **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB.
- **Normal X, Y**
	- Sets the X and Y values of the materials normals. If no input is avilable leave at 0.5 on both or shading will break.
- **Normal Strength**
	- The strength of the normals.
- **RSSSS Toggle**
	- Set to 0 to use RSSSAO input, 1 to use RSSSS input.
- **AO Strength**
	- Sets the strength of the AO effect.  _(RSSSAO Only)_