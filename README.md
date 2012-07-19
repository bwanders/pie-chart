pie-chart
=========

A simple pie chart renderer in PHP.

Usage
=====
http://domain/pie-chart/WIDTHxHEIGHT/FLAGS/DATA/TITLE.png

  - WIDTHxHEIGHT: optional part to set the width and height of the pie chart (defaults to 340x400)
  - FLAGS: tweaks the pie chart render, multiple flags seperated by a semi-colon
    - legend=[on|off] whether the legend is displayed
    - significance=<number> the significance of displayed numbers
    - sort=[on|off] should the pie slices be sorted?
  - DATA: the actual pie slices. Given as a semi-colon seperated list of key:value pairs
  - TITLE: optional title (the .png is mandatory) for the file

