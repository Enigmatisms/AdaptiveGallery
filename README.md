# AdaptiveGallery
Gallery for my [AdaPT renderer](https://github.com/Enigmatisms/AdaPT). The repo holds some good-looking rendering results and the scene files / obj files.

Note that some of the models come from [TurboSquid](https://www.turbosquid.com/) and [Sketchup 3D warehouse](https://3dwarehouse.sketchup.com/). If the usage of some models violates your copyright, please contact me for removal.

##### The Helmet of Vader

|Lambertian|Frensel Blend|Glass Transmit|
|:---:|:---:|:---:|
|   ![lambertian-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/636774d9-d541-4561-aa56-80a4c5f7d2ba)|![fresnel-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/e1c70c7f-4ba5-49e2-be10-a8bdddf65fa1)|             ![glass-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/1156f1bf-5cb6-4ac8-b755-f616ec47670c)|
|Blinn Phong Glossy| Modified Phong (no diffuse)|Modified Phong (all components) |
|![blinn-phong-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/30a28f2b-9116-48a0-adcf-e6f2b28e8424)|![mod-phong-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/f5cb7540-d0f4-47fd-a3e2-774bc80e2432)|         ![correct-mod-phong](https://github.com/Enigmatisms/AdaPT/assets/46109954/dfa42a42-b5da-4f07-9656-aecd6e305976)|
|Oren-Nayar|Smooth GGX|Rougher GGX|
|![oren-nayar-vader](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/36087bbf-d925-4d04-b2f1-faab4aeef6e6)|![microfacet-vader-0 001-rough](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/63150d77-4510-48aa-975c-c7d3a71b4461)|![microfacet-vader-0 05-rough](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/97c9c5eb-e575-4726-bc1c-144b71b0ad5d)|
|Thin coating plastic|Lambertian trans|Normal mapping|
|![plastic-vader](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/05bb8045-929b-476f-9296-d99f0f92f810)|![lambertian-trans](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/93849ff9-2570-48ea-a241-546ae1c4a9dd)|![bumped-oren-nayar-vader](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/c375fc9e-38ec-4f72-a0aa-fbed22fe634c)|

#### Sports car

This scene has ~290k primitives, 16 bounces, with many different BxDFs:
Front view:
<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/b480b716-f6f2-4163-86d9-3b87591297de"/></p>

Back view:
<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/23b7c7a1-acc8-439f-a91a-903fdc28a381"/></p>

**SSAO**: The following images are rendered using RTX3060-laptop with a interactive preview, without it, the rendering speed is 81 fps and 161 fps, respectively.

|Lambo scene (67 fps)|Lambo-back scene (120 fps)|
|:-:|:-:|
|![pbr-lambo-ao](https://github.com/Enigmatisms/AdaPT/assets/46109954/3acf5890-0535-4d33-985f-e36cd952fdac)|![pbr-lambo-back-ao](https://github.com/Enigmatisms/AdaPT/assets/46109954/40d390eb-2c04-4cf5-85eb-ae30ff5364a9)|


##### Bathroom scene

Original scene can be found here: [Blendswap](http://www.blendswap.com/blends/view/73937). I made a few modifications (like the bathtub), and since I can't obtain the original texture and material, I re-created the scene (which is about 400k primitives, 8 bounces, CUDA backend 0.2fps for BDPT, 1.8fps for PT).

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/69272001-8acf-4196-9451-cfd4830e4067"/></p>

##### material orb scene (~500k primitives, 24 bounces, CUDA backend 16fps)

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/79754d30-1ce6-4ab2-a382-42010ed7c5b5"/></p>

##### venus scene (shading normal, bump map and glossy reflection):

<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/e72cc048-c001-4d46-ae5f-828052c8cbfc"/></p>

##### skeleton scene (~100k faces):

<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/be8a9307-4dd6-43d8-a52e-eac666223203"/></p>

##### Kitchen scene (100k+ faces):

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/4c891d25-70ce-4239-9c48-ddf72c72ad4d"/></p>

##### Stuff scene

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/d91b93e4-3084-419d-a310-a5dbb11d77ea"/></p>

##### Storm troopers scene

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/038a7b15-3e88-40e2-82a9-0155ca10ade0"/></p>

##### Heterogeneous medium rendering

| Janga Smoke (RGB volume) | Desert Tornado (RGB volume) |
| ------------------------- | --------------- |
|![pbr-cbox-rgbvol-vpt-rgblight](https://github.com/Enigmatisms/AdaPT/assets/46109954/6bb9f35a-7323-432a-b319-7b04b96e91d0)|![pbr-cbox-rgbvol-vpt](https://github.com/Enigmatisms/AdaPT/assets/46109954/11f5a64e-4fa4-4ae1-9971-ba2bc40d8fc5)|

##### Bunny scenes (90k+ faces)

| "Spotlight Foggy Bunnies" | "Three Bunnies" |
| ------------------------- | --------------- |
|  ![pbr-bunny-bdpt-textured](https://github.com/Enigmatisms/AdaPT/assets/46109954/07f0b226-f94b-4862-8c8e-a9511b5eceeb)            |      ![pbr-bunny-pt](https://github.com/Enigmatisms/AdaPT/assets/46109954/6caee802-8933-4c96-8ca4-281065fe5cfe)           |

##### Bunny with shading normal & total reflection

<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/277c86e9-c407-4f14-9aa7-e8478878645b"/></p>

##### Cornell sphere

|Plastic ball|Lambertian Transmission|Mixture|
|:-:|:-:|:-:|
|![pbr-mix-balls-bdpt](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/e0329c61-bd7a-4c9b-9c49-35731281b9f1)|![pbr-balls-mono-bdpt](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/ca706645-6208-4105-bb0a-d596abc75a11)|![pbr-mix-balls-bdpt-strange](https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/6bb792f9-8c8a-4281-afe5-c7e9b5a76da3)|
