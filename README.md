# weblogic-deploy
Simple ant build file for deploying and undeploying artifacts from/to WebLogic servers.

By the way, y'all: you'll need a properties file called 'weblogic.properties' with properties in it like so:

weblogic.lib.dir=<your weblogic home>/wlserver_10.3/server/lib
weblogic.user=<admin user name>
weblogic.password=<admin user password>
weblogic.targets=<targets, default being AdminServer>

Just put that in the root directory of the checkout.  The gitignore file will ignore it for ya.
