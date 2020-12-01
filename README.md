# decorations

This repository contains examples of adding decorations to Legal
Server.

## Contents

This GitHub repository contains the following files:

* [music.html](https://github.com/LegalServerJS/decorations/blob/master/music.html):
  This adds a picture in which the mouse cursor is either Santa and
  Reindeer or a dreidel, depending on a random number.  It also
  includes an audio widget for playing a random holiday song.
* [snow.html](https://github.com/LegalServerJS/decorations/blob/master/snow.html):
  This adds an animation of falling snow at the top of the home
  screen.
* [xmas-lights.html](https://github.com/LegalServerJS/decorations/blob/master/xmas-lights.html):
  This adds blinking Christmas lights to the blue navigation bar of
  the Legal Server home page.
* [xmas-other.html](https://github.com/LegalServerJS/decorations/blob/master/xmas-other.html):
  This adds a variety of other holiday decorations to the Legal Server
  home page, such as the replacement of "Home" in the breadcrumb
  navigation with "Ho, ho, home!", "wrapping paper" in the sidebar,
  and a Christmas tree in the background.
* [halloween.html](https://github.com/LegalServerJS/decorations/blob/master/halloween.html):
  A spooky ghost sometimes appears, before quickly disappearing again.

You can find links to these files above.

## Instructions

Log into Legal Server as an Administrator.

Go to Admin -> Processes, Forms, and Profiles

Set "Forms and Processes for Module" to "Home/Section Front"

On the Profiles tab, click the edit icon next to your main "Home"
profile.

Scroll down to where you see the "Add" button.

Set the pull-down selector to "Instruction" and click "Add."

This will add an "Instruction" as an "Enabled" form element.

Open up the instruction's properties by clicking the blue triangle.

Check the checkbox next to "Format as HTML."  This is very important!

Copy and paste the contents of one of the HTML files in this
repository into the "Text" of the Instruction.  (When viewing the file
in GitHub, it might make it easier to copy and paste if you click the
"Raw" button; then you can copy everything with Ctrl-a.)

Then press "Continue" or "Save & Stay on Page" to save your work.

This will decorate the Home page only.  If you want to decorate
the Profile for cases, follow the instructions above but instead
of choosing the "Home" profile under "Home/Section Front", choose the
"Case/Matter" module and edit the profile you use for cases.

For most of the decorations, it doesn't matter where you place them
because the instructions themselves are invisible.  However,
[music.html](https://github.com/LegalServerJS/decorations/blob/master/music.html)
is an exception to this.  You can place this instruction in the place
in the page where you want the picture to appear.

## Customization

The HTML snippets contain URL references to image files hosted on the
web site of Philadelphia Legal Assistance.  E.g.,
`https://philalegal.org/html/night.jpg` You can see what each of these
images looks like by selecting the URL, copying it, opening a new tab
in your web browser, and then pasting the URL into the location bar.
If you want to use a different image, just change the URL.  For
example, `https://philalegal.org/html/night.jpg` is a nighttime
picture of Philadelphia.  You might want to change this to a URL for a
nighttime picture of your city.  If you have an image on your computer
that you want to make available at a URL, talk to your IT director
about putting the image on your organization's web site.

The JavaScript code inside the HTML snippets also contains some
if/else statements based on random numbers.  For example, the code
that places some "holiday wrapping paper" in the Legal Server sidebar
is programmed to use one pattern 50% of the time, another pattern 25%
of the time, and a third pattern (a Hanukkah pattern) 25% of the time.
You might want to change these ratios by tweaking the random number
thresholds, which are numbers between 0 and 1.

## Bonus customization: random cat picture

* [random-cat.html](https://github.com/LegalServerJS/decorations/blob/master/random-cat.html): You can place this in any auxiliary form.  It
  displays a link saying "Click here to display your visual reward!"
  and when you click it, you see a random picture of a cat, courtesy
  of the Cat API.

## Second bonus customization: puppies tab

* [puppies.html](https://github.com/LegalServerJS/decorations/blob/master/puppies.html):
  From the "Home/Section Front" area of your "Processes, Forms, and
  Profiles," go to "Tab Blocks" and edit one of the "tab blocks" that
  is used by your Home screen.  Add a "Tab" called "Puppies" and
  include this HTML as an instruction.

## Third bonus customization: Harry Potter spells

* [lumos.html](https://github.com/LegalServerJS/decorations/blob/master/lumos.html): Lumos!
* [wingardium.html](https://github.com/LegalServerJS/decorations/blob/master/wingardium.html):
  Wingardium Leviosa!

## Contact

Contact [Jonathan Pyle](mailto:jpyle@philalegal.org) at [Philadelphia
Legal Assistance](https://philalegal.org), 215-981-3843, with any
questions.
