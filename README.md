Moodle-Dspace-Plugin
====================

This is a Moodle plugin to import learning objects from DSpace and link them in Moodle.

This plugin allows you to download a learning object from DSpace and make a link to it in Moodle in one operation. It integrantes Moodle and DSpace through using the [DSpace REST API](https://wiki.duraspace.org/display/DSDOC6x/REST+API).

This is a fork of [original code](https://github.com/pmarrone/Moodle-Dspace-Plugin) adapted to the needs of [UP2U project](https://up2university.eu/).

Useful Links
------------

[Source Code](https://github.com/up2university/Moodle-Dspace-Plugin/tree/up2u)

Installation
------------

1.	Place the 'Moodle-Dspace-Plugin' folder to Moodle's repository folder
2.	Inside Moodle, log-in with administrative privileges and go to *site administration > Plugins > Repositories > Manage Repositories*
3.	Find *DSpace Repository* plugin and enable it.
4.	Configure *DSpace Repository* (enter settings)
5.	Create a repository Instance enter the *Name* and *DSpace REST API URL* (example: http://localhost:8080/rest/) and save

The plugin requires the DSpace REST API access restrictions to be deactivated.
