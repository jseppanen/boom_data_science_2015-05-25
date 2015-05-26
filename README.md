
# Boom Beach data science presentation

For Helsinki data science meetup, 2015-05-25

Online version: http://jseppanen.github.io/boom_data_science_2015-05-25

# Building an HTML version

## Convert to HTML

~~~~
ipython nbconvert Boom_Beach_data_science.ipynb --to slides --reveal-prefix=//cdnjs.cloudflare.com/ajax/libs/reveal.js/2.6.2
~~~~

## Change presentation size

Edit the generated `Boom_Beach_data_science.slides.html` and add the width and height parameters:

~~~~
Reveal.initialize({
width: 1600,
height: 900,
~~~~
