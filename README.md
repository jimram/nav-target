# nav:target

## Simple, Semantic, Script free, Accessible Navigation pattern.

### Structure

The navigation sits at the bottom of your document with an id of "#main-naviagtion". 

In the header you place a 'jump to link' with a href of "#main-naviagtion".

When triggered the navigation is positioned at the top of the viewport and slides into position using CSS transitions.

Within the navigation element there's another 'jump to link' - this one has a blank href of "#" which triggers the navigation to close.

Simples.

#### Browser support
Works perfectly in all modern browsers and IE9+.

In browsers that don't support :target or css transitions it degrades to a simple jump menu.

[View Demo](demo/index.html)
