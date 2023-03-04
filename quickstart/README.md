<!--
  ~ Copyright (c) VMware, Inc. 2023. All rights reserved.
  ~ SPDX-License-Identifier: Apache-2.0
  -->

# VMware GemFire Quick Start examples
The examples in this folder are practical guides to getting started with GemFire.

For details on all GemFire features, see [VMware GemFire Documentation](https://docs.vmware.com/en/VMware-GemFire).

## VMware GemFire Version
Your client code must link against the _same or older_ version (ignoring patch versions) of VMware GemFire as the VMware GemFire server it will connect to.

To link against a different version of GemFire, edit the `<version>` tag for each com.vmware.gemfire dependency in `pom.xml` in each quickstart.

## Prerequisites

In order to execute the examples in this project, follow these steps:
1. Ensure [JDK 11](https://bell-sw.com/pages/downloads/) or JDK17 is installed.
1. Ensure [Maven 3.6](https://maven.apache.org/download.cgi) or later is installed according to mvn [installation instructions](https://maven.apache.org/install.html).
1. Each quickstart below will guide you through remaining setup steps such as downloading GemFire, setting GEMFIRE_HOME, and configuring a "commercial repo" account.

### Quick Starts

* [Client-Server Intoduction](quickstart/001_client_server_introduction/README.md)
* [Client Object Instances](quickstart/002_client_server_user_objects/README.md)
* [Client JSON](quickstart/003_client_server_json/README.md)