# Projet de gestion des opérations des comptes bancaires des clients
le but de ce projet consiste à créer une application web struts basant sur le modèle MVC. 
Cette application permet de gérer les opérations des comptes bancaires appartenant à des clients.
- Pour simplifier le modèle nous supposons qu’un Compte appartient à un client. 
- Le client peut posséder plusieurs comptes. 
- Le compte peut subir plusieurs opérations.
- Chaque Client est caractérisé par son code, son nom et son adresse.
- Chaque compte est défini par son numéro, sa date création et son solde
- Chaque Opération est définie par le Numéro opération, le numéro compte, la date d’opération et le montant de mouvement ainsi que son type [retrait ou dépôt].

## Cette application contient les composants Strus (Vue, Modèle et Contrôleur) pour répondre aux besoins suivants :

- [x] Une Vue pour ajouter un nouveau client.
- [x] Une Vue qui permet d’ajouter un nouveau compte.
- [x] Une Vue qui permet ajouter une opération de versement.
- [x] Une Vue qui permet d’ajouter une opération de retrait.
- [x] Une Vue qui permet de retourner tous les clients.
- [x] Une Vue qui permet de consulter un client via son code.
- [x] Une Vue qui permet de consulter un compte via son Numéro.
- [x] Une Vue qui permet de consulter les opérations (retrait et versement) d’un Compte.
- [ ] Une Vue qui permet de consulter toutes les opérations réalisées entre deux périodes.
