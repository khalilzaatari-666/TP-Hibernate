# Projets Hibernate

Ce README décrit différents projets Hibernate divisés en quatre parties : Exercice 1, Exercice 2, Exercice 3 et Devoir (Homework). Il fournit également des instructions sur la configuration de la base de données nécessaire pour ces projets.

## Configuration de la Base de Données

Avant de commencer, assurez-vous d'avoir une base de données configurée. Vous pouvez utiliser MySQL, PostgreSQL ou H2, par exemple. Ajustez les informations de connexion dans le fichier `hibernate.cfg.xml` pour correspondre à votre base de données, y compris le pilote JDBC, l'URL, le nom d'utilisateur et le mot de passe.

```xml
<property name="hibernate.connection.driver_class">com.mysql.cj.jdbc.Driver</property>
<property name="hibernate.connection.url">jdbc:mysql://localhost:3306/votre_base_de_donnees</property>
<property name="hibernate.connection.username">votre_utilisateur</property>
<property name="hibernate.connection.password">votre_mot_de_passe</property>
```

## Exercice 1

L'objectif de cet exercice est d'introduire Hibernate en créant une classe d'entité simple et en effectuant des opérations de base. Le code correspondant se trouve dans le dossier "Exercice1".

Assurez-vous que la configuration Hibernate est correcte, que votre base de données est prête, et suivez les instructions du fichier README dans le dossier "Exercice 1" pour réaliser cet exercice.

## Exercice 2

Cet exercice se concentre sur les relations entre les entités. Vous allez créer des associations entre différentes classes d'entités, telles que les relations "many-to-one" ou "one-to-many". Le code pour cet exercice se trouve dans le dossier "Exercice 2".

## Exercice 3

Cet exercice se concentre sur les requêtes et les critères. Vous allez apprendre à interroger la base de données en utilisant le langage HQL (Hibernate Query Language) et les critères de requête. Le code de cet exercice se trouve dans le dossier "Exercice 3".

