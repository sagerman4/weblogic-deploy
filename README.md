# weblogic-deploy
Simple ant build file for deploying and undeploying artifacts from/to WebLogic servers.

By the way, y'all: you'll need a properties file called 'weblogic.properties' with a property in it like so:

weblogic.lib.dir=<your weblogic home>/wlserver_10.3/server/lib

Just put that in the root directory of the checkout.  The gitignore file will ignore it for ya.
