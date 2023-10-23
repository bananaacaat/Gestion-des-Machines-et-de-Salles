# Application de Gestion de Machines et de Salles 
Ce projet est une application de gestion de machines et de salles qui permet d'ajouter, supprimer, modifier et trier les machines par salle en utilisant la technologie RMI (Remote Method Invocation)

## Fonctionnalités
- **Ajouter une machine**: Permet d'ajouter une nouvelle machine en spécifiant sa référence, sa marque, son prix et la salle à laquelle elle est associée.
- **Supprimer une machine**: Permet de supprimer une machine existante en fonction de son identifiant.
- **Modifier une machine**: Permet de mettre à jour les informations d'une machine existante.
- **Trier les machines par salle**: Trie les machines par salle d'appartenance pour une meilleure gestion.

## Screenshots de Workstation

### Gestion des machines
![g machine](https://github.com/bananaacaat/tp-RMI/assets/147453939/18aca65b-ab4a-4457-aaf7-a2be24635c45)

#### Ajout des machines
![WhatsApp Image 2023-10-23 at 18 11 14_57a6f009](https://github.com/bananaacaat/tp-RMI/assets/147453939/10fa13ab-84fc-4d0f-a1eb-4f36bf48841a)

#### Supression des machines
![supp machine](https://github.com/bananaacaat/tp-RMI/assets/147453939/ef00d4f7-a4b5-4c06-b283-f374f78c93e5)

#### Modification des machines 
![mod machine](https://github.com/bananaacaat/tp-RMI/assets/147453939/69c629bc-325e-49db-a4cc-53abb0002689)

### Gestion des salles
![sall](https://github.com/bananaacaat/tp-RMI/assets/147453939/69097865-8c65-4bdc-b068-7679cc5d87cf)

#### Ajout des salles
![sall ajout](https://github.com/bananaacaat/tp-RMI/assets/147453939/e6312eb6-acbd-433a-ac8f-60e1a60277ff)

#### Modification des salles 
![mod salle](https://github.com/bananaacaat/tp-RMI/assets/147453939/4c26b1fe-aa75-433c-b634-65b92bdfd09e)

## ServerRMI Project
- `src/main/java/entities`: Entity classes for machines and rooms.
- `src/main/java/util`: `HibernateUtil` class for managing the SessionFactory.
- `src/main/java/service`: `MachineService` and `RoomService` classes for service operations.
- `src/main/java/config`: `hibernate.cfg.xml` file for Hibernate configuration.
- `src/main/java/dao`: `IDao` interface for CRUD operations.
- `src/main/java/server`: `Server` class to start the RMI server.

## ClientRMI Project
- `src/main/java/entities`: Entity classes for machines and rooms.
- `src/main/java/dao`: `IDao` interface for CRUD operations.
- `src/main/java/config`: `Config` class for RMI configuration (IP address and port).
- `src/main/resources`: `configuration.properties` file to specify the server's IP address and port.
- `src/main/java/ui`: Swing graphical user interface for room and machine management.

## System Requirements
- Java 8 or higher
- MySQL Server
- Hibernate
- Network connection for RMI communication

## Configuration du Projet
- Clonez ce projet sur votre ordinateur.
- Démarrez le serveur RMI en utilisant la classe Server du projet ServerRMI.
- Exécutez l'application Swing en utilisant la classe principale du projet ClientRMI.
- Utilisez l'interface graphique pour effectuer des opérations CRUD sur les machines et les salles.
- Effectuez des recherches pour trouver les machines disponibles dans chaque salle

## Help
Ce projet est destiné à la gestion des salles et des machines en utilisant des technologies avancées en Java. Pour toute question ou commentaire, veuillez me contacter.





