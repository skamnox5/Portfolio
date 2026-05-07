---
tags:
  - Blender
  - Rigging
  - Texturing
  - Animating
  - Modeling
---
<Carousel>
<img src="Rifle_FullAnim.gif" alt="Anim"/>
<img src="Rifle_01.png" alt="Details"/>
<img src="Rifle_02.png" alt="Texture"/>
</Carousel>

# Details

- **Software:** Blender
- **Style**: PBR
- **Polycount:** 4,451
- **Texture Resolution:** 1024x1024
- **Role:** Modeler, Rigger, Texture Artist, Animator

# Modeling

<Carousel>
<img src="Rifle_Details.png" alt="Details"/>
</Carousel>

I modeled this by extruding planes and cubes over a reference image with an active subdivision modifier, using creases to sharpen certain edges.
# Texture


<Carousel>
<img src="Rifle_Color.png" alt="Albedo Map"/>
<img src="Rifle_Packed.png" alt="Packed Roughness and Metallic"/>
<img src="Rifle_Normal.png" alt="Normal Map"/>
</Carousel>

I used the Ucupaint Blender add-on to create the Albedo, Roughness, Metallic and Normal maps for the rifle.

I used a procedural noise texture to create the wood like material and used a different noise texture to add a patchy roughness layer on both the metal and wood materials to make the rifle have more texture so it doesn't look too flat and polished. 


# Rigging

<Carousel>
<img src="Rifle_Limit.gif" alt="Rig constraint"/>
</Carousel>

I rigged the different mechanical parts of the rifle such as the lever, trigger, hammer, chamber and loading port. 

I created a control rig where I added Limit Constraints to most of the control bones so that the only move in the ways that those pieces should move and limited them to what would be their realistic limits.