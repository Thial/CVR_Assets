# Welcome to my CVR Assets repo.

You can find all of my public projects here. If you like my work please click the **Watch** button so I'll have a better idea of how many people are interested in my work.

## Installation

All of my assets are available as **.unitypackage** files therefore you just need to import them to Unity.

# Current Projects

## [Anime Grass](https://github.com/Thial/CVR_Assets/blob/master/Shaders/AnimeGrass.unitypackage)
This is an edit of a grass shader by Leviant. The shader has been modified to provide maximum performance with some nice features and to make the grass look like in Studio Ghibli movies. This shader is made for people baking their shadows outside of Unity. It does not support Unity's light maps / lighting / shadows since that requires extra calculations. It is meant for highly stylized worlds.

![Anime Grass](https://i.imgur.com/C0CL9Ct.png)

1. Forced the grass blades to be rendered in the most optimized way.
2. Removed Lighting/Shadows calculations
3. Removed the grass shadow gradient and replaced it with tip brightness to allow blending with the ground texture
4. Removed other unnecessary calculations to keep the bare minimum of the code necessary for the grass to render.
5. Added color map UV mapping support (As the shader doesn't support shadows the shadows need to be baked onto the color map texture).
6. Added height map functionality along with UV mapping support.
7. Added height map strength functionality.
8. Added height map mask functionality which doesn't render grass where the height map is black or dark enough depending on the Height Map Mask Strength slider (This allows you to create patches/clumps/paths/remove grass from below other objects etc).
9. Added grass rotation functionality. If the rotation is too strong and the grass will go under the surface it simply won't be rendered just like with the height map masking.

