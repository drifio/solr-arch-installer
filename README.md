# solr-arch-installer
Install script for Solr 8.5.1.

Old version of Solr on the AUR installed to /opt/solr, and seemed to function as expected. However, that version has disappeared and a version has appeared on the official packages list.

This new version added doesn't seem to function correctly, so ultimately I needed to manually install. The install script that comes with Solr doesn't support Arch, so this repository contains a modified version of that script, along with a systemd definition to install and create the service.
