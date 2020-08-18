---











<!--more-->

Here's a list of classes that you can add to your markup to make it happen.

* 	<i class="icon-angle-right"></i> **flipboard-remove** — will ignore any element with this class
* 	<i class="icon-angle-right"></i> **flipboard-keep** — will use this element in the article e.g tagging a paragraph with this will insure it remains part of the excerpt
* 	<i class="icon-angle-right"></i> **flipboard-image** — will use the element as an image
* 	<i class="icon-angle-right"></i> **flipboard-title** — will use as title
* 	<i class="icon-angle-right"></i> **flipboard-subtitle** — will use subtitle
* 	<i class="icon-angle-right"></i> **flipboard-author** — use as author
* 	<i class="icon-angle-right"></i> **flipboard-copyright** – set copyright
* 	<i class="icon-angle-right"></i> **flipboard-date** — set the date of the article
* 	<i class="icon-angle-right"></i> **flipboard-caption** — set as caption for an image; must be immediately after the image
* 	<i class="icon-angle-right"></i> **flipboard-startArticle and flipboard-endArticle** — only consider the markup between flipboard-startArticle and flipboard-endArticle


Simple example for date using wardrobe:
	
	<div class="date flipboard-date">{{ date("M/d/Y", strtotime($post->publish_date)) }}</div>
	
This way you can control a bit more on what content should be displayed on Flipboard.

	