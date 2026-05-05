What is an Entity in ER Modeling?
An entity is a real‑world object, concept, or thing that the database needs to store information about. Entities are represented as rectangles in an ER diagram.
Examples include Person, Pet, Order, Product.
Entities must be uniquely identifiable, usually through a primary key.

How Are Attributes Defined and Associated With Entities?
Attributes are properties that describe an entity. They are represented as ovals connected to their entity.
Examples:

A Person may have attributes like FirstName, LastName, PhoneNumber.

A Pet may have Name, Species, Birthdate.

Types of attributes include:

Simple (cannot be broken down)

Composite (can be subdivided, like FullName → FirstName + LastName)

Derived (calculated, like Age from Birthdate)

Key attributes (uniquely identify an entity, like PersonID)

What Is a Relationship in ERM, and How Does It Connect Entities?
A relationship describes how two entities are logically connected.
It is represented as a diamond between entities.

Examples:

A Student enrolls in a Course

A Person owns a Pet

Relationships come from verbs in real‑world descriptions.

Types of Cardinality (1:1, 1:N, N:M)
Cardinality defines how many instances of one entity can be associated with another.

1. One‑to‑One (1:1)
One instance of Entity A relates to one instance of Entity B.
Example: One person ↔ one passport.

2. One‑to‑Many (1:N)
One instance of Entity A relates to many instances of Entity B.
Example: One customer → many orders.
This is the most common cardinality.

3. Many‑to‑Many (N:M)
Many instances of Entity A relate to many instances of Entity B.
Example: Students ↔ Classes.
This usually requires a junction table in relational databases