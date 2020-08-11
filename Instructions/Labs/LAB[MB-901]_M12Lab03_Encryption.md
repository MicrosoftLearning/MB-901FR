---
lab:
    title: 'Labo 03 : Améliorez la sécurité en chiffrant vos données'
    module: 'Module 12 : Vérification de la sécurité de Dynamics 365'
---

# MB-901 : Dynamics 365 Fundamentals
## Module 12, Labo 3 : Améliorez la sécurité en chiffrant vos données

**Scénario :** En tant qu’administrateur système, vous devez modifier et copier la clé de chiffrement de l’organisation.

## Instructions

1. Accédez au centre d’administration Power Platform.  
1. Ces paramètres se trouvent dans **Environnements** > [sélectionnez un environnement]> **Réglages** > **Chiffrement** > **Chiffrement des données**.
1. Dans la zone **Modifier la clé de chiffrement**, tapez la nouvelle clé de chiffrement, puis sélectionnez **Modifier**.
1. Sélectionnez **OK** dans le message de confirmation, puis sélectionnez **Fermer** pour quitter la page de **Chiffrement des données**.

Nous vous recommandons fortement de faire une copie de votre clé de chiffrement des données.

1. Sélectionnez le même environnement que vous avez utilisé aux étapes 1 à 4 et accédez à **Paramètres** > **Chiffrement**.
1. Dans la boîte de dialogue **Chiffrement des données**, sélectionnez **Afficher la clé de chiffrement**, dans la zone **Clé de chiffrement actuelle**, sélectionnez la clé de chiffrement et copiez-la dans le presse-papiers.
1. Copiez la clé de chiffrement dans un éditeur de texte tel que le Bloc-notes.

**Remarque :** Par défaut, les applications pilotées par modèle dans Dynamics 365 génèrent une phrase secrète qui est une série aléatoire de caractères Unicode. Par conséquent, vous devez enregistrer la phrase secrète générée par le système à l’aide d’une application et d’un fichier qui prennent en charge les caractères Unicode. Certains éditeurs de texte, tels que le Bloc-notes, utilisent le codage ANSI par défaut. Avant d’enregistrer la phrase secrète à l’aide du Bloc-notes, sélectionnez Enregistrer sous, puis dans la liste Codage, sélectionnez Unicode.

La pratique recommandée consiste à enregistrer le fichier texte qui contient la clé de chiffrement sur un ordinateur, dans un emplacement sécurisé et sur un disque dur chiffré.
