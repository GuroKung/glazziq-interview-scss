# Web design / SCSS interview problem

## Setup

You will need to install [SASS](http://sass-lang.com/)
to compile/re-compile `application.scss` using the scss interpreter.
You can have scss watch for changes and compile them into
`application.css` by running `compile-scss.sh` (Ctrl-C to exit).

## Background and Problem Statement

Your designer has produced the mockups contained within the downloaded folder.
The design is intended to be responsive, with breakpoints for large screen 
widths, medium widths, and mobile devices.

* The menubar should initially scroll with the page, and then remain fixed 
at the top (displayed above other content), as shown in `*_scrolled.png`.

* There are two types of menus shown: a dropdown menu and a full-width menu.

Use SCSS to generate usable CSS classes for the development team. You are 
allowed to import and use external libraries, but the HTML code using your 
CSS classes should be as semantic as possible. In other words,
`<div class="headline-featured">` is acceptable, but 
`<div class="headline headline-featured pull-left headline-lg">` is not.

Feel free to replace any of the imported libraries or change any of the
boilerplate code that is provided. The boilerplate builds on top of
 Pure.css, but
you can use Bootstrap, Foundation, etc if you prefer.

You should produce:

1. One (or more) SCSS files that compiles down to a single CSS file. 
It should use easily changeable variables to determine media 
query breakpoints, container widths, etc.
2. One HTML page that reproduces the design as accurately as possible. 
It should be capable of demonstrating responsive design as well as menu 
functionality. The code should have comments that make it easy for developers 
to add dynamic (server-side rendered) data.

## Submitting Answers

Upload your code to Github and send a pull request against the original repo, then
send an email with your name / contact information and a link to your repo
to [glazziq-dev-interview@glazziq.com](mailto:glazziq-dev-interview@glazziq.com).
