# DDA_Assignment
Database Tables: Tables created in SAP HANA database to store, read, and modify.

CDS Views: Virtual data models of SAP HANA that allow direct access to underlying tables of the HANA database. Annotations can be used to add metadata to the data model.

CDS Projections: The top-most layer of a CDS data model that expose data of an underlying CDS view for a dedicated business use case.
Metadata Extensions: Enables to write UI annotations for a CDS (consumption) view in a different development object to separate them from the CDS view.
Behavior Definitions: A crucial aspect of any CDS data model that defines the actions that can be performed on the data, such as creating, updating, and deleting records.
Behavior Implementation: Class	Classes in which the behavior specific procedures can be implemented like validation, transformation, calculation, etc., during the CRUD operations.
Behavior Projections: Projection for the behavior of a CDS projection view that contains the existing properties of a behavior definition with the provision to extend the behavior based on the business use case.
Service Definition: Describes the CDS entities (projections) of a data model to be exposed so that a specific business service can be handled.
Service Binding: ABAP Repository object used to bind a service definition to a client-server communication protocol such as OData.
Fiori Elements: A frontend framework that comprises the most commonly used floorplan templates and is designed to speed up development by reducing the amount of frontend code needed to build SAP Fiori apps (WebApps).
