# SCP-CB-style-interaction-UI-in-Unity
This script will make an image hover over a particular object like in SCP CB.

README!!!:
----------------------------------------------------------------------------------------
Here is the guide on installing it:

1. Create an empty GameObject in your scene and put both of the scripts inside it.

2. Create a Canvas, click on UI and create an "Image". After that, set your sprite to that image and adjust the size.

3. Create an object you want the image to hover over it. Then, add a box collider in that object, adjust the size of it and set the tick box "Is trigger". This collider will be your area where when a player enters it, the image will appear and start hovering over an particular object.

4. If you dont have the FPS controller, you should add it.

5. Select that empty GameObject that you created, and follow the next steps:




1)Hover Image : Reference to an image that will hover over an target. Put your hovering image inside the box.

2)Target Collider : Reference to an area (Box Collider), where when the player enters it, the image will be visible on camera and will start hovering over an target. Put your object where the box collider is installed.

3)Player Collider : Reference to the player. Just put the FPS_Controller prefab into that box.

4)Target Object : Reference to an object, that the image will hover over it. Put the target object inside it.

5)Image Hover : Reference to an "Image Hover" script. just put your empty GameObject inside it.



Make sure that all your object (Target,image and collider) are in your empty GameObject!

----------------------------------------------------------------------------------------
