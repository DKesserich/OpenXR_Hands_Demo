# OpenXR_Hands_Demo

![](https://github.com/DKesserich/OpenXR_Hands_Demo/blob/main/gif/Hands.gif)

A modified version of the Unreal OpenXR Template that uses LiveLink for finger tracking (requires a compatible VR headset and controllers)

See the Content\Hand\OpenXR_Hand_AnimBP to see how I set up the animation blueprint for the hands.

I've only tested the finger tracking with a Valve Index and Index Controllers. It should work with any OpenXR compatible PC headset, though if using an Oculus Quest you may have to run using SteamVR as your OpenXR Runtime.

The skeletal mesh for the hand was pulled from the SteamVR Rendermodels. I'm unsure if the hand models that were added to the template in Unreal Engine 5.1 are compatible with this setup.
