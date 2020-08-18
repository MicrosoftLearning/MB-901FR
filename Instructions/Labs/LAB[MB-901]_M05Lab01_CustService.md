---
lab:
    title: 'Labo 01 : Découvrez le service client Dynamics 365'
    module: 'Module 05 : Présentation de Dynamics 365 Customer Service'
---

# MB-901 : Dynamics 365 Fundamentals 
## Module 5, Labo 1 - Découvrez le service client Dynamics 365 

**Conditions préalables :** Avant d’effectuer les étapes de ce labo, réalisez les tâches suivantes : 

**Facultatif :**
1. Dans votre instance Dynamics 365, accédez à **Paramètres** > **Gestion des données**. 
1. Sélectionnez **Exemple de données**. 
1. Si les exemples de données ne sont pas installés, sélectionnez **Installer des exemples de données**. Les exemples de données peuvent mettre quelques minutes à apparaître, mais vous pouvez continuer à utiliser l’application pendant l’installation. 
1. Sélectionnez **Fermer**. 

**Scénario :**
En tant que représentant du service client, vous devez suivre vos demandes et problèmes clients en créant des cas de support dans le service client Dynamics 365. Lorsqu’un client contacte le support technique pour une question ou un problème, vous pouvez rapidement vérifier si ce type d’incident existe déjà ou ouvrir un nouvel incident et commencer à suivre le problème. Vous pouvez également faire remonter, réaffecter ou remettre un incident dans la file d’attente de service si vous n’avez pas suffisamment d’informations ou de temps pour y travailler.

Avant de fournir un support, vous pouvez également vérifier les droits du client. Les droits sont comme des contrats qui vous indiquent à quel type de support un client est éligible. Vous verrez si les conditions de support dépendent du nombre d’heures ou de cas, du canal de support ou du produit ou service que le client a acheté.

Pour vous aider à sélectionner l’état correct d’un incident votre administrateur peut faire en sorte que ne voyiez qu’un ensemble limité d’états en fonction de l’état actuel d’un incident.

## Instructions

### Créer un incident

1. Dans le **Concentrateur du service client**, accédez à **Service** > **Incidents**.
1. Sélectionnez **Nouvel incident**.
1. Dans le champ **Titre de l’incident**, tapez **Smart watch Seahorse**.
1. Dans le champ **Clients**, sélectionnez **Fabrikam.** 
1. Dans le champ **Description**, tapez **Problème avec la smartwatch**
1. Cliquez sur l’onglet **Détails**.
1. Dans le champ **Contact**, cliquez sur le bouton **Recherche de contact** et sélectionnez un contact existant pour l’incident ou sélectionnez **Nouveau** dans les résultats de la recherche en ligne pour créer un nouvel enregistrement de contact.
1. Cliquez sur **Enregistrer**.
1. Pour suivre votre conversation avec le client, dans la section **Chronologie**, cliquez sur **+** pour ajouter des informations et des activités.
1. Cliquez sur **Remarque**.
1. Dans le champ **Titre**, tapez **Défaut de la smart watch**.
1. Dans le champ **Remarque**, tapez **Faire réparer**.
1. Cliquez sur **Ajouter une remarque**. 
14.	Pour savoir quel type de support vous devez fournir au client, cliquez sur le bouton **Recherche de droits d’utilisation** et sélectionnez un droit d’utilisation actif.
 **Remarque :** Si le client n’a aucun droit d’utilisation, cette zone sera vide.
1. Cliquez sur **Enregistrer**.

### Trouver une solution à partir d’incidents similaires

**Remarque :** Vous pouvez consulter les incidents résolus pour voir s’ils peuvent vous aider à résoudre l’incident sur lequel vous travaillez. Par exemple, si le sujet de l’incident sur lequel vous travaillez est «**Défaut de smartwatch**», vous pouvez rechercher des incidents résolus qui portent le même sujet pour obtenir de l’aide sur votre indicent actuel.

### Résolution d’incident

Avant de résoudre un incident, assurez-vous que toutes les activités de cet incident sont fermées. Sinon, vous recevrez un message indiquant que des activités associées à l’incident sont encore ouvertes et seront annulées si l’incident est résolu.

1. Accédez à **Service** > **Incidents**.
1. Dans la liste des incidents actifs, ouvrez l’incident **Smartwatch Seahorse** à résoudre.
1. Sélectionnez **Résoudre** l’incident dans la barre de commandes.
1. Dans la boîte de dialogue **Résoudre l’incident**, sélectionnez **Problème résolu** dans la liste **Type de résolution**.
1. Dans la zone **Résolution**, tapez **Réparé**.
1. Le temps réel consacré à toutes les activités de cet incident, tel qu’enregistré dans la zone **Durée** de chaque activité, est automatiquement renseigné dans la zone **Durée totale**.
1. Dans la liste **Durée à facturer**, sélectionnez **30 minutes** comme temps, passé sur l’incident, à facturer au client.
 **Remarque :** Si cet incident est lié à un contrat ou à un droit d’utilisation, le temps facturable sera soustrait des minutes allouées à ce contrat.
1. Sélectionnez **Résoudre**. Une activité de résolution d’incident est créée et affichée dans la zone **Activités**. 

L’activité de résolution contient des informations sur un incident résolu, y compris la résolution et le temps total passé sur l’incident. Vous pouvez à tout moment réactiver un incident résolu.
