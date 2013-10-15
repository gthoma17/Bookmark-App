Bookmark-App
============
This is the framework that I use for creating bookmark extensions for the chromebooks at work.

I went with an extension as opposed to an app since it seemed easier to use content scripts with extensions.

It works as follows:



1) Icon is clicked and loads popup.html

2) popup.html loads popup.js

3) popup.js loads the page that we want to load

4) The extension notices out page has a content script. It gets loaded

5) Users stop complaining and everything is sunshine and rainbows
