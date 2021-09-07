# ETS-Assessment-Spring-MVC

Designing a Spring MVC web app satisfying the following requirements. Designing tables for data insertion/retrieval.

Creating a handler that accepts a userId, transactionDate, transactionAmount from client. transactionAmount could be negative (in case of withdrawal) or positive (in case of deposit).
a. Store userId, transactionDate in Table A.
b. Store transactionAmount in Table B.
c. Access Table C with userId and Store totalAmount as previousAmount + transactionAmount.
 

Taking these into considerations.
Table A information must be persisted always.
Persistence of Table B and Table C are dependent on each other.

Creating a handler to retrieve following information based on userId.
a. Recent transactionDate
b. Last transactionAmount
c. totalAmount
