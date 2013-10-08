#GoogleOAuth2#

This JavaScript module provides AOuth2 authentication using Google's API. 
And was written to be used with [wakandaDB](http://wakandaDB.org/).

For an example use please see https://github.com/lyle/GlassWakanda

To Install for use with Wakanda
-------------------------------

Put the GoogleOAuth2.js file into your Wakanda Project "Modules" folder - you can just clone this repo as a sumb module. Or just download the GoogleOAuth2.js file.

If you clone the project as a sumbmodule, from your git project root:

    git submodule add https://github.com/lyle/GoogleOAuth2.git path/to/Modules/GoogleOAuth2

Then get the dependency "wakanda-querystring" into the Modules folder.
Simply go and grab the querystring.js file from https://github.com/anvivia/wakanda-querystring
And place that file in your Modules folder so that Wakanda finds it at init.