# Assignment 2

- [Work](https://bennyboy.tech/bab-test-1/)
- [Source](https://github.com/molarmanful/bab-test-1)
- [Inspiration](https://loc.gov/resource/ppmsca.30768/)
- [Model](https://www.myminifactory.com/object/3d-print-hand-muscles-69480)

![](https://tile.loc.gov/storage-services/service/pnp/ppmsca/30700/30768v.jpg)

I was inspired by the camera distortions present in the photo of the pictured bracelet; especially notable were the chromatic aberration (see bottom of photo) and bloom generated by the metal's reflective highlights. With these observations in mind, I decided to experiment with similar distortions and interactions from my BabylonJS workflow. After composing the hand model and ground, I spent most of my efforts on tuning the lighting, materials, and post-processing to bring out the forms and features of the hand that I felt were aesthetically compelling.

Much of my experimentation ended up yielding rather simple setups; thankfully, this plays well with the limited computing power available in browser-based 3D rendering. I ended up using only one directional light, instead relying on a reflection texture/HDRI and fresnel settings to create interesting highlights. I initially tried to make a PBR material, only to go back to the default standard material since I liked the contouring and glossiness it brought out. For the ground, I placed a noise texture and dialed down the settings significantly to create an extremely subtle variance that was only slightly visible when panning the camera. Despite the subtleness, I liked that it made the background more visually interesting without overpowering the scene. Finally, I used the default rendering pipeline's chromatic aberration, bloom, and grain to create a filmic yet stylized finish that further accentuated the various hand features I brought out.
