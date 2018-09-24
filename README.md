# elda-standalone
Virtuoso Frontal (ELDA)

1. Deployment:
    1. Clone this repository in your localhost.
    2. Import to eclipse.
    3. Export as WAR file.
    4. Remove standalone.war from /data/apps/tomcat/webapps/standalone.war and wait until standalone/ directory will removed.
    5. Copy the new standalone.war to /data/apps/tomcat/webapps/ and wait until new standalone/ directory will deployed.
    6.	Copy .ttl files from /data/assets/elda/specs/ into /data/apps/tomcat/webapps/standalone/specs/