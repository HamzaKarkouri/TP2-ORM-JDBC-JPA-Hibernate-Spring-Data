# TP2-ORM-JDBC-JPA-Hibernate-Spring-Data
## Introduction
Ce rapport présente les étapes essentielles et les activités réalisées lors du TP de développement d'une application de gestion de patients en utilisant le framework Spring Boot et l'IDE IntelliJ Ultimate. Le TP a consisté en plusieurs phases, depuis la configuration de l'environnement de développement jusqu'à la migration de la base de données. Les étapes clés de ce projet incluent l'installation d'IntelliJ Ultimate, la création d'un projet Spring Initializer avec des dépendances JPA, H2, Spring Web et Lombok, la définition d'une entité JPA "Patient" avec ses attributs, la configuration de l'unité de persistance dans le fichier application.properties, la création d'une interface JPA Repository basée sur Spring Data, et enfin, la mise en place de diverses opérations de gestion de patients telles que l'ajout, la consultation, la recherche, la mise à jour et la suppression de patients.
Ce rapport documente en détail chaque étape du processus de développement, mettant en évidence les challenges rencontrés, les solutions adoptées, ainsi que les résultats obtenus tout au long de la réalisation de ce TP. Enfin, le rapport se termine en abordant la migration de la base de données H2 vers MySQL, ce qui démontre une transition vers un système de gestion de données plus robuste pour une application en pleine croissance.

## Ennoncé
1. Installer IntelliJ Ultimate
2. Créer un projet Spring Initializer avec les dépendances JPA, H2, Spring Web et Lombock
3. Créer l'entité JPA Patient ayant les attributs :
       - id de type Long
       - nom de type String
       - dateNaissanec de type Date
       - malade de type boolean
       - score de type int
4. Configurer l'unité de persistance dans le ficher application.properties 
5. Créer l'interface JPA Repository basée sur Spring data
6. Tester quelques opérations de gestion de patients :
    - Ajouter des patients
    - Consulter tous les patients
    - Consulter un patient
    - Chercher des patients
    - Mettre à jour un patient 
    - supprimer un patient
7. Migrer de H2 Database vers MySQL

8. ## Capture d'écran
