---
lab:
    title : 'Labo 01 : Découvrez Dynamics 365 Sales'
    module : 'Module 03 : Présentation de Dynamics 365 Sales'
---

# MB-901 : Dynamics 365 Sales
## Module 3, Labo 1 - Découvrez Dynamics 365 Sales

**Conditions préalables :** Avant d’effectuer les étapes de ce labo, réalisez les tâches suivantes :

1. Créez et enregistrez un document Word avec un exemple de texte tel que « Guide des ventes Dynamics 365 » sur votre ordinateur de bureau.
1. Activez l’expérience **Améliorer l’e-mail** des paramètres de l’application Centre des ventes. Cette fonctionnalité permet à la fenêtre de composition d’e-mail de s’ouvrir dans une fenêtre contextuelle lorsque vous créez un nouvel e-mail dans la section **Chronologie**.
1. Actualisez votre navigateur.

**Facultatif :**
 
1. Dans votre instance Dynamics 365, accédez à Paramètres > Gestion des données.
1. Sélectionnez Exemple de données.
1. Si les exemples de données ne sont pas installés, sélectionnez **Installer des exemples de données**. Les exemples de données peuvent mettre quelques minutes à apparaître, mais vous pouvez continuer à utiliser l’application pendant l’installation.
1. Sélectionnez **Fermer**.

### Créez un nouveau contact

1. Dans le **Concentrateur des ventes de Dynamics 365**, accédez à **Clients** > **Contacts**.
1. Cliquez sur **Nouveau**.
1. Dans le champ **Prénom**, saisissez **Cameron**.
1. Dans le champ **Nom**, saisissez **Azadi**.
1. Dans le champ **Fonction**, saisissez **Gestionnaire de développement Xbox X-Series**.
1. Dans le champ **Téléphone professionnel**, saisissez **949-555-1212**.
1. Dans le champ **Adresse 1 : Rue 1**, saisissez **1 Microsoft Way**.
1. Dans le champ **Adresse 1 : **Dans le champ **Ville**, saisissez **Redmond**.
    - **Remarque :** si des données de la version de démonstration ont été téléchargées, le formulaire **Suggestions d’adresses** apparaîtra. Cliquez sur **OK**. Il remplira automatiquement les champs **Adresse 1**. 
1. Dans le champ **Adresse 1 :** Dans le champ **État/Province**, saisissez **WA**.
1. Dans le champ **Adresse 1 :** Dans le champ **Code postal**, saisissez **98007**.
1. Dans le champ **Adresse 1 :** Dans le champ **Pays/Région**, saisissez **États-Unis**.
1. Dans le champ **E-mail**, saisissez votre alias de messagerie.
1. Cliquez sur **Enregistrer**.

### Création d’un nouveau prospect

1. Dans le **concentrateur des ventes de Dynamics 365**, accédez à **Ventes** > **Prospects**
1. Cliquez sur **Nouveau**.
1. Cliquez sur l’icône **Étape de qualification**.
1. Dans le champ **Contact existant ?**,  sélectionnez ou saisissez **Cameron Azadi**.
- **Remarque :** La sélection d’un contact existant lors de la création d’un enregistrement de prospect remplit automatiquement le prénom, le nom, la profession, le téléphone professionnel, le téléphone portable et l’e-mail dans le formulaire du prospect. La sélection d’un compte existant remplira automatiquement le nom de l’entreprise dans le formulaire du prospect. Cela permet de saisir rapidement et facilement un enregistrement de prospect.
1. Dans le champ **Sujet**, saisissez **Aime nos produits Xbox**.
1. Cliquez sur **Enregistrer**.

### Modifiez les paramètres système

1. Accédez à l’icône **Réglages**, représentant un engrenage, dans le menu supérieur droit. Dans la liste déroulante, sélectionnez **Paramètres avancés**.
1. Cliquez sur la liste déroulante **Paramètres** puis sur **Administration** sous **Paramètres système.**
1. Sélectionnez l’onglet **Ventes**.
1. Dans le champ **Qualifier l’expérience du prospect**, sélectionnez **Non**.
1. Cliquez sur **OK**.

### Qualifiez le nouveau prospect

1. Dans le **Concentrateur des ventes de Dynamics 365**, accédez à **Ventes** > **Prospects**.
1. Sélectionnez **Cameron Azadi**.
1. Cliquez sur le bouton **Qualifier**.
1. Dans le formulaire **Qualifier le prospect**, cliquez sur **Contact**. Cela remplacera la valeur **Oui** par **Non**.
1. Dans le formulaire **Qualifier le prospect**, cliquez sur **Opportunité**. Cela remplacera la valeur **Non** par **Oui.**
1. Dans le formulaire **Qualifier le prospect**, cliquez sur **OK**. 
**Remarque :** Le prospect passera au stade de développement.

### Ajoutez des remarques au nouveau prospect

1. Dans la section **Chronologie**, cliquez sur **+** pour ajouter une nouvelle **Remarque**.
1. Dans le champ **Titre**, saisissez **Rencontre avec Cameron concernant la Xbox X-Series**.
1. Cliquez sur **Ajouter une remarque**.
1. Dans la section **Chronologie**, cliquez sur **+** pour ajouter une autre **Remarque** avec une pièce jointe.
1. Dans le champ **Titre**, saisissez **Informations sur le produit Xbox X-Series**.
1. Cliquez sur l’icône de pièce jointe et sélectionnez le document Word que vous avez créé au début de ce labo.
1. Cliquez sur **Ajouter une remarque**.

### Vérifiez les remarques créées dans le prospect à partir des opportunités

1. Dans le **Concentrateur des ventes de Dynamics 365**, accédez à **Ventes** > , puis à **Opportunités**.
1. Changez de vue en cliquant sur le menu déroulant et en sélectionnant **Toutes les opportunités**.
1. Cliquez pour sélectionner l’opportunité **Aime nos produits Xbox pour Cameron Azadi**.
1. Notez que la pièce jointe et les remarques créées dans le formulaire de prospect sont également disponibles dans le formulaire d’opportunité. 
1. Dans la section **Chronologie**, cliquez sur **+** pour rédiger et envoyer un **E-mail**. La fenêtre contextuelle d’e-mail apparaîtra.
1. Dans le champ **Sujet**, saisissez **Xbox X-Series**.
1. Saisissez un message tel que « Bonjour Cameron, merci de votre intérêt pour la Xbox X-Series. Nous attendons avec impatience de vous rencontrer. » 
1. Le cas échéant, à partir de à partir de la fiche d’opportunité ou des fiches connexes telles que la fiche de contact, en arrière-plan, vous pouvez copier et coller toutes les informations dans l’e-mail, sans perdre le focus et gagner du temps.
1. Cliquez sur **Enregistrer**.




