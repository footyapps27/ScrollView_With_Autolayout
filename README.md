UIScrollView with auto layout implementation example.

This repository contains a Xcode project showing how to implement the UIScrollView using auto layout.

The complete implementation was done using Storyboard.

The important points to remember with this aspect are:-

	• Drag a scroll view to the main view & setup its constraints.
		○ This is the size the scrollview will take in the screen.
	• Drag a new uiview to the scrollview.
		○ Setup the constraints(all edges set to 0)
	• Setup the size constraint of the scrollview
		○ Ideally if you want the view to scroll, setup the size to more than the size of the scrollview.


*If the size of the content view is not known, then the constraints of the child view need to set the same.