# Requirements

A client has hired you to track zoo animals.
For each animal, you must track that their name, species, and all zoos in which they have resided (including zoo name and address).

Determine the database tables necessary to track this information.

Label any relationships between table.


##A good data model

- capture ALL the data the system needs
- capture ONLY the data the system needs
- reflect reality
- is flexible, can evolve with future needs of the system
- guarantee data integrity
- driven by the way the data will be used


## Components

- entities: the nouns => resources in REST
- properties: what to track per entity
- relationships: how they relate to each other

## Workflow

- identify the entities
- identify the properties
- identify the relationships

## Relationships

- one to one: very rare
- one to many: this is the most common!
- many to many

## Mantras
- every table MUST have a primary key (PK)
- on a one to many relationship, there is a foreign key (FK)
- the FK goes in the MANY side
- in the many to many relationships, there is a third table
- the third table can have extra information


#requirements-

