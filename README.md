# AutoGroup Local Plugin

Automatically assigns enrolled users on a course into groups
dependant upon information within their user profile.

This plugin will create, update, and delete groups automatically
to match the users on your course. All behaviour is event-driven
and so will occur within page loads.

The system can also monitor manual group setting changes and
moderate them to ensure that groups are kept neat and tidy.

## Changelog
* v2.2 
  * Performance enhancement: Event listeners now check to see whether triggered by AutoGroup 
* v2.1
  * Switched to individual toggles for event listeners
  * Minor change to settings structure for improved usability
  * Fixed compatibility with Moodle 3.1 and onwards
* v2.0
  * Added support for defining multiple grouping sets on one course
  * Sort modules are now fully modular
  * Added new sort module for Totara positional assignments
* v1.1
  * Fixed a bug which would have resulted in roles being removed from all groupsets across a site
  * Changed default permissions for plugin files 
* v1.01
  * Added event handler for course_restored and related setting
* v1.0
  * Stable release. Tested for compatibility with Moodle 2.7 and 2.8

## Install

1. Copy the plugin directory "autogroup" into moodle\local\.
2. Check admin notifications to install.

## Maintainer

The module was authored and is being maintained by Mark Ward (me@moodlemark.com).

## Thanks to

Development for v1.0 of the plugin was funded by East Central BOCES (http://www.ecboces.org/)

Many ideas and suggestions for the functionality of the plugin were contributed
by Emma Richardson at East Central BOCES.

## Technical Support

Issue tracker can be found on [GitHub](https://github.com/markward/local_autogroup/issues). Please
try to give as much detail about your problem as possible and I'll do what I can to help.

## License

Released Under the GNU General Public Licence http://www.gnu.org/copyleft/gpl.html
