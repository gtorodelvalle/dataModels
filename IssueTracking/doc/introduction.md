# Issue Tracking data models

These data models allow to perform civic issue tracking. They have been designed with a view to enabling interoperability
between FIWARE NGSI version 2 and [Open311](http://www.open311.org/). As a result property names have not been
normalized to the `camelCase`syntax, they remain as specified by Open311. That is the rational behind naming entity
types with a `Open311` prefix. However, additional properties are added so that FIWARE NGSI version 2
implementations can properly store and serve Open 311 data.

In the future FIWARE and OASC can propose Open311 a harmonized data model aligned with the rest of FIWARE data models. 

The issue tracking data model defines the following entity types:

+ [Open311:ServiceType](../Open311ServiceType/doc/spec.md). A type of service a citizen can request.  
+ [Open311:ServiceRequest](../Open311ServiceRequest/doc/spec.md). A specific service request (of a service type) made by a citizen. 
