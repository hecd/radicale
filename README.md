Role Name
=========

A role installing and configuring Radicale for Debian 9 for use by an nginx reverse proxy.

Requirements
------------

TBA

Role Variables
--------------
radicale_port: port radicale server listens on. Currently supports localhost ports only.
radicale_rights_file: path where radicale rights configuration is stored
radicale_shared_calendar_collection_name: name of the globally (between all authenticated users) shared calendar.
radicale_shared_contacts_collection_name: name of the globally (between all authenticated users) shared contacts collection.
radicale_filesystem_folder: path where radicale collections are stored.

Dependencies
------------
TBA

Example Playbook
----------------
TBA

License
-------

GPLv3

Author Information
------------------
TBA
