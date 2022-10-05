# AR XRay learning project

Third project in CircuitStream XR Development course, September 2021

An Augmented Reality demo project for projecting 3D models based on visual identification using Vuforia Engine.

Reference excerpt: https://library.vuforia.com/getting-started/getting-started-vuforia-engine-unity section "About Vuforia Engine":
"Vuforia Engine is a software development kit (SDK) for creating Augmented Reality apps.
With the SDK, you add advanced computer vision functionality to your application, allowing it to recognize images,
objects, and spaces with intuitive options to configure your app to interact with the real world."

The primary challenge in this exercise was to implement the Vuforia Engine SDK in an Augmented Reality application in Unity.
This involved adding reference images to the scene from real world objects with clear contrasts for visual recognition through a device camera.
In the AR application, a 3D object can be represented in real time, oriented to the reference image and manipulated.
The further implementation involved creating an "XRay" effect by augmenting the render queue where two 3D objects interact.
