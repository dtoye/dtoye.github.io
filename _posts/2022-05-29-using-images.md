---
layout: post
title: Using Images
date: 2022-05-29 23:21 -0400
categories: [Documentation]
tags: [jekyll, howto]
---

# imagebam.com

Looks like a free site where I can post images that my web pages can display. No clue how they make money. I'm debating whether just to download the images to the assets directory and use it from my own site. Just in case the site goes vaporware.

## Rotating the image

add the following to rotate the image 90 degrees

'''bash
style="transform:rotate(90deg);"
'''

### Example

'''bash
<a href="https://www.imagebam.com/view/MEB2ETV" target="_blank"><img src="https://thumbs4.imagebam.com/18/04/fa/MEB2ETV_t.jpeg" alt="7159C4FB-8033-414A-BDCD-F1A7BB5CAD1C.jpeg" style="transform:rotate(90deg);"/></a>
'''

<a href="https://www.imagebam.com/view/MEB2ETV" target="_blank"><img src="https://thumbs4.imagebam.com/18/04/fa/MEB2ETV_t.jpeg" alt="7159C4FB-8033-414A-BDCD-F1A7BB5CAD1C.jpeg" style="transform:rotate(90deg);"/></a>
