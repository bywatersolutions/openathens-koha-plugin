openathens-koha-plugin
==================

openathens-koha-plugin

Tested on Koha v 16.11+

Switch to Koha-v17.11x branch for Koha v 17.11 supprt

End of Support Notice
==================
EBSCO now supports OpenAthens Logins through an internal connection service leveraging ILS-DI.  No additional development will be done on this plugin.

Quick Installation steps
==================

Download the package file oa_Plugin_xx.kpz

Login to Koha Admin and go to Tools-> Plugin ( Make sure Koha plugin is enabled)

Upload Plugin

Click on Run Tool and follow instructions.

Click on Configure and enter required details from OA admin.

Troubleshooting
==================
Apache may need to be configured to correctly run the plugin

See https://github.com/ebsco/edsapi-koha-plugin/wiki/Apache-Setup for more details

Technical
==================
TLS 1.2+ is required on the Koha server.
See http://docs.openathens.net/display/public/MD/Implementing+the+API+connector+in+your+code
