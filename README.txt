=== Toggle PSD ===
Contributors: codenameEli
Tags: toggle,psd,overlay,image,design,development,developer,dev,devtool,pixelperfect,launchdm
Tested up to: 4.1
Stable tag: 1.3
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Develop your site pixel-perfect by overlaying the comp!

== Description ==

This plugin enables the developer to toggle the overlay the comp of the site with just the click of a button. Stop going back and forth between your browser and Photoshop to get the height or margin between elements and live-edit 'til it lines up exact!

Upon installation, the plugin will create a CPT called "Toggle PSD". This is where you can add and remove images of the design as needed. The title is used as a label on the dropdown menu. The featured image is the design image.

== Installation ==
1. Upload `toggle-psd` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. In the WordPress Dashboard, go to Toggle PSD -> Add New
1. Enter a title for the overlay (e.g. Homepage)
1. Upload the image of the design (homepage.jpg) and click "Publish"
1. Go to homepage of your site and hover over the "Toggle PSD" admin bar item at the top
1. Click on the overlay you want to display

== Features ==
- :cookie: to remember the last selected item
- Clicking the "Toggle PSD" admin bar item will toggle the last selected item
- <kbd>~</kbd> toggles the last selected item
- Right-clicking on the overlay will hide it for 3 seconds, so that you can inspect an element without having to toggle. The overlay will toggle back on in 3 seconds on its own.

== FAQ ==
1. Where is the negative margin being set?
It is being set in Javascript. It takes the width of your image, halves it and sets that to the negative margin.

== Screenshots ==

1. Toggle PSD in action
