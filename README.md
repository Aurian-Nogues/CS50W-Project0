# Project 0

Web Programming with Python and JavaScript
# Project0

test

This project's aim is to build a website presenting the roman emperors and some basic information about their reign.

On top of each page you can find a Navbar that allows you to quickly navigate between the different eras and the homepage of the website. The navbar collases into a list on smaller screens.

Styles.scss is the file controlling the layout, colours and fonts of the other pages.
The main styling elements like colors and fonts are defined by variables at the top of the file. The rest of the file assigns these variables to the different elements of the website and allows for styling of specific elements.

styles.css is the styles.scss file compiled through SAAS and read by the other .html pages

Index.html is the homepage. It list the different eras and emperors within them. You can click on any era to reach to their respective pages and get more information about their respective emperors. The title of the page gets shorter and its font smaller when displayed on smaller screens.

Claudian.html,Flavian.html,Gordian.html,Nerva.html and Severan.html are all built using the same structure and list the emperors from their respective eras and some of their characteristics.
The pages are built around a top conainter hosting the title and 2 columns that adjust depoending on screen size. The left colum contains the legend for the tags used in the table. The right column contains a table with a list of the different emperors and various information about them. The last column of this table contains tags from bootstrap 4 that help quickly identify an emperor's dynasty and succession type.



