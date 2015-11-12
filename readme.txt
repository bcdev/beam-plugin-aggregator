BEAM Plugin Aggregator

The purpose of this project is to aggregate multiple BEAM related projects for easier
build configuration on our TeamCity build server.

Plugins which shall be aggregated must be added as module to the pom.xml file.
For each module a SCM connection must be configured within the related projected on the TeamCity server.
Also an additional build step, which builds the assembly, can be added for the new module.
Finally the assembly must be added to the list of artifact paths.
The already existing modules may serve as template.
