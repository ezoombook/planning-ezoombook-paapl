# Planning de développement pour le projet eZoomBook

Planning de développement de la plate-forme eZoomBook dans le cadre du projet d'application d'Ophir et Shuli.

# Tâches

## Découverte de la plate-forme
Tâche | Durée estimée | personne assignée | Avancement
--- | --- | --- | --- | 
Apprendre scala | 2 semaines | tous | entamé
Découverte de l'organisation du code | 1 semaine | tous | entamé
Rédiger une courte documentation sur l'organisation du code | 1 semaine | tous | À faire en même temps que les autre tâches

## Debug
Tâche | Durée estimée | personne assignée | Avancement et notes
--- | --- | --- | ---
1. **Erreur lors de l’accès à un chapitre** | 2 mois | Shuli 
1.1 Choix d'une solution provisoire permettant d'éviter la page d'erreur | 1 jour | Shuli | fait
1.2 Implémentation de la solution choisie en 1.1 | 1 semaine | Shuli
1.3 Choix d'une solution définitive (impliquant nécessairement des changements dans l'organisation de la page d'édition des eZoomBooks), en accord avec Christine.  | 1 semaine | Shuli, Ophir, ... | Nécessite d'avoir étudié ce problème dans le cadre du projet d'ANREC. (cf 5.)
1.4 Implémentation de la solution choisie en 1.3 | 1 mois | Shuli, Ophir, ... | 
2. **Page d’erreur après la connexion** | 3 semaines | Ophir | Éventuellement beaucoup moins, selon la nature du bug et les choix techniques qui seront effectués
2.1 Intégrer le dépôt `dev` à l'intérieur du dépôt `EZB_WEB` | 3 jours | Ophir | Solution à étudier. À faire, selon la complexité. Éventuellemnt à discuter avec Mayleen
2.2 Localiser la méthode qui cause le bug | 1 à 2 semaines | Ophir | Temps variable...
2.3 Corriger le bug | 2 jours | Ophir
3. **Impossible de supprimer un eZB** | 1 semaine | Bertrand
4. **Problème lors de l’enregistrement des citations sélectionnées** | 2 semaines | Pas encore défini | La solution dépendra probablement des choix effectués en 1.3
5. **Changements dans l'interface d'édition** | 1 mois | Ophir, Shuli | Selon le projet d'ANREC
6. **Ajout d'un nom aux layers** | 1 semaine | Ophir | À discuter avec Christine
7. **Rédaction rapports** | 1 semaine | Ophir, Shuli
 
## Dates clés
   Date   |      Tâches                |                         Objectif                    
----------|----------------------------|-------------------------------------------------------------| 
lun. 22/12| 1.1, 1.2, 2, 3, (4)        | Fin des tâches de debug
ven. 16/01| 1.3, 1.4, 5, 6             | Fin des ajouts de fonctionnalité
lun. 19/01| 7                          | Envoi du rapport
ven. 23/01|                            | Fin officielle du projet d'application d'Ophir et Shuli
