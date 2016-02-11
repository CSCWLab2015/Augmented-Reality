# augmented-reality
The general information about the Augmented Reality part of the project can be found at our [wiki](https://github.com/CSCWLab2015/augmented-reality/wiki) page.

#Environment
The project is developed on [Unity3D 5.2.2f](https://unity3d.com/get-unity/download/archive). We are using 32 Bit version of Unity 5.2.2f, because [Vuforia 5-0-6 plugin](https://developer.vuforia.com/downloads/sdk)
that we are using for tracking the markers does not have 64 Bit dll files for Unity 5.
Communication between server and AR is done by using JSON files. These JSON files are processed by [LitJson plugin](http://lbv.github.io/litjson/)
for unity. How to use LitJson is well explained at this [tutorial](https://youtu.be/OyQQ-7-22Hw).

