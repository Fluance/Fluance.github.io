OSIP Functionality
======

Data Collection
------

One of the primary functions of the OSIP is to collect and store data, from any system. This is especially useful when connecting to legacy systems that do not have easily accessible data stores through open API’s, and have therefore built up ‘siloed’ data. The OSIP provides a mechanism for such silos to be accessed and data stored in a secure but open and vendor-neutral repository. It also means that the information and granularity of the original data is kept and made accessible without the original system.

Data Aggregation
------

As the data repository grows, it can be aggregated in any way the organisation chooses. Increasingly, a patient-centric view of the data is needed to provide a holistic view of the patient e.g. lab data from different providers could be structured in chronological order rather than by provider. This is just one example and essentially the type and method of aggregation should be dictated by the organisations needs and focus.

Data Federation
------

Storing data is the first step, but the real goal is to use this data in a clinical environment, providing the clinician with the right information at the right time to best provide care for the patient. Therefore, we need to make this data accessible. To achieve this we built easy-to-use APIs and a security layer. This is the ESB or Enterprise Service Bus. This middleware ensures that the right data is available in the right place to authorised providers. A log and audit trail is also built in by default. 

Data Transformation
------

There are many reasons to transform data from supplying it in a different format to third party systems to generation of new information based algorithms utilising existing data.  This can easily be accomplished with the OSIP. 

Identity Federation
------

In healthcare you often have a mix of corporate identities, usually on a Microsoft Active Directory and a multitude of system based user identities. The OSIP can federate existing identities as long as they conform to an established security standard. In addition to that it can provide and maintain identities of its own. Both can be used by third parties giving the ability, to use common logins for all connected parties.

Enabling innovation on legacy systems
------

Being modular, open source and open standard the OSIP can easily be adapted to existing environments. It is possible to build a modern ecosystem without compromising the role or functionality of key systems in use. These systems do not have to be replaced before it is necessary and the data they hold is also secure in a separate repository minimising the need for costly data migration activities. 

Bridge the gap
------
In most healthcare environments, the changing business needs dictate the priorities and this often leaves gaps in the overall system architecture. The OSIP can act as an integrator, translator and interpreter between systems that are unable to interact directly. In addition to simple point-to-point integration the platform provides full control over your data and monitoring of activities.

Web Apps
------

Sometimes you have the data but not the right user interface. OSIP can provide its own app environment. These web apps are easy to develop and adapt to specific needs and need no installation. They run on all modern platforms as long as the UI suits the screen size.

----
**Table of Contents**

[A. Introduction](A_introduction.mdl)

[B. Innovation and Open Technology](B_innovation_and_open_technology.md)

C. OSIP Functionality

[D. Outside the current scope of OSIP](D_outside_the_current_scope_of_osip.md)

[E. Main Components of OSIP](E_main_components_of_osip.md)

[F. System environment for OSIP](F_system_environment_for_osip.md)

[G. Implementation scenarios](G_implementation_scenarios.md)
