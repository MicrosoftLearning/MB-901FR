---
lab:
    title : 'Labo 01 : Découvrez Dynamics 365 Finance'
    module : 'Module 07 : Présentation de Dynamics 365 Finance'
---

# MB-901 : Dynamics 365 Fundamentals 
## Module 7, Labo 1 - Découvrez Dynamics 365 Finance 


**Conditions préalables** : Avant d’effectuer les étapes de ce labo, réalisez les
tâches suivantes : 

**Remarque :** Vous devez disposer d’un environnement déployé avec des données de démonstration avant d’effectuer
ce labo. Vous pouvez lancer votre instance des applications Dynamics 365 Finance et Operations
depuis LCS ou en allant directement à l’URL de l’instance.

Vous devez modifier la société en **USMF**. Pour vous connecter à l’instance des applications Dynamics 365 Finance et Operations, vous devez disposer d’un nom d’utilisateur et d’un mot de passe avec un rôle de sécurité de **président directeur général** ou d’**administrateur système**.

Dans le cas où votre environnement ne dispose pas de données de démonstration, suivez les instructions
ci-dessous :

Accédez à **Modules>Données de démonstration**, puis cliquez sur **Générer des données**, et enfin sur
    **OK.**

### Importer des taux de change

1.  Modifiez la société en **USMF**.

2.  Accédez à **Comptabilité > Devises > Types de taux de change**.

3.  Cliquez sur **Nouveau**.

4.  Dans le champ **Type de taux de change**, tapez « GTL-EXCH ».

5.  Dans le champ **Nom**, tapez « Taux de change Seahorse ».

6.  Cliquez sur **Taux de change**.

7.  Notez qu’aucun taux de change n’est disponible.

8.  Fermez le formulaire de taux de change.

9.  Fermez le formulaire de type de taux de change

10. Accédez à **Comptabilité > Devises > Configurer les fournisseurs de taux de change**.

11. Cliquez sur **Nouveau**.

12. Sélectionnez **Banque centrale de la Fédération de Russie**

13. Cliquez sur **OK**.

14. Fermez la page.

15. Accédez à **Comptabilité > Devises > Importer les taux de change des devises**.

16. Dans le champ **Type de taux de change**, entrez ou sélectionnez GTL-EXCH

17. Sélectionnez **Banque centrale de la Fédération de Russie**

18. Dans le champ **Fournisseur de taux de change**, entrez ou sélectionnez **Banque centrale de
    la Fédération de Russie**

19. Cliquez sur **OK**.

20. Accédez à **Comptabilité > Devises > Types de taux de change**.

21. Sélectionnez **GTL-EXCH**

22. Cliquez sur **Taux de change**.

23. Notez les valeurs importées

24. Fermez tous les formulaires

### Créer une commande fournisseur, publier un accusé de réception de marchandises

1.  Accédez à **Comptabilité fournisseur > Commandes fournisseur > Toutes les commandes fournisseur**.

2.  Cliquez sur **Nouveau**.

3.  Dans le champ **Compte fournisseur**, sélectionnez **1001 Acme Office Supplies**.

4.  Dans le champ **Entrepôt**, sélectionnez **11**.

5.  Cliquez sur **OK**.

6.  Dans le champ **Numéro d’article**, sélectionnez un article **1000 Surface Pro 128 Go**.

7.  Dans le volet Actions, cliquez sur **Achat**.

8.  Cliquez sur **Confirmer**.

9.  Dans le volet Actions, cliquez sur **Recevoir**.

10. Cliquez sur **Accusé de réception de marchandises**.

11. Dans le champ **Accusé de réception de marchandises**, tapez **GTL02020**.

12. Cliquez sur **OK**.

13. Fermez tous les formulaires.

### Créer une facture financière gratuite

1.  Accédez à **Comptabilité client > Factures > Toutes factures financières**.

2.  Sélectionnez **Nouveau**.

3.  Dans le champ **Compte client**, sélectionnez **US-003**.

4.  Dans le champ **Description**, entrez **Guide de facture financière**.
    Dans la boîte de dialogue, cliquez sur **Oui**.

5.  Dans le champ **Compte principal**, sélectionnez le numéro de compte **110180**.

6.  Dans le champ **Quantité**, entrez **17**.

7.  Dans le champ **Prix unitaire**, entrez **817,00**. Le montant est calculé comme suit :
    la quantité multipliée par le prix unitaire. Cependant, vous pouvez remplacer ce
    calcul en saisissant un montant.

8.  Sélectionnez **Frais** pour ajouter des frais à la facture.

9.  Dans le champ **Code frais**, entrez **Frais de transport**.

10. Dans le champ **Valeur des frais**, entrez **150**.

11. Fermez la page.

12. Sélectionnez **Totaux** pour afficher un résumé des détails et des totaux de la facture.

13. Sélectionnez **Fermer**.

14. Cliquez sur **Valider** pour valider la facture. Ensuite, vous avez la possibilité
    d’annuler avant de valider.

    -  Vous pouvez modifier le temps d’impression des factures. Sélectionnez **Actuel** pour
        pouvoir imprimer chaque facture lors de sa mise à jour. Sélectionnez **Après** pour imprimer après
        la mise à jour de toutes les factures.

    -  Pour modifier la façon dont la limite de crédit du client est vérifiée avant la validation de la facture,
        modifiez la valeur dans le champ **Type de limite de crédit**.

    -  Pour imprimer la facture, définissez l’option sur **Oui**.

    -  Pour valider la facture, définissez l’option sur **Oui**. Vous pouvez imprimer la
        facture sans la valider.

15. Cliquez sur **OK**.
