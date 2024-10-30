=== Loading Screen by Imoptimal ===
Contributors: imoptimal
Tags: loading, loading screen
Requires at least: 4.9.8
Tested up to: 5.5.1
Requires PHP: 5.6
Stable tag: trunk.
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

== Description ==
Complement your branding efforts by enabling a loading screen progress bar (with percentage text) on your website, that features the logo/image of your choosing.

Key Features:
* Possibility to set the number of loading screen options your website needs (either one for the entire website, or two different ones - first for the homepage, second for all of the other pages).
* Select the logo image that will be used on the loading sccreen (from the existing uploads, or by uploading a new one).
* Select the background color for the loading screen.
* Select the color of progress bar and percentage text.

== Installation ==

1. Login to your WordPress admin area
2. Search for 'Loading Screen by Imoptimal'
3. Click to install 'Loading Screen by Imoptimal'
4. Activate through the Plugins menu in WordPress or when asked during installation
5. Set your options from the Settings -> 'Loading Screen by Imoptimal' admin area

Alternatively:
1. Download the plugin from official wordpress.org/plugins page.
2. Unzip it and upload the folder loading-screen-by-imoptimal to the /wp-content/plugins/ directory.
3. Activate the plugin through the Plugins menu in WordPress.
4. Set your options from the Settings -> 'Loading Screen by Imoptimal' admin area

== Frequently Asked Questions ==
 
= What if I'm using a lazy-load plugin for images on my website, does it effect the selected loading screen logo/image =

Yes, it does have an effect - the selected logo/image is loaded with additional delay, which makes it visible only in the last half a second or so.
My recommendation is to find a plugin that enables you to choose which css class to exclude from the effect of lazy-load (use the class 'imoload-preview-image').
I personally use the plugin 'Smush' by WPMU DEV for lazy-loading of images. It's a free plugin, and provides other image optimization options as well.

== Screenshots ==

1. This is where you'll find the settings page in your admin dashboard
2. Meta options section in the settings page
3. Collapsible instructions section in the settings page
4. Loading Screen options section in settings page
5. Collapsible Loading Screen options item section in the settings page

== Changelog ==

= 1.0.0 =
Plugin released.

= 1.0.5 =
Readme file update - added full resources list and plugins.
Added plugins uri link.

= 1.1.0 =
Enabling webpage content to be hidden before the javascript powered loading screen starts.

= 1.1.5 =
Updated the loading logo/image style.

= 1.2.0 =
Cleaning the javascript code.

= 1.2.1 =
Set the default plugin values upon activation.

= 1.2.2 =
The plugin's settings page submit button ajax request modified in order to reset the button style and remove notices after 2 sec.

= 1.2.3 =
Added support and review links on the plugin settings page.

= 1.2.4 =
Moved the user-facing css code into the javascript file.

= 1.2.5 =
Reverting back. Loading screen messed up without css files.

= 1.2.6 =
Plugin assets updated.

== Copyright ==

Loading Screen by Imoptimal, Copyright 2020 Ivan Maljukanovic
Loading Screen by Imoptimal is distributed under the terms of the GNU GPL

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/gpl-3.0.en.html/>

== Resources ==
* jscolor.js 2.0.5, GPLv3 - available @ http://jscolor.com/
* imoptimal-logo-white.png © 2020 Ivan Maljukanović, CC0 - made by me, not available online apart from the plugins directory /img, and my personal website @ https://imoptimal.com (used as an asset)
* banner-772x250.png © 2020 Ivan Maljukanović, CC0 - made by me, not available online apart from the plugins official wordpress.org repository (used as an asset)
* icon-256x256.png © 2020 Ivan Maljukanović, CC0 - made by me, not available online apart from the plugins official wordpress.org repository (used as an asset)

Resources used in the plugins last screenshot (number 5):
* Photo of my cat Mizza © 2010 Swanheart, CC0 - made for me on my request; given to me free of charge; not available online
