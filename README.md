
<img src="images/3DHome_Repo_Banner.jpg" alt="BannerImage" style="width:100%;"/>

## Modeling guidlines to consider: #


### Polycount: ## 

Less than 100,000 polygons.

<img src="images/Polycount.jpg" alt="Polycount" style="width:20%;"/> <img src="images/Wireframe_PolyCount.jpg" alt="Wireframe" style="width:79%;"/>


### Texture optimization: 

Please map as many models as possible to a single texture. Additionally, baking the lighting into the textures would be beneficial.

<img src="images/BuildingBaked.jpg" alt="BuildingBaked" style="width:24%;"/> <img src="images/FloorBaked.jpg" alt="FloorBaked" style="width:24%;"/> <img src="images/FramingBaked.jpg" alt="FramingBaked" style="width:24%;"/> <img src="images/LandscapeBaked.jpg" alt="LandscapeBaked" style="width:24%;"/>

### Texture sizes: 
Keeping the texture resolutions low with memory, loading and performance. Please optimize them accordingly.


### Export settings: 

You can choose one of the following options based on your preference.

GLTF format with separate textures and a binary file (.gltf + textures + .bin)
GLTF format with embedded textures (.gltf with embedded textures)
GLB format with embedded textures (.glb with embedded textures)

### Total File Size:

Please try to keep the total file size smaller than 30mb. You can make it larger but it will take longer to load. 

##
### UV Editor
<img src="images/UV_Editor.jpg" alt="BakedTexture" style="width:32%;"/>

Under the UV Editor there are up to 3 textures to assign. There is a flat texture you can use when you want to assign and bake lights. There is a baked lightmap and UV Grid. 

<img src="images/UV_Grid.jpg" alt="UVGRid" style="width:32%;"/> <img src="images/UV_Texture.jpg" alt="FlatTextures" style="width:32%;"/> <img src="images/UV_Texture_Baked.jpg" alt="BakedTexture" style="width:32%;"/>




