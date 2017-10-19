Smoke Mixcloud Integrator
=========================

Wordpress plugin implementing a simple AngularJS application to display podcasts and allow them to be played in an embedded player.

Use it with the shortcode [mixcloud-integrator].

The plugin uses the Mixcloud API to list shows published by a given account, and makes a second call to retrieve the embed player HTML for a particular podcast when the user tries to play one.

Installation
------------

Just add the files as a folder to your site's `plugins` directory.

You can turn off the default styling by commenting out line 13 in `mixcloud-integrator.php`. You can change the Mixcloud station used in `/js/service.js` on line 6.
