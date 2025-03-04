upload of the web server cluster module example from Terraform-up-and-running-V3.

# What does this module do

This module contains a configuration that allows to deploy a cluster of web servers on Amazon AWS.
This configuration includes a load balancer that can be connected to over port 80 which will return a text page stating: "Hello, World" .

## Quick start

Terraform modules are not meant to be deployed directly. Instead, include them in other Terraform 
configurations. See [stage/services/webserver-cluster](../../../stage/services/webserver-cluster) and
[prod/services/webserver-cluster](../../../prod/services/webserver-cluster) for examples.
