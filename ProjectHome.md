Based on  [Gaya's QueryLoader](http://www.gayadesign.com/diy/queryloader-preload-your-website-in-style/e)

Used to preload any div, it displays an overlay until all the images
and background images in the div are loaded.
It can have optional arguments to display and customize a porogress bar and
progress text.

This loader extends Gaya Design's QueryLoader adds more functionality and control:

- supports custom arguments no need for external CSS

- can have several loaders/divs being loaded running at the same time not limited to only one

- if the div itself has a background-image or if it is an image it is now taken into consideration.

- resize when window is resized.

- added support for a Stop Function, if you want to cancel a load in progress.

- Fixed an IE detection bug (make sure you are using jQuery 3.1.2).