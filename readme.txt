=== Show More for P2 ===
Contributors: kylesureline
Donate link: http://www.kylescheuerlein.com/
Tags: p2, excerpt, show, more
Requires at least: 4.5.3
Tested up to: 4.7
Stable tag: `/trunk/`
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Automatically turn all posts into excerpts of 300 characters and add a "Show More" link that will load directly in the page.

== Description ==

Automatically turn all posts into excerpts of 300 characters and add a "Show More" link that will load directly in the page. If your post includes a picture, it will also obtain a thumbnail and place that at the beginning of the excerpt. Supports Infinite Scroll, too (assuming you manually enabled it on your P2 site)!

* Shorter posts will be left alone, unless they have a picture
* Posts with a picture will always be turned into a thumbnail/excerpt
* Expanding or contracting a post will scroll to the top of the post

Planned:

* Long posts with embedded video and no image include the video in the excerpt
* Change the character length from the admin screen

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress

== Frequently Asked Questions ==

= Infinite Scrolling isn't working on my P2 site =

You'll need to enable it manually. This plugin won't do that for you.

== Screenshots ==

1. Example of a P2 blog with plugin enabled.
2. Sample post excerpt.
3. Expanded full post.
4. Sample of thumbnail.
5. Expanded post with picture.

== Changelog ==

= 1.3.3 =
* Clicking on thumbnails will expand posts
* Clicking on blog post titles will expand posts

= 1.3.2 =
* Fix excerpts on archive/category/search pages
* Preserve the title on blog posts when making an excerpt

= 1.3.1 =
* Fix cache busting of jQuery file

= 1.3 =
* Bug fixes

= 1.2 =
* Fix thumbnail generation for externally hosted images
* Fix thumbnail generation for various sizes (Large, Medium) and alignments

= 1.1 =
* Fix thumbnail generation for all images

= 1.0 =
* Plugin release

== Upgrade Notice ==

= 1.0 =
* Plugin release
