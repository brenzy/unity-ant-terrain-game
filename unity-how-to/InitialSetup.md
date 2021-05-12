## Initial Setup

- created an empty 3D project

# Discussion of URP vs 3D
- The original plan was to use the Universal Rendering Pipeline (URP) for this project in order to get access to all the post-processing effects available in the URP
- I had created an empty 3D project rather than using the URP template in Unity Hub in order to be able to start with a clean project and not have to figure what I need to keep or throw away
- followed the steps for [Installing the Universal Render Pipeline into an existing Project](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@11.0/manual/InstallURPIntoAProject.html)
- All the packages I was picking up needed to be converted to the URP.  The easiest way to convert package to URP seems to be  "Edit > Render Pipeline > Universal Render Pipeline > Upgrade Project Materials to URP Materials".  Otherwise, you need to find each asset and convert it separately.
- In the end I backed out of these changes and decided to stick with 3D for a number of reasons.  It took a long time to load, it was much slower in the dev environment, it was a hassle to keep converting assets, and it wasn't something I could demo on Discord because it took up too much CPU.
