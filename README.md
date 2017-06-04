# jelly.css
Very simple, light and easy to use responsive grid. Feel free to download and edit!

Jelly is my little personal project. I use it in my websites, as alternative for grid from Bootstrap or another frameworks. Jelly is very simple and intuitive. Weighs only 3kb but it's fully responsive and customisable grid for websites.

# How to install jelly

Download jelly.css or jelly.min.css and add it to your project as a usual css stylesheet.

<link rel="stylesheet" href="css/jelly.min.css" />
or
<link rel="stylesheet" href="css/jelly.css" />

# How to use jelly

jelly is responsive grid based on very simple system. User operate on six basic classes specifying width of columns:

col-1 - full width
col-1-4 25% width
col-2-4 50% width
col-3-4 75% width
col-1-3 33.3333% width
col-2-3 66.6666% width

Every module of your website, where jelly grid is used may be placed in div with "grid" class. You can use "page-container" class as a main div of your page.

Offsetting

you can offset your columns with "lo" class. Below you have small example:

col-lo-2-4 - it means 50%  left offset
co-lo-1-4 - it means 25% left offset

Responsive

jelly has a 3 breakpoints - for smartphone (360px), tablets (768px) and desktop (1200px). To determine float of your columns just add specific prefix to your classes.
smt - for smartphone
ipd - for ipad/tablet
dsk - for desktop
Example -
<div class="smt-col-1 dsk col-1-4">this div have 25% width on desktop and 100% width on smartphone</div>


# Summary

jelly is my little project and I'm still working on it. I will add new functionalities to this repository, like new classes and components. Feel free to download, use and edit this grid. You can report issues and errors in this project.

Have fun :)
