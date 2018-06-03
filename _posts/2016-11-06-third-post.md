---
layout: post
title: Third Post from Jeff
postHero: /images/pyramid.jpg
author: Jeff Harper
authorTwitter: http://twitter.com/jeff_harper
gravatar: /images/jd_avatar.jpg
postFooter: Additional information, and maybe a <a href="#">link or two</a>
---

Try playing around by adding new posts, changing the date, changing the filename to see how Jekyll builds URLs, and changing the frontmatter to have different titles, authors, etc. You now have a super-simple blog! Jekyll has a lot more bells and whistles that can make your blog even fancier, which you can learn about by reading the [Jekyll documentation](https://jekyllrb.com/docs/home/).



Is your programmer’s itch acting up again? Do you see what we’ve repeated on both the blog index page and blog detail page? This repetition cannot stand! Refactor the site by moving the recent post list into its own include, and then load that include on both the blog index and detail pages.

<img class="pull-left" src="images/Jeff-mark-camels.jpg"
     alt="camel riders">

One last little Jekyll Liquid tag trick before we move on. You might at some point want to add a link on the site, or a small description, that can direct users to the most recent blog post. Let’s first add a link in the header as the last navigation link. Open up _includes/nav-links.html and add in the changes in Listing 179.

Flipping between the two pages, you’ll see that things are looking pretty organized, and the content is looking good (Figure 193). Notice that for the post content we bumped up the font size of the text to 1.2rem. It is always nice to have slightly larger type for sections of content that are text-heavy for readability—a font size in the range of being equivalent to 16px to 18px is a good target.