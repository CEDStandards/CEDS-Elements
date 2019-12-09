![CEDS Elements Logo](/res/CEDS-Elements-Logo-Full-Medium.png "CEDS Elements")

# CEDS Elements 
Welcome to the CEDS Open Source Community! 

The Common Education Data Standards (CEDS) are an education data management initiative whose purpose is to streamline the understanding of data within and across P-20W institutions and sectors. CEDS includes a common vocabulary complete with standard element names, definitions, and option sets. This repository contains all the CEDS elements, definitions, option sets and their definitions, and entities and definitions. Its purpose is to expand that vocabulary to meet the needs of every education stakeholder. The expanded vocabulary is then added to the CEDS Standard and the CEDS Integrated Data Store, as appropriate.

## Getting Started
CEDS is an evolving standard that continually expands the vocabulary to meet the needs of every education stakeholder. Therefore, in order to add or change an element, a use case that describes the justification for the addition or change must be submitted in GitHub Issues.

## Submitting a Use Case
Use cases may be submitted through the [Issues](https://github.com/CEDStandards/CEDS-Elements/issues) tab by clicking on **New Issue** and then **Get Started** which is located next to **CEDS Element and/or Option Set Use Case**.

## Contributing
Please read [Contributing.md](https://github.com/CEDStandards/CEDS-Elements/blob/master/Contributing.md) for details on the process for submitting pull requests.

## Versioning 
The CEDS open source community uses a customized version of Explicit Versioning. To keep the various CEDS open source projects in alignment with the CEDS Elements, the concept of "disruptive" releases has been replaced with "alignment" releases. These releases ensure that the data models are in sync with the official, CEDS community approved list of CEDS Elements. For the versions available, see the tags on this repository.

Here is an example of how explicit versioning will occur.

Assuming an official release of CEDS has just occurred:

Data Warehouse (DW) version = 7.0.0.0
Integrated Data Store (IDS) version = 7.0.0.0
CEDS Elements = 7.0.0.0

Use Case:

Brand new elements are introduced to CEDS, because they are new, they represent no breaking change to any of the other CEDS elements:

CEDS Elements version = 7.0.1.0

These new elements, however, result in a new understanding of how data is integrated in the IDS resulting in a restructuring of the IDS which is not backwards compatible.

IDS version = 7.1.0.0

These elements are added to the DW structure and result in backwards compatibility, but a defect is identified in doing so that needs to be corrected.

DW version = 7.0.1.1
Throughout the remainder of the year, many changes occur in each of the different repositories. The changes prior to the annual release of CEDS results in the following:

DW version = 7.27.1.6
IDS version = 7.3.2.0
CEDS Elements = 7.2.18.2

The annual official CEDS release occurs, typically around January/February of the calendar year. All resources are brought into version alignment (Note: no changes occurred to the resource, the annual release simply restarts/aligns the versioning):

DW version = 8.0.0.0
IDS version = 8.0.0.0
CEDS Elements version = 8.0.0.0

Note: The CEDS Collaborative Exchange contains resources contributed by stakeholders. These resources should contain the compatible version they were created under.  The versions are not changed for a resource unless a stakeholder updates them to function under a newer version.

