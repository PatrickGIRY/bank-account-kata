# bank-account-kata

2022-07-06

### Objectifs

* Apprendre et pratiquer le TDD double boucle
* Tester l'application depuis l'exterieur, identifier les effets de bord

### Description du problème

Créer une simple application de banque avec les fonctionnalités suivantes :

     - Deposit into Account
     - Withdraw from an Account
     - Print a bank statement to the console

## Critères d'acceptance

Le relevé de compte doit avoir des transactions au format suivant:

```text
  DATE       | AMOUNT  | BALANCE
  10/04/2014 | 500.00  | 1400.00
  02/04/2014 | -100.00 | 900.00
  01/04/2014 | 1000.00 | 1000.00
```

## Point de départ et contraintes

Commencer avec une classe avec la structure suivante:

```java
public class Account {

    public void deposit(int amount);

    public void withdrawal(int amount);

    public void printStatement();

}
```

Vous n'êtes pas autoriser à ajouter une autre méthode publique à cette classe.

> **NOTE:** Dans le but de simplifier l'exercice :
> * utilisez des _int_ pour les montants et des _String_ pour les dates.
> * Ignorer la mise en forme (les espaces entre les pipe `|` et les mots).
