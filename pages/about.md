---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: cities391
# set background-position for featured image, "center", "top", "bottom"
position: center
# major heading to display over featured image
heading: Learn About Awesome Stuff
# paragraph text below heading in featured image
sub-heading: Now!
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 6em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

## Learn More

{% include feature/alert.html text="Watch out!" color="warning" align="center" %}

This is random paragraph content!
This a paragraph.

{% capture example %}
### Example Stuff

This a paragraph.
Hey everyone!

- cats 
- dogs
- muffins

More info.
{% endcapture %}

{% include feature/collapse.html button="Answer One" color="primary" text=example %}

## Quiz

{% include feature/collapse.html button="Learn More" color="success" text="Such an interesting story!" %}

{% include feature/cloud.html fields="subject;creator" min=2 %}

## More Images

{% include feature/image.html objectid="cities851" width="25" caption=false %}

### Also 

Importantly, you should look at these:

{% include feature/image.html objectid="cities851;cities1049" %}
