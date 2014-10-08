Customsize Groupimage for Elgg 1.8
Latest Version: 1.8.0
Released: 2014-10-08
Contact: iionly@gmx.de
License: GNU General Public License version 2
Copyright: (c) iionly 2014


This plugin fills the gap of the missing "master"-sized group image icon as long as this issue is open in Elgg core. Instead of the missing re-sized master image it serves the original uploaded image instead.

For group profile pages it replaces the "large"-sized version of the group image icon with the master (= original sized) image by registering the "customsize_groupimage_hook" callback function for the 'entity:icon:url', 'group' plugin hook. This results in the "large"-sized group icon image to get replaced by the master/original image wherever it's used. If you don't want the "large" image to be replaced but only want the original image where you explicitly call for the "master" group icon, comment out the registering of the "customsize_groupimage_hook" plugin hook.


1. Copy the customsize_groupimage plugin folder into the mod folder on your server,
2. Enable the plugin in the admin section of your site.


Changelog

1.8.0
- Intial release for Elgg 1.8.
