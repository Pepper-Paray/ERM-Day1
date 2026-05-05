# ERM-Day1
+-------------+            +-------------+
|   Person    |            |     Pet     |
+-------------+            +-------------+
| PersonID PK | 1       N | PetID PK     |
| FirstName   |------------| Name         |
| LastName    |   Owns     | Species      |
| PhoneNumber |            | Birthdate    |
+-------------+            +-------------+
Person and Pet are the two main entities because they represent real‑world objects we need to store data about.

Each entity has a primary key (PersonID, PetID) so each record is uniquely identifiable.

The relationship Owns connects the two entities because the scenario describes ownership.

The cardinality is 1:N because one person can own multiple pets, but each pet belongs to one person.

This structure is simple, logical, and follows standard ER modeling rules.