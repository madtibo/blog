---
layout: post
title: Nouvel outil Dalibo Labs - ldap2pg
author: Léo Cossic
twitter_id: dalibolabs
github_id: dalibo
tags: [Ldap, ldap2pg, postgresql, tool, opensource, dalibolabs, dalibo, labs]

---

*Paris, le 29 juin 2017*

Étienne, un des développeurs de notre "agence dev", a prit l'initiative, pour répondre au besoin d'un client, de créer un outil permettant de synchroniser les ACL Postgres depuis LDAP.


<!--MORE-->


Ldap2pg est un couteaux suisse permettant de synchroniser les listes de contôles des accès depuis n'importe quel répertoire LDAP.

Fonctionnalités:

    Créé et dépose les rôles PostgreSQL depuis les requêtes Ldap
    Gère les options des rôles (Crée et modifie)
    Lancement sec
    
    Creates and drops PostgreSQL roles from LDAP queries.
    Manage role options (CREATE and ALTER).
    Dry run.
    logs LDAP queries as ldapsearch commands.
    logs every SQL queries.
    Reads settings from YAML config file.

## Versions

Consultez les versions ldap2pg.yml pour plus d'options: https://github.com/dalibo/ldap2pg/blob/master/ldap2pg.yml

## Installation

Installez le grâce à l'archive GitHub: pip install https://github.com/dalibo/ldap2pg/archive/master.zip

*ldap2pg est sous licence PostgreSQL.*