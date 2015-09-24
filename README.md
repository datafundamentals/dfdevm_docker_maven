# dfdevm_docker_maven

This is a special use case cookbook for when you need to run 'mvn docker:build' against a maven project which is designed to create containers using maven-docker-plugin

It also has java oracle 8

It is designed to be run from kitchen converge, and has not been tested thoroughly. In that sense it is a quick, pragmatic cookbook and probably unsuitable for general use.

If you are consuming this cookbook yourself, you would probably want to tailor the kitchen.yml file to suit your own needs, such as shared folders, vm memory, ip address, such as that.
