To install this script: [with root privilege]
 Edit the script to change the path of the location of codeBeamer MR and the user that it was installed under.
 Copy to /etc/init.d
 chmod +x /etc/init.d/cmr-svn
 
To start the script:
/etc/init.d/cmr-svn start

RHEL: 
service cmr-svn start

Setup the service to start on boot [this may changed based on your distro]
rc-update.d add cmr-svn default [For gentoo]
update-rc.d cmr-svn defaults
