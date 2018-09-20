Class: CEG 4110-01 Intro to Software Engineering
Project Assignment: Homework 1
Project Name: # CEG4110-HW-01
Student Name: Cameron Windsor Fox
This is the first homework project assignment for my CEG 4110 class of my Senior Year at Wright State University.

How I ran and tested the Android Application: I have only been able to run the application by using my own phone to test it. I could not get an emulator running at all on my computer no matter what I tried. 

Purpose of Application:
This application is composed of two parts; 

Special Deployment Instructions:
There are no special deployment instructions to run this application. The only thing is that I could only run and text the project through my own phone. So I have the 
full project zipped, unzip it and run it in android studio, everything should work as intended.

Part 1, create a UI where you can input the name of a color or any text in a text box, then when you click a button it will randomly change the color of the text of whatever you just entered on the application.

Part 2, you must create a second UI on this application that contains a canvas that will let you draw on the screen with your finger. In addition to painting in the canvas, you must also be abl eto do the following:
1. Clear the Canvas to start a new drawing by the use of a button.
2. When you finish your drawing you must be able to save this image of the canvas in either a png file or jpeg file format. 

Including these two parts to the assignment you need to implement a way of navigating between both UI elements to travel back and forth if if the user chooses to do so. 
Deep Detailed Description:
For my build of the assignment here is my display and how to use the application.
Phase 01:
Figure 1.0 shows the application when you first start it up.
![screenshot_20180919-153915](https://user-images.githubusercontent.com/33787330/45783321-4f469f00-bc1a-11e8-8ed2-40d7c8b67d96.png)

Then by tapping on the text view at the middle top of the screen the keyboard will come up and the text disapeares when you tap it, giving you the space to enter what text you want. This is showsn in Figure 1.1.
![screenshot_20180919-153935](https://user-images.githubusercontent.com/33787330/45783699-620da380-bc1b-11e8-9c44-47f48954af7b.png)

You Then Enter the Color or what ever text you choose into the text box. See in Figure 1.2
![screenshot_20180919-153945](https://user-images.githubusercontent.com/33787330/45783526-dbf15d00-bc1a-11e8-9b2a-93db327335a9.png)

Then apon tapping the text color generator button, the text will change to a random color while also display the rgb data followed by the hex code for the color that is generated. See the last figure of part 1. Figure 1.3
![screenshot_20180919-173914](https://user-images.githubusercontent.com/33787330/45783645-312d6e80-bc1b-11e8-881e-687790b25e43.png)

At the bottom of the screen there is an additonal button labed canvas. This button will direct you to the second UI element, the canvas as the button name suggests, it is where you are able to trace your finger on the screen and draw what ever you want with in the given white space provided. See Figure 1.4 for the main view of this UI.
![screenshot_20180919-154051](https://user-images.githubusercontent.com/33787330/45783904-faa42380-bc1b-11e8-88b4-a7f3f294b2c2.png)

Now you are able to run your finger across the screen in the given white space and draw what you choose. Currently giving you the color black as default. See the Figure 1.5 for an example.
![screenshot_20180919-154138](https://user-images.githubusercontent.com/33787330/45784058-64bcc880-bc1c-11e8-9dda-0388d64a7ec7.png)

At the bottom you see three buttons, the first one labed clear canvas, will do as the name says, it will clear any drawing made and bring you to a blank screen just as you saw in Figure 1.4.

The next button, labeled brush color will change the color you are painting with. Since you are currently using black as a default color if you hit the brush color button, the background of the button will change and the color it changes to is the new color you can draw with. It will also change the color of the drawing that is shown on the canvas if you haven't cleared it before hand. Allowing you to continue drawing and see everything in a different color of choice. See Figure 1.6.
![screenshot_20180919-180257](https://user-images.githubusercontent.com/33787330/45786986-d51d1700-bc27-11e8-87a8-2f0b9d6326dc.png)

Next up is the save drawing button, this will take the canvas drawing that you created and save it as a PNG file. To show it works when you press the button a text display will appear for a short time to say whether or not the image was successfully saved. See Figure 1.7 for when the image is saved.
![screenshot_20180919-191114](https://user-images.githubusercontent.com/33787330/45786773-edd8fd00-bc26-11e8-890f-301e33d98cda.png)

Finally the last button shown at the top of the canvas screen, labed go back. This uses the same function as the canvas button from the previous UI. It will take you back to the first UI screen. When doing so, it resets the UI as if you just booted the app up as shown in Figure 1.0.

Extras
Now when the Image is not saved correctly Figure 1.8 will come up.
![screenshot_20180919-180312](https://user-images.githubusercontent.com/33787330/45787048-1f05fd00-bc28-11e8-940b-2efeaecc5e72.png)
