
DESIGNING A DATABASE USING ER MODELLING AND 
EX.No.:11 
NORMALIZATION 
 
  
AIM: 
To design a database using ER Modeling and Normalization 
PROCEDURE: 
NORMALIZATION 
Normalization is the analysis of functional dependencies between attributes/data items of user  
views. It reduces a complex user view to a set of small and stable subgroups of the fields and relations.  
This process helps to design a logical data model known as conceptual data model. 
There are different normal forms 
1.	First Normal Form(1NF) 
2.	Second Normal Form(2NF) 3. Third Normal Form(3NF) 
FIRST NORMAL FORM (1NF) 
1NF states that the domain of an attribute must include only atomic values and that value of any  
attribute in a tuple must be a single value from the domain of that attribute. Hence 1NF disallows  multivalued attributes, composite attributes. It disallows “relations within relations”. 
SECOND NORMAL FORM (2NF) 
A relation is said to be in 2NF if it is already in 1NF and it has no partial dependency. 2NF is based  on the concept of full functional dependency. 
A functional dependency(FD) x→y is fully functional dependency is (x-(A))→y does not hold  
dependency any more if A→x. 
A functional dependency x→y is partial dependency if A can be removed which does not 
affect the  dependency ie (x-(A))→y holds. 
A relation is in 2NF if it is in 1NF and every non-primary key attribute is fully and functionally  dependent on primary key. 
A relation is in 1NF will be in the 2NF if one of the following conditions is satisfied: 
1.	The primary key consist of only one attribute. 
2.	No non-key attribute exist in relation ie all the attributes in the relation are components of the primary  key. 
Every non-key attribute is functionally dependent on full set of primary key attributes. 
THIRD NORMAL FORM (3NF) 
A relation is said to be in 3NF if it is already in 2NF and it has no transitive dependency. 
A FD x→y in a relation schema R is a transitive dependency if there is a set of attributes z that is neither a candidate key nor a subset of any key of the relation and both x→z and z→y hold. 
Entity relationship diagram (ERD): 
An entity relationship diagram (ERD) shows the relationships of entity sets stored in a database. An  
entity in this context is an object, a component of data. An entity set is a collection of similar entities.  
These entities can have attributes that define its properties. 
