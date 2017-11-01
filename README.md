Condensation: It how clouds are made.
=====================================

Version 0.1

Condensation is a tool for building images for compute clusters using Apache Mesos and Spark. Currently it only supports Docker images, but the build system (packer) is flexible and can build images for VMWare, OpenStack, etc. with a little more work.

You need Docker and Packer.io v1.1.1 to use this. Not guarenteed to work with newer versions of Packer, but it just might.

The included compose.yml can set up a simulated cluster on your own machine. It uses Docker-Compose.

TODO:
-----
More image types (especially OpenStack)

Use Apache Ambari
