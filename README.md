# README

Application de Gossip

Comment tester l'appli :

- Lancer dans le terminal la commande rails db:seed

- Puis la commande rails console

- Afficher le(les) potins d'un utilisateur : User.find(id_du_user).gossips

- Afficher le(les) tags d'un potin : Gossip.find(id_du_gossip).tags

- Afficher la ville d'un user : User.find(id_du_user).city

- ...

## Auteur

 ~ Orgeret Florence ~