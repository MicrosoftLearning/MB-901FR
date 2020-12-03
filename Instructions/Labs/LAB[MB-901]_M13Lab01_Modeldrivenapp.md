---
lab:
    title: 'Labo 01 : Créez votre première application basée sur un modèle à partir de zéro'
    module: 'Module 13 : Connexion et analyse de vos données Dynamics 365'
---

# MB-901 : Dynamics 365 Fundamentals
## Module 13, Labo 1 : Créez votre première application basée sur un modèle à partir de zéro

**Scénario :** Vous devez créer une application basée sur un modèle en utilisant l’une des entités standard disponibles dans votre environnement Power Apps. Les applications basées sur un modèle ne s’exécutent pas dans l’application mobile Power Apps. Au lieu de cela, vous exécutez une application pilotée par modèle sur un appareil mobile à l’aide de l’application mobile Dynamics 365 ou dans le navigateur web du téléphone.

Connectez-vous avec votre identifiant Windows Live à Power Apps. Si vous n’avez pas encore de compte Power Apps, cliquez sur le lien gratuit Démarrer sur https://signup.microsoft.com/Start?sku=powerapps_viral&ru=https%3a%2f%2fweb.powerapps.com%2flogin%2fportal

## Instructions
1. Accédez au Centre d’administration Power Platform.
12.	Sélectionnez **Environnements**.
13.	Sélectionnez votre environnement de test CRM. 
14.	Sélectionnez le lien hypertexte ![Centre d’administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx?redirect=False0).
15.	Sélectionnez **GTLPowerApps**.
16.	Sélectionnez **Ouvrir**.
17.	Sélectionnez **Créer une nouvelle application**.
19.	Sur la page **Créer une nouvelle application**, saisissez les détails suivants, puis sélectionnez **Terminé** :
    - **Nom :** Saisissez **GuideToPowerApp**.
    - **Nom unique :** Par défaut, le nom unique utilise le nom que vous spécifiez dans la case Nom sans espaces et précédé du préfixe de l’éditeur et d’un trait de soulignement (_).
    - **Description :** Saisissez **GuideToPowerApp**.
20.	Sélectionnez **Terminé**.
21.	Depuis le concepteur d’application, vous pouvez ajoutez des composants à votre application. Sélectionnez l’icône représentant un crayon sur le bouton **Plan du site** pour ouvrir le concepteur du plan du site.
22.	Vous allez utiliser l’entité Comptes dans cette Power App pour gérer les comptes clients.
22. Sous l’onglet **Propriétés**, saisissez **Comptes** pour le nom de la zone.
23.	Dans le concepteur du plan de site, sélectionnez **Nouvelle sous-zone**, dans le volet droit, sélectionnez l’onglet **Propriétés**, puis sélectionnez la valeur des propriétés suivantes :
    - **Type : Entité**
    - **Entité : Compte**  
    - Sélectionnez **Enregistrer**. 
24.	Sélectionnez **Concepteur d’applications**.
25.	Sur le canevas du concepteur d’applications, sélectionnez **Formulaires**, puis dans le volet droit, sous le groupe **Formulaires principaux**, sélectionnez le formulaire **Compte**.
26.	Sélectionnez le bouton **Précédent**.
27.	Sur le canevas du concepteur d’applications, sélectionnez **Vues**, puis sélectionnez les vues **Comptes actifs**, **Tous les comptes**, et **Mes comptes actifs**.
28.	Sélectionnez le bouton **Précédent**.
29.	Sur le canevas du concepteur d’applications, sélectionnez **Graphiques**, puis sélectionnez le **Graphique des comptes par secteur d’activité**.
30.	Sélectionnez le bouton **Précédent**.
31.	Dans la barre d’outils du concepteur d’applications, cliquez sur **Enregistrer** puis sur **Publier**.
32.	Sélectionnez **Lire**.
34.	Examinez les résultats et interagissez avec votre première application basée sur un modèle.
35.	Essayez de le faire sur votre mobile en installant l’application Dynamics 365 pour téléphones ou Dynamics 365 pour tablettes depuis le magasin d’applications ou App Store de votre appareil. Pour plus d'informations, rendez-vous sur : https://docs.microsoft.com/dynamics365/customer-engagement/mobile-app/install-dynamics-365-for-phones-and-tablets
36.	Saisissez l’URL de l’application directement dans le navigateur de votre téléphone et suivez les instructions à l’écran pour charger l’application. 
  **Remarque :** Un exemple de l’URL de votre application ressemblera à ceci : https://orgxxxxx.crm.dynamics.com/main.aspx?appid=e4547538-e20f-ea01-a811-000d3a33438d&pagetype=entitylist&etn=account
