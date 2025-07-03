AI3D Render is a series of 3D/XR app experiments built around a system allowing generative image to video to video AI. 

Since it's 2025 and image to 3D is basically a fully solved problem - beyond primitives:

1) we can extract a 3D model from an image and then tangibly animate it in AR to create a video as shown in my early 2025 CVPR Demo: 

![](https://www.youtube.com/watch?v=-_IHmyiEDak)

2) it seems that people prefer having a more traditional creator app, so I fleshed this out into the AI3D Render app, presented at CVPR (part of Go with the Flow Orals and CVPR Demos) along with moving both camera and scene objects using Ultraleap hand tracking in glasses-free 3D using a Sony Spatial Computing Display. 

[![Image from Gyazo](https://i.gyazo.com/7cdc36a9ade230aa33a62cdc9da7b7fe.gif)](https://gyazo.com/7cdc36a9ade230aa33a62cdc9da7b7fe)

![](https://www.youtube.com/watch?v=wbkcvBow6vA)

The first frame method can also be interpreted as a form of "vidbreeder", where one can "breed" new videos from a prompt+ first frame controlnet + video "motion noise". 


3) Here's an early version of an AI3D Render AR app (though the model doesn't generate great results when the objects are too small, FOV of phone issue)

![](https://www.youtube.com/watch?v=JcorlEGGswk)
