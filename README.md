check_mk-nut
===================

this has been updated to work with check_mk raw version 1.6.0p15.cre (tested on Ubuntu 20.04)
also contains some cosmetic improvements and the pull requests unaccepted by the original author

How to use:
- make sure you have nut set up and running - verify you get corret info displayed when running `upsc yourupsname`.
- install check_mk raw as described in the manual
- once installed, get the .deb agent from the webui of check_mk and install it alongside
- copy to /usr/lib/check_mk_agent/plugins the correspondig plugin file. Make it executable.
- copy to /opt/omd/versions/default/share/check_mk/checks the correspondig check file.
- copy to /opt/omd/versions/default/share/check_mk/checkman the corresponding man file (optional - it has syntax errors I couldn't figure out how to correct).

Create a site, and a host, 127.0.0.1 at IP address and good luck!
