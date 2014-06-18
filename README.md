openmetro
=========
**Open** Data + Milan **Metro** = **OpenMetro**.

This is just a way to showcase what open data can be used for. Ideally it should be used to represent the whole metro map but I started with the shortest line which is working right now ([lilac line or line number 5](https://en.wikipedia.org/wiki/Milan_Metro_Line_5)).

Browser issues
==============
It does not work on Opera and Safari (but next release, Safari 8, should implement the template tag and so it should start working fine). It looks a bit weird in Chrome (labels are far away from the circles representing metro stations). It looks fine on Firefox.

Code issues
===========
It has to be rewritten compltely from the bottom up! :) 

Data
====
I've provided a data directory where the raw dataset (comma separated value format) has been provided for you to be reused. I'll provide more info on this dataset in the next commits.

Libraries
=========
CVS.js: https://github.com/adobe-webplatform/Snap.svg This is used to get an array of objects starting from a list of raw data in comma separated values.

Snap.svg: https://github.com/gkindel/CSV-JS This is used to create a representation of the metro line and any animation effect applied on it.

=========
Gabriele Gigliotti - twitter [@ridillo](https://twitter.com/ridillo), 2014
http://blog.gigliotti.it
