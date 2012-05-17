jquery.percentageloader 0.1
===========================

[work in progress]

Requirements
------------

* Firefox 3.0+, Safari 4.0+, Chrome 7+, IE9+, Opera 9+

(i.e any browser with reasonable canvas support)

* jQuery 1.4+

Installation
------------

* Include the javascript file
* Optional but recommended web font - Bebas Neue + fontkit CSS
* Run on any block element where you want the widget to appear

* Options include:
  - progress (initial starting position of loader, range 0 - 1.0)
  - value (initial label for the value)
  - width (defaults to 256)
  - height (default to 256)

  e.g:
    $("#myDiv").percentageLoader({
        width : 180, height : 180, progress : 0.5, value : '512kb'});

* You can update the values with .setProgress() and .setValue() functions 

