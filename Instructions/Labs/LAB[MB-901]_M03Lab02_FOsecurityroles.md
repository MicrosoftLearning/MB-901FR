---
lab:
    title : 'Labo 02 : Découvrez les rôles de sécurité dans les applications Dynamics 365 Finance and Operations'
    module : 'Module 03 : Vérification de la sécurité de Dynamics 365'
---

# MB-901 : Dynamics 365 Fundamentals
## Module 3, Labo 2 - Découvrez les rôles de sécurité dans les applications Dynamics 365 Finance and Operations

### Exclusion de rôle

**Scénario :** Le service des ressources humaines d’USMF a demandé de supprimer l’accès à la comptabilité client du rôle de commis dans les applications Dynamics 365 Finance and Operations pour un employé qui a changé de rôle. En tant qu’administrateur système, vous devez exclure le rôle de commis aux comptes clients pour l’employé.

1. Accédez à **Administration système** > **Sécurité** > **Affecter des utilisateurs aux rôles**.
1. Dans l’arborescence, sélectionnez **Commis à la comptabilité clients**.
1. Cliquez sur **Affecter** / **exclure manuellement des utilisateurs**.
1. Dans la liste, sélectionnez un utilisateur.
1. Sélectionnez **Exclure du rôle** pour exclure les utilisateurs sélectionnés du rôle.
1. Pour supprimer les exclusions, sélectionnez les utilisateurs pour lesquels vous souhaitez supprimer les exclusions, puis sélectionnez **Rétablir le statut**. 

### Créer une règle de répartition des tâches

**Scénario :** Le service des ressources humaines de l’USMF a demandé une règle de répartition des tâches pour qu’**Accéder à l’espace de travail d’avantages** soit en premier et **Approuver le journal de production** en deuxième. En tant qu’administrateur système, vous devez créer la règle.

1. Accédez à **Administration système** > **Sécurité** > **Répartition des tâches** > **Règles de répartition des tâches**.
1. Cliquez sur **Nouveau**.
1. Dans le champ **Nom**, tapez un nom unique pour cette règle.
1. Dans le champ **Première responsabilité**, cliquez sur le bouton de liste déroulante pour lancer la recherche.
1. Dans la liste, recherchez et sélectionnez la première responsabilité contrôlée par la règle.
1. Dans la liste, cliquez sur le lien dans la ligne sélectionnée.
1. Dans le champ **Seconde responsabilité**, cliquez sur le bouton en regard de la liste déroulante pour lancer la recherche.
1. Dans la liste, recherchez et sélectionnez la seconde responsabilité contrôlée par la règle.
1. Dans la liste, cliquez sur le lien dans la ligne sélectionnée.
1. Dans le champ **Gravité**, sélectionnez la gravité du risque qui se produit lorsque le même utilisateur ou le même rôle remplit les deux responsabilités.
1. Dans le champ **Risque de sécurité**, tapez une description du risque de sécurité.
1. Dans le champ **Atténuation de sécurité**, tapez une valeur.
1. Entrez une description des actions que vous prenez pour atténuer le risque de sécurité. 
Par exemple, vous pouvez atténuer le risque en effectuant des évaluations plus détaillées du processus, en effectuant une révision mensuelle de la gestion ou en partageant les ressources avec d’autres services.
1. Cliquez sur **Enregistrer**.
