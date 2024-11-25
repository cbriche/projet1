# **Mecamina - Gestion des Performances et Résolution de Problèmes**
# **A Noter ceci est un excercice, rien ne fonctionnera - NE PAS TELECHARGER**

## **Description**
**Mecamina** est une solution d'analyse et d'optimisation pour une entreprise de e-commerce BtoB opérant à l'international. Le projet vise à diagnostiquer et résoudre les problèmes liés à la baisse de chiffre d'affaires, tout en améliorant la gestion interne (ventes, finances, logistique, et RH). Ce projet repose sur des outils collaboratifs (Trello, Google Sheets) et des analyses poussées via SQL et Power BI.

---

## **Objectifs**
- Diagnostiquer la **baisse de CA** au Q1 2024 (-15 % par rapport à Q1 2023).
- Proposer des solutions concrètes pour :
  - Optimiser la **gestion des stocks** et des produits phares.
  - Améliorer les **performances commerciales** des équipes.
  - Maximiser le **recouvrement des créances**.
- Renforcer les décisions stratégiques par des **KPI** ciblés.

---

## **Installation et Pré-requis**
1. **Outils nécessaires** :
   - SQL (gestion des bases de données).
   - Trello (suivi des tâches).
   - Power BI (visualisation des données).
   - Google Sheets (dictionnaire des données et suivi des KPI).
   
2. **Environnement requis** :
   - Accès aux données e-commerce (ventes, stocks, performances RH).
   - Permissions pour l'intégration Power BI.

3. **Configuration** :
   - Clonez le dépôt :
     ```bash
     git clone https://github.com/username/mecamina.git
     ```
   - Configurez les connexions SQL dans le fichier `config/database.json`.

---

## **Utilisation**
1. **Analyse des Ventes** :
   - Identifier les produits les plus et les moins performants.
   - Comparer les chiffres d'affaires par catégorie et par pays.
   - Suivre les variations de taux de marge pour une prise de décision éclairée.

2. **Analyse RH** :
   - Identifier les meilleurs vendeurs (Top 2/3) sur une période donnée.
   - Détecter les points de faiblesse pour planifier des formations.

3. **Analyse Logistique** :
   - Quantifier les stocks invendus et les immobilisations financières.
   - Classer les produits par popularité pour ajuster les commandes.

4. **Analyse Financière** :
   - Suivre les encours clients et les créances.
   - Optimiser la gestion des fournisseurs.

---

## **KPI Développés**
### **Ventes**
- Nombre de produits vendus par catégorie et par mois avec taux de variation.
- Top bureau en CA et flop bureau en CA.

### **Logistique**
- Top 5 des produits les plus et les moins commandés (avec quantités en stock).

### **RH**
- Classement des meilleurs vendeurs sur le dernier mois (Top 2/3).

### **Finances**
- Encours clients et chiffre d'affaires des commandes des deux derniers mois par pays.

---

## **Licence**
Ce projet est sous licence [MIT](LICENSE).

---

## **Équipe**
- **Scrum Master** : Mireille
- **Product Owner** : Kassim
- **Tech Members** : Sofiane, Corinne
