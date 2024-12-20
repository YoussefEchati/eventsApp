﻿# EventsApp

EventsApp est une application web développée avec Spring Boot qui permet de gérer des événements. Les fonctionnalités incluent :
- Inscription des participants
- Liste d'attente
- Paiement avec Stripe. 
- Envoi des notifications d'inscription aux participants via Spring Mail 

## Technologies utilisées
- Spring Boot
- Thymeleaf
- Bootstrap


## Comment exécuter le projet
1. Clonez ce dépôt :
   ```bash
    git clone https://github.com/YoussefEchati/eventsApp.git

  
2. Importez-le dans votre IDE (IntelliJ, Eclipse).
3. Configurez la base de données (MySQL).
4. Lancez le projet en exécutant `EventsAppApplication.java`.
5. Rendez-vous à l'adresse suivante pour voir l'application en action : http://localhost:9090

## Notes
1. Après le lancement de l'application, un utilisateur avec username "admin" et mot de passe "12345" va être crée. Utilisez-le pour accéder au Dashboard.
2. Dans "application.properties", Remplacez "spring.mail.username" et "spring.mail.password" par ton Gmail et son mot de passe d'application , et "stripe.api.key" par le mot de passe secret que vous pouvez recuperer via ton compte "Stripe" 

## Auteur
- **Youssef Echati**  


