Storybord Lab Instructions
=================
Let's make a simple app interface using Storyboards.

1. Make a new Xcode project.

2. Drag two UIViewController's onto Main.storyboard from the UI element panel on the bottom right of Interface Builder.

3. For each UIViewController, select the top part of the UIViewController (next to the three buttons on top), then look at the panel on the right. Find the 'Custom Class' tab and change the custom class of the first UIViewController to MatchSelectionViewController. Change the custom class of the second UIViewController to DetailedProfileViewController.

4. Drag a button onto MatchSelectionViewController.

5. Create a _segue_ from the button to the DetailedProfileViewController. CTRL + DRAG from the button to DetailedProfileViewController. In the Action Menu segue that pops up, choose 'Present Modally'.

6. Drag a label onto DetailedProfileViewController and change the text of the label to 'Details'.

7. Drag a button onto this UIViewController. Then create an IBAction between this button and DetailedProfileViewController.swift.

8: Add this code inside the IBAction:
dismissViewControllerAnimated(true, completion: nil)

You should now be able to tap a button, see another screen pop up from below, and then dismiss the second screen by tapping the button on the second screen. This uses a segue, an IBAction, and Storyboard.

If you finish everything, go ahead and make your interface look nicer, and explore the right panel on Xcode, and all the UI elements you can drag on screen in there. 
