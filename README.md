# agile-final-project
# Calculateur d'intérêt simple

## 📌 Description

Ce projet contient les détails et la logique nécessaires à la réalisation d'un **calculateur d'intérêt simple**.

L'objectif est de permettre à l'utilisateur de calculer rapidement l'intérêt généré par un capital initial sur une période donnée, à partir d'un taux d'intérêt fixe.

## 🧮 Formule

Le calcul de l'intérêt simple repose sur la formule :

```text
I = P × r × t
```

Avec :

- **I** : intérêt généré
- **P** : capital initial (principal)
- **r** : taux d'intérêt par période, exprimé en décimal
- **t** : durée de placement ou d'emprunt

Le montant total obtenu à la fin de la période est :

```text
A = P + I
```

ou :

```text
A = P × (1 + r × t)
```

## 🔢 Exemple

Pour un capital de **1 000 $**, avec un taux d'intérêt annuel de **5 %** pendant **3 ans** :

- Capital : 1 000 $
- Taux : 5 % = 0,05
- Durée : 3 ans

### Calcul de l'intérêt

```text
I = 1000 × 0,05 × 3
I = 150 $
```

### Montant total

```text
A = 1000 + 150
A = 1150 $
```

## ⚙️ Fonctionnement

Le calculateur doit permettre à l'utilisateur de :

1. Saisir le capital initial.
2. Saisir le taux d'intérêt.
3. Saisir la durée.
4. Lancer le calcul.
5. Afficher l'intérêt généré.
6. Afficher le montant total.

## ✅ Validation des données

Les entrées doivent respecter les règles suivantes :

- Le capital doit être supérieur à `0`.
- Le taux d'intérêt doit être supérieur ou égal à `0`.
- La durée doit être supérieure à `0`.
- Les valeurs saisies doivent être numériques.
- Le taux saisi en pourcentage doit être converti en décimal avant le calcul.

## 🎯 Objectif du projet

Ce calculateur constitue un exercice simple permettant de comprendre :

- la gestion des entrées utilisateur ;
- la validation des données ;
- l'application d'une formule mathématique ;
- le traitement des résultats ;
- la séparation entre les données d'entrée, la logique de calcul et l'affichage.

## 🚀 Évolutions possibles

Une version ultérieure pourrait intégrer :

- [ ] Le calcul des intérêts composés.
- [ ] Différentes fréquences de calcul.
- [ ] La gestion de plusieurs devises.
- [ ] Un historique des calculs.
- [ ] Des graphiques d'évolution du capital.
- [ ] L'export des résultats.
