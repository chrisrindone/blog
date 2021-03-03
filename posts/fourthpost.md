---
title: This is my fourth post.
description: This is a post on My Blog about touchpoints and circling wagons.
date: 2018-09-30
tags: second-tag
layout: layouts/post.njk
---
Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.

Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.

## Section Header

Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.

Implementation Notes
about/index.md shows how to add a content page.
posts/ has the blog posts but really they can live in any directory. They need only the post tag to be added to this collection.
Add the nav tag to add a template to the top level site navigation. For example, this is in use on index.njk and about/index.md.
Content can be any template format (blog posts needn’t be markdown, for example). Configure your supported templates in .eleventy.js -> templateFormats.
Because css and png are listed in templateFormats but are not supported template types, any files with these extensions will be copied without modification to the output (while keeping the same directory structure).
The blog post feed template is in feed/feed.njk. This is also a good example of using a global data files in that it uses _data/metadata.json.
This example uses three layouts:
_includes/layouts/base.njk: the top level HTML structure
_includes/layouts/home.njk: the home page template (wrapped into base.njk)
_includes/layouts/post.njk: the blog post template (wrapped into base.njk)
_includes/postlist.njk is a Nunjucks include and is a reusable component used to display a list of all the posts. index.njk has an example of how to use it.

