+++
url = "/fr/avancé/migrations/"
title = "Migrations"
weight = 20
chapter = true
tags = ["infrastructure", "migration"]
+++

# Migrations

Une migration est une opération qui consiste à faire évoluer une caractéristique technique de votre compte. Par exemple, une migration vers une nouvelle version de MySQL.

Les migrations disponibles apparaissent dans le menu **Avancé > Migrations** de l'[administration alwaysdata](https://admin.alwaysdata.com). De nouvelles migrations sont ajoutées régulièrement et nous avertissons nos utilisateurs par email pour les informer.

{{< fig "migrations-menu.fr.png" "Interface d'administration : menu Migrations" >}}

Certaines migrations sont facultatives : nous vous laissons le choix de l'effectuer ou non. D'autres migrations sont obligatoires : vous disposez alors d'un certain temps pour les effectuer. Une fois la date limite atteinte, les migrations non effectuées le seront automatiquement.


- [Effectuer une migration]({{< ref "advanced/migrations/perform-migration" >}})
- [Migrations Cloud Privé]({{< ref "advanced/migrations/vps-and-dedicated-migrations" >}})


## Migrations actuellement proposées

- [MariaDB 10.6]({{< ref "advanced/migrations/mariadb-10_6" >}})
- [PostgreSQL 14]({{< ref "advanced/migrations/postgresql-14" >}})

Cloud Privé :

- [MariaDB 10.5]({{< ref "advanced/migrations/mariadb-10_5" >}})
- [PostgreSQL 13]({{< ref "advanced/migrations/postgresql-13" >}})

## Anciennes migrations

* [Infrastructure logicielle 2020]({{< ref "advanced/migrations/2020-software-architecture" >}})
* [Infrastructure logicielle 2017]({{< ref "advanced/migrations/2017-software-architecture" >}})
