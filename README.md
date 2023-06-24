# Online-banking-angular-springboot-mysql

Online-Bank

Spring Boot/Spring Data/Spring Security/Hibernate/MySQL/REST


The project is a simulation of an online banking system that allows the management of bank accounts. Each account is associated with a client and can be categorized as either Current or Savings. Various operations such as debit and credit can be performed on each account. The application follows a layered architecture consisting of the following components:

  - DAO layer: This layer includes JPA entities and repositories, which handle the persistence of data in the database.
  - Service layer: The service layer defines the core operations of the application. These operations include adding accounts and clients, performing debit and credit transactions, executing transfers between accounts, and       providing the ability to consult account information.
  - DTO layer: The DTO (Data Transfer Object) layer is responsible for defining data transfer objects that facilitate the exchange of information between different layers of the application.
  - Mappers: Mappers are used to convert data between DTOs and entities, ensuring seamless communication between layers.
  - Web layer: The web layer consists of REST controllers that expose the functionality of the application through RESTful APIs, allowing clients to interact with the system.
    
In summary, this project implements an online banking system with the ability to manage bank accounts, perform transactions, and provide client services. The layered architecture and the defined components ensure a structured and efficient development and operation of the application.

## Thing to run the application

__Clone the repository__
```
git clone https://github.com/chifaabelmaaza/EbankJEE-Backend 
```

__Go the folder__
```
E_Bank
```

__Set Your MySQL username & password in application.properties__

[application.properties](src/main/resources/application.properties)

__Run the application__

## Conception
1.	Digramme de classe :
   
![image](https://user-images.githubusercontent.com/90484039/175660644-09680cd8-30f9-4b73-b892-1c8d76fe0d6a.png)


3.	Pourquoi spring et angular ?
   
