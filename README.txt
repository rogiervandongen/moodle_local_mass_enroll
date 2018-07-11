moodle_local_mass_enroll
========================

In memory of Patrick Pollet who was the original maintainer of this plugin until Moodle v2.8, I have been updating this repository seperately to keep it compatible with progressing versions. Developers are welcomed to contribute to this. Pull requests will be reviewed and merged.

A Moodle tool for all teachers to enrol/unenrol existing users to their courses using CSV files (without bothering their admins)

Main features are :

* users can be specified by username, id number or email 
* users can be optionnally enroled to groups/groupings (autocreated if needed)
* email reports can be send
* import can be repeated if some users are to be in several groups
* usage can be restricted by modifying specific capabilities (local/mass_enroll:enrol and local:/mass_enroll:unenrol) 
* can be inserted in Course's admin menu or called from a specific Moodle block 

This plugin is test until Moodle 3.4 after contributing codes to match compatibilies.

See the wiki page https://github.com/patrickpollet/moodle_local_mass_enroll/wiki for installation and usage. 
