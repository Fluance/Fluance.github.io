System environment for OSIP
=====

Infrastructure layer: the key to flexibility
-----

A typical system environment for our framework would consist of several Linux servers (Ubuntu LTS). However, we’ve decided to pack all our components in Docker containers (https://www.docker.com/). This gives us the ability to run our environment on many different types of servers, as long as there is a docker instance or a similar runtime.

Orchestration
-----

To achieve a high availability of our platform, we suggest the use of Kubernetes (https://kubernetes.io/). However, this is not mandatory and must be provided by the customer.

Move to the cloud
-----

By using Docker and Kubernetes, we are by default platform agnostic. OSIP can be installed and operated on all kind of environments. We suggest running it in a cloud environment, because we believe that modern clod offerings are the most secure environments a healthcare institution can afford. However, all common deployment choices are supported i.e. on-premise, private cloud on Amazon AWS, Microsoft Azure or anything else. 

Serverless
-----

If you decide to run part of OSIP in a Microsoft Azure Cloud environment, we can use some native serverless components. Usually these perform better than the same system in a Docker container.

----
**Table of Contents**

[A. Introduction](A_introduction.md)

[B. Innovation and Open Technology](B_innovation_and_open_technology.md)

[C. OSIP Functionality](C_osip_functionality.md)

[D. Outside the current scope of OSIP](D_outside_the_current_scope_of_osip.md)

[E. Main Components of OSIP](E_main_components_of_osip.md)

F. System environment for OSIP

[G. Implementation scenarios](G_implementation_scenarios.md)
