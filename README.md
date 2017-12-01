# Udacity-VRND-HelloWorld

First Udacity virtual reality nanodegree (VRND) project. Our hello project required us to edit some game objects in a 
pre-made scene and deploy it to our phone. We also had to add a flashlight and modify a menu to include buttons that were descriptive
based on the actions they initiated. Lastly, we had to provide instructions so that a user would know what to do. 

![Picture of Hello World Project] (https://docs.google.com/uc?id=0B6uYPHCWTV0xSlVuM1hLSGZuRWc)
![Picture of instructions] (https://docs.google.com/uc?id=0B6uYPHCWTV0xSXhDVVkyRlMwMk0)
![Picture of flashlight] (https://docs.google.com/uc?id=0B6uYPHCWTV0xZUowNmN4d3RxLVk)

# Project Requirements
## Customizing Your App

### Change the Hello World text to include the Student's name

Student locates the "Hello World" Gameobject in the Hierarchy and finds the Text component. They change the text field to include their name and instructions on how to use the app. Example text could be "Hello World by First Last. In this game, you can spawn cubes from the sky, toggle night and day, and turn on a flashlight"

### Position Hello World Text object appropriately in the World

Once you have added in your name and instructions, some of the text will mostly likely appear below the floor. Make sure to raise it with the translation tool, so all the text appears above the floor.

### Change the functionality of the bottom 3 buttons to be 3 distinct functions other than SwitchShape.

Change the functionality of the bottom 3 buttons of the menu to be a different function other than ToggleShape and name "Switch Shape". The provided functions in the UdacityFunEffects script are "ToggleSun", "ToggleFlashlight", "ChangeParticleColor", "SpawnRandomCubes"

### Change the text of each button to reflect the function of the button

Give a descriptive name that corresponds to the name of the function for each of the 3 buttons. For example, for Toggle Sun, a basic 
name would be "Toggle Sun". A more creative and descriptive name would be "Switch Between Night and Day". Creativity is always 
rewarded :)

## Viewing Your App On a Device (Android or IOS)

### Screenshot of Unity app running on phone

Take a screenshot or a picture of your phone screen with the app you built running. Ideally, it shows any customization they made whether that be the student's name or changes you made to the menu. Place any screenshots in a folder named Screenshots/ in the top directory.

### Successful build of the app (apk file for Android and XCode project for iOS)

Make a folder called Build in the top directory of your zip file and place your apk or XCode project in there.

### All the player settings are correctly modified in order to build to device

The bundle identifier is set to a unique name that is not provided (i.e. com.udacity.p1.myname) and the default orientation of the app was changed to Landscape Left.
