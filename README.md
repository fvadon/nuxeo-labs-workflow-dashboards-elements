# About Workflow Dashboards

Workflow Dashboard elements for the Nuxeo.

These are Polymer Web components.

# Instruction

To use this template, there are several places where the names should be adapted to your project:

- README.md: obviously
- bower.json: app name and dependencies (a few are already there that may not be necessary).
- .jshintrc: TimeoffBehaviors ??
- build.xml: project name
- pom.xml: project description and scm info
- gulpfile.js: update DIST var (l50).
- src/main/app/: this is where your app goes. So you should probably start with manifest.json. And then index.html. Routing.html is here to manage sup url within your app.
- src/main/java: if you have java code to deploy on the server.
- scr/main/resources/META-INF/MANIFEST.MF: bundle name.
- scr/main/resources/OSGI-INF/auth-config.xml: url pattern for the app deployed in Nuxeo.
- scr/main/resources/OSGI-INF/deployment-fragment.xml: url pattern again.


# Building

    mvn [-DskipCleanCache] clean install
    

## Deploying
 

To deploy on Nuxeo Platform manually: copy the builded JAR bundles into `$NUXEO_HOME/nxserver/bundles`. Or create a Nuxeo Package to deploy it.

 
 
# Licensing
 
[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)
 
# About Nuxeo
 
Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with
SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris.
More information is available at [www.nuxeo.com](http://www.nuxeo.com).
