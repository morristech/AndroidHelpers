DualPaneLayout - A simple implementation of a tablet friendly layout
====================================================================

## Features

* Small screens (phones) will display each fragment full screen

* Medium screens (tablet portrait mode) will display both fragments but the left fragment
can be hidden. When the left fragment is visible, the right fragment is 50% drawn off screen.

* Large screens (tablet landscape mode) will display both fragments always

This is a simple demonstration on how to structure your application using fragments and
variable layout files depending on screen width.
This allows you to take advantage of the screen of tablets while still fully supporting phones.

To use this in your own application, use my demo app as a base for how to override the
necessary methods and make sure to
change the class names in the layout.xml files as well. If you want to change the relative widths
of the fragments, change the weights in layout_constants.xml

Feel free to use this code any way you please.