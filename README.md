# SSC-2023

"Tupã" Zip file for swift playground with an iPad

"Swift_Student_Challenge-2023" file for Xcode with an iPhone real device

# What's that about?

I developed this game for the Swift Student Challenge of the Apple Worldwide Developers Conference, I used RealityKit to show a 3D native Brazilian village in augmented reality, because with this technology I could present the most didactic and immersive way possible as a native Brazilian village, you can notice people performing their daily activities, such as fishing, farming, archery training, boating. To make the experience as immersive as possible, I used AVFoundation to play a nature sound that I recorded myself. In this small world are hidden folklore monsters, when finding them the user must touch them, when this happens, I used the UIFeedbackGenerator to generate a vibration in the device. Soon afterward, a small screen appears with the respective legend of that monster.

Now that the user has learned about the Brazilian folklore he can give closure to the game story and be congratulated for having helped the native Brazilian village, I hope that this journey can be a great opportunity for the user to learn about the Brazilian folklore and that it instigates him to know other tales of the our folklore.

# Advises
if you are trying to use the playground version, you need to use in the iPad playground and follow this recomendations:

### -- App needs to be used in portrait --

I couldn't set the app to accept only portrait mode in playground, so I ask you to lock the ipad in portrait mode and use it this way

### -- Augmented reality content --

- The game uses the camera to show 3D objects in augmented reality, I urge you to use PlayGround on iPad to be able to use the device's camera

- Try aiming the iPad camera at textured surfaces, because RealityKit does not detect solid color surfaces very well (during testing I was pointing at my keyboard)

- Even when loading the 3D models asynchronously, the game freeze for a few moments while loading the 3D models, please wait, it doesn't take long time

- As soon as the game detects a plane it places the 3D model on the detected plane, as soon as the camera opens, aim the iPad at the place you want to place the 3D model.

### -- Sound --

- The game has a nature sound during gameplay use a headset for a relaxing experience :-)

Enjoy.
