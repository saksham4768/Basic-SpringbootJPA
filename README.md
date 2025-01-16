Java Persistence API (JPA) :- JPA (Java Persistence API) is a specification in Java that provides a way to manage relational data in Java applications.
Below are some core concepts in JPA:- 

    -> Entities: An entity is a Java class that is mapped to a database table. The class should be annotated with @Entity and @Table (optional) to specify the table name.
    
    -> JPQL (Java Persistence Query Language):- JPQL is similar to SQL but operates on entity objects rather than database tables.
    
    -> Transactions:- JPA supports transactions to ensure that database operations are executed atomically.You can start, commit, or roll back transactions using EntityTransaction.
    
    -> Relationships:- JPA provides annotations to define relationships between entities:
                        @OneToOne
                        @OneToMany
                        @ManyToOne
                        @ManyToMany
                    
