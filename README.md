# Williams-AR-Test-Export
 
I’ve tested this on a Pixel 7 Android device. Launch the app and look at the phone to see the Logan Sargeant's Helmet on your head. This Dir folder is the complete export from Unity but my understanding is you only need the “unityLibrary” folder for integration into React Native. 

I used these articles as reference:  
- https://jpdev8.medium.com/how-to-create-a-unity-library-for-react-native-android-2f6230d6cdcd  
- https://pronteff.com/unity-integration-in-react-native/  

Here are further resources I found while researching that may be helpful:
- https://unity.com/features/unity-as-a-library
- https://docs.unity3d.com/Manual/UnityasaLibrary.html
- https://www.youtube.com/watch?v=2zQYrOeF1Ko
- https://github.com/Unity-Technologies/uaal-example
- https://github.com/Unity-Technologies/uaal-ar-example

These are the configuration settings I used that could have some impact on your application.

Under Graphics API OpenGLES2 is being deprecated so I'm only using OpenGLES3. It’s possible we want Vulcan enabled but I didn’t enable it in this version.  
![alt text](/readme_images/graphics.png)

.NET Framework is the other option under Api Compatibility Level. I used .NET Standard 2.1. I also left on ARMv7 under Target Architectures.  
![alt text](/readme_images/configuration.png)
