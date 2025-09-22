### Project Overview: Relational Database Schema Design for Dog Ownership Management
This project demonstrates the design of a dog ownership and management system, starting with a UML class diagram to model key entities—Person, Organization, Ownership, and Dog—and their relationships, including breed-specific specializations. The conceptual model was then translated into a relational database schema with tables, primary keys, and foreign keys to ensure data integrity and support structured queries.

### Dog Breeding and Ownership UML Class Diagram
![UML class diagram of dog ownership](https://github.com/user-attachments/assets/1d1188f0-64f5-48d1-99cf-226d6be96b30)


### Dog Breeding and Ownership Relational Database Schema
![Database schema (1)](https://github.com/user-attachments/assets/161142fb-699a-45eb-8bb7-a05a092e7c0b)


### Textual Description of Dog Breeding and Ownership Relational Database Schema
The textual representation below provides a structured description of the database schema, listing each table, its attributes, and the relationships or constraints (such as primary keys, foreign keys, and alternate keys) that enforce the integrity of the model.   
•	Person (Name, Address)   
•	Organization (Organization Name)   
•	Workplace (Workplace Name, Employee Name) Workplace.Employee Name is foreign key towards Person.Name . Workplace.Workplace Name is foreign key towards Organization.OrgName .   
•	Ownership (From, Owner Id, Dog Name, Owner Name), Ownership.Dog Name is foreign key towards Dog.Dog Name. Ownership.Owner Name is foreign key towards Person.Name.  Dog Name and Owner Name are alternate keys.   
•	Dog (Dog Name, Champion, Dog Type), Dog.Dog Type is foreign key towards Breed.Dog Type. Dog Type is alternate key.   
•	Dachhound (Dog Name, Hunting), Dachhound.Dog Name is foreign key towards Dog.Dog Name.    
•	Misc (Dog Name, additional information), Misc.Dog Name is foreign key towards Dog.Dog Name.   
•	Breed (Dog Type)   
•	Disease (Dog Type, Disease), Disease.Dog Type is foreign key towards Breed.Dog Type.   

The project highlights the process of converting business requirements into a logical database design. Next steps for a business analyst could include refining requirements, defining detailed business rules, and creating queries, reports, or dashboards to illustrate how the database supports decision-making and user interactions.
