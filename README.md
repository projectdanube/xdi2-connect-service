<a href="http://projectdanube.org/" target="_blank"><img src="http://projectdanube.github.com/xdi2/images/projectdanube_logo.png" align="right"></a>
<img src="http://projectdanube.github.com/xdi2/images/logo64.png"><br>

This is a "Connect Service" component for the XDI Browser binding.

### XDI Connect

This is part of a set of projects related to XDI Connect:
* [xdi2-connect-core](http://github.com/projectdanube/xdi2-connect-core)
* [xdi2-connect-service](http://github.com/projectdanube/xdi2-connect-service)
* [xdi2-connect-auth-service](http://github.com/projectdanube/xdi2-connect-auth-service)
* [xdi2-connect-acmenews](http://github.com/projectdanube/xdi2-connect-acmenews)
* [xdi2-connect-acmepizza](http://github.com/projectdanube/xdi2-connect-acmepizza)

### Information

TODO

### How to build

First, you need to build the main [XDI2](http://github.com/projectdanube/xdi2) and the 
[xdi2-connect-core](http://github.com/projectdanube/xdi2-connect-core) projects.

After that, just run

    mvn clean install jetty:run

Then the Connect Service is available at

	http://localhost:9201/

### How to use

Maven repository for releases:

        <repositories>
                <repository>
                        <id>XDI2</id>
                        <name>XDI2-releases</name>
                        <url>https://artifactory.xdi2.org/xdi2-releases-local</url>
                </repository>
        </repositories>

Maven repository for snapshots:

        <repositories>
                <repository>
                        <id>XDI2</id>
                        <name>XDI2-releases</name>
                        <url>https://artifactory.xdi2.org/xdi2-snapshot-local</url>
                </repository>
        </repositories>

Maven dependencies:

        <dependencies>
                <dependency>
                        <groupId>xdi2</groupId>
                        <artifactId>xdi2-connect-service</artifactId>
                        <version>... version here ...</version>
                        <scope>compile</scope>
                </dependency>
        </dependencies>

### Community

Website: https://xdi2.org/

Google Group: http://groups.google.com/group/xdi2

Weekly Call: [Thursdays at 4pm US Eastern Time](https://github.com/projectdanube/xdi2/wiki/XDI2-Weekly-Call)

IRC: [irc://irc.freenode.net:6667/xdi](http://webchat.freenode.net?randomnick=1&channels=%23xdi)

