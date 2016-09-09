social-colors-scss
===========

## Simple sass social media color variables and utility classes
(based on schmittyjd/colors-scss which was based on mrmrs/colors, colors taken from koycarraway/_vars-social-colors.scss)

This Sass package will add a bunch of Sass variables and CSS utility classes for different social media and other web properties, saving you *literally tens of seconds* of work.

### Installation
with bower
<pre>$ bower install social-colors-scss --save</pre>

Then import it in your main.scss (or other .scss) file
```scss
@import "colors"; // (or path to colors if not in root relative to stylesheet)

.facebook-colored-thing {
  background-color: $color--facebook;
  // etc
}

```

### CSS Utility Classes

For each property, five vaguely useful utility classes will also be generated.

e.g. for "Facebook", we'll get:

```
.color--facebook { color: #365396; }
.bg--facebook { background-color: #365396; }
.border--facebook { border: #365396; }
.fill--facebook { fill: #365396; }
.stroke--facebook { stroke: #365396; }

```

Apparently those last 2 are for SVGs or something. Whatever!

### Included Brands

 - amazon
 - apple
 - basecamp
 - box
 - dribbble
 - dropbox
 - ebay
 - facebook
 - flickr
 - foursquare
 - github
 - google
 - google_plus
 - instagram
 - linkedin
 - pinterest
 - skype
 - tumblr
 - twitter
 - vimeo
 - yelp
 - youtube

Thx to koycarraway/_vars-social-colors.scss for these.

Do people actually use linkedin?