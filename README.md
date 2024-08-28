# VR_Carboard
I created the application using the provided documentation. In my application, I implemented spheres and other game objects like cubes. I added materials with different colors and textures. I implemented TextMeshPro and wrote "Welcome to VR" in the room. I also added scripting for rotation that supports the API and implemented an orbiting asteroid. Finally, my first Android application turned out well, and I named it "VR." It’s cool to see the icon on my phone.

Problems I faced:
CommandInvokationFailure: Unable to install APK to device. Please make sure the Android SDK is installed and is properly configured in the Editor. See the Console for more details.
D:\Files\UnityHub\2022.3.10f1\Editor\Data\PlaybackEngines\AndroidPlayer\SDK\platform-tools\adb.exe -s "bm6lc64lcux4fee6" install -r -d "D:\VR\BuildCode\First\Jane_Cardboard.apk"

Solution:
I solved it by verifying that adb is working on my system and reinstalling the SDK.
