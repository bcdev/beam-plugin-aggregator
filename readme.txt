BEAM Plugin Aggregator

The purpose of this project is to aggregate multiple BEAM related projects for easier
build configuration on our TeamCity build server.

Plugins which shall be aggregated must be added as module to the pom.xml file.
For each module a SCM connection must be configured within the related projected on the TeamCity server.
So remember to add a SCM connection to TeamCity when adding a module to the pom.