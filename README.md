# AdaptiveGallery
Gallery for my [AdaPT renderer](https://github.com/Enigmatisms/AdaPT). The repo holds some good-looking rendering results and the scene files / obj files.

Note that some of the models come from [TurboSquid](https://www.turbosquid.com/) and [Sketchup 3D warehouse](https://3dwarehouse.sketchup.com/). If the usage of some models violates your copyright, please contact me for removal.

##### The Helmet of Vader

|Lambertian|Frensel Blend|Glass Transmit|
|:---:|:---:|:---:|
|   ![lambertian-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/636774d9-d541-4561-aa56-80a4c5f7d2ba)|![fresnel-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/e1c70c7f-4ba5-49e2-be10-a8bdddf65fa1)|             ![glass-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/1156f1bf-5cb6-4ac8-b755-f616ec47670c)|
|Blinn Phong Glossy| Modified Phong (incorrect)|Modified Phong (correct) |
|![blinn-phong-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/30a28f2b-9116-48a0-adcf-e6f2b28e8424)|![mod-phong-vader](https://github.com/Enigmatisms/AdaPT/assets/46109954/f5cb7540-d0f4-47fd-a3e2-774bc80e2432)|         ![correct-mod-phong](https://github.com/Enigmatisms/AdaPT/assets/46109954/dfa42a42-b5da-4f07-9656-aecd6e305976)|

##### Bathroom scene

Original scene can be found here: [Blendswap](http://www.blendswap.com/blends/view/73937). I made a few modifications (like the bathtub), and since I can't obtain the original texture and material, I re-created the scene (which is about 400k primitives, 8 bounces, CUDA backend 0.2fps for BDPT, 1.8fps for PT).

<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/8515ab2f-d008-44db-812e-6c99786bb602"/></p>

##### material orb scene (~500k primitives, 24 bounces, CUDA backend 16fps)

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/79754d30-1ce6-4ab2-a382-42010ed7c5b5"/></p>

##### venus scene (shading normal, bump map and glossy reflection):

<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/e1cf7fa0-6788-4539-8c62-56f1aedd818a"/></p>

##### skeleton scene (~100k faces):

<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/be8a9307-4dd6-43d8-a52e-eac666223203"/></p>

##### Kitchen scene (100k+ faces):

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/4c891d25-70ce-4239-9c48-ddf72c72ad4d"/></p>

##### Stuff scene

<p align="center"><img src="https://github.com/Enigmatisms/AdaPT/assets/46109954/d91b93e4-3084-419d-a310-a5dbb11d77ea"/></p>

##### Bunny scenes (90k+ faces)

| "Spotlight Foggy Bunnies" | "Three Bunnies" |
| ------------------------- | --------------- |
|  ![pbr-bunny-bdpt-textured](https://github.com/Enigmatisms/AdaPT/assets/46109954/07f0b226-f94b-4862-8c8e-a9511b5eceeb)            |      ![pbr-bunny-pt](https://github.com/Enigmatisms/AdaPT/assets/46109954/6caee802-8933-4c96-8ca4-281065fe5cfe)           |

##### Bunny with shading normal & total reflection

<p align="center"><img src="https://github.com/Enigmatisms/AdaptiveGallery/assets/46109954/1a850733-0833-4e44-aa0e-31a49ff815fb"/></p>

