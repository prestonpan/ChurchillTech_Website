# My Website
author: Preston Pan \
description: My minimal, js-free website.

## Introduction
This is our school's tech club website. It's cool I guess, and I like it.
Due to the minimalistic nature of the website, fonts are locally stored and there are no google fonts to render.

## building
To generate and open the website, run the website.sh script with:
`./website.sh build`
A build folder in the same directory as that script will be generated. Simply open `index.html` in your browser. Note that
the fonts will not display until after you actually deploy the
website, due to me refering to the fonts via global path in my
css file, which is really an html file in templates by the name of
of `style.html`.
