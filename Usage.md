# Introduction #

The plugin was designed to be friendly and does not require any additional CSS.


# Details #
The constructor of the Loader object takes 2 arguments:
1- The id of the div, if not defined it is set to the body
2- An object defining the options to be used:
> a- overlayColor: hex string defining the color of the overlay defaults to black.

> b- userCallback: function called when the loading is completed, defaults to null.

> c- showProgress: boolean variable defining if the progress bar is shown or not, defaults to false.

> d- showProgressText: boolean variable defining if the progress text is shown or not, defaults to false.

> e- progressColor: hex string defining the color of the progress bar, defaults to white.

> f- textColor: hex string defining the color of the progress text, defaults to white.


> g- textSize: hex string defining the sizeof the progress text.

> h- loaderPosition: an object defining the position of the progress text and loading bar relative to the loader overlay.



Usage Example:

var loader= new Loader("#content", {userCallback:showContent, showProgress:true, showProgressText:true, textSize:15});

loader.Start();

or:

var loader= new Loader("#content", {userCallback:showContent, showProgress:true, showProgressText:true, textSize:15, loaderPosition:{top:20,left:50}});

loader.Start();