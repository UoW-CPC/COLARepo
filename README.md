# MiCADO: TOSCA Repository

##### This repository holds the TOSCA related material developed as a part of the [COLA Project](https://project-cola.eu/). The templates and definitions found here are compliant with MiCADOv0.5.x
------------

## custom type definitions/
##### Custom type defintions for nodes, relationships, capabilities and data types are defined here
The file here defines all custom types for use with the MiCADO platform. Its location is referenced in the import section of an ADT, and the types defined therein can be used as needed within the topology section of the ADT.

## custom policy definitions/
##### Policy definitions are kept here
These definitions describe policies which can be referenced and abstracted by various ADTs. The location of a policy defintion is referenced in the import section of an ADT, and its defintion is expanded with properties and targets within the policies section of the ADT.

## use-case templates/
##### COLA Use-Case Application Description Templates are kept here
These templates describe the application topology and policies for COLA use-cases. They are submitted to the toscasubmitter component in MiCADO to deploy applications to the cloud.

## example templates/
##### Example Application Description Templates are kept here
These templates describe the application topology and policies for examples that have been used by COLA in proof-of-concept testing. They use features of TOSCA that are not currently explored in the use-cases, or are used for benchmarking and demonstrations.

## pre-filled templates/
##### Pre-filled Application Description Templates are kept here
These templates provide a simple fill-in-the-blanks approach for those looking to create their own TOSCA ADTs for use with MiCADO.
