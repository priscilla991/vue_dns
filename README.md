# vue_dns  

**Vue personnalisée DNS dans l'Observateur d'événements**  

**Objectif**  

Cette vue personnalisée a été créée pour surveiller l'état du service DNS sur un serveur Windows. Elle permet de détecter rapidement les événements critiques, les erreurs et les avertissements liés :  

Au serveur DNS (DNS-Server-Service)  

Au client DNS (DNS Client Events)  

**Sources surveillées**  

DNS-Server-Service : Activité du service DNS serveur  

DNS Client Events : Résolution de noms côté client    

**ID des événements filtrés**

| ID   | Description                 |
| ---- | --------------------------- |
| 2    | Démarrage du serveur DNS    |
| 4    | Arrêt du serveur DNS        |
| 409  | Erreur de résolution de nom |
| 501  | Échec de chargement de zone |
| 502  | Échec de chargement de zone |
| 6001 | Problème de réplication DNS |
| 6002 | Problème de réplication DNS |


 **Configuration**  
 
Niveaux d'événements : Critique, Erreur, avertissement , informations.  

Filtrage par ID d’événement

**Emplacement**  

**La vue est enregistré dans :**

Event Viewer > Custom Views > Surveillance-DNS


