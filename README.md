# AHP – Outil d'aide à la décision multicritère

Application web interactive basée sur le **Processus de Hiérarchie Analytique (AHP)**.  
Elle vous permet de définir des critères et des alternatives, de les comparer par paires,  
de vérifier la cohérence de vos jugements et d’identifier la meilleure alternative.

## 🌟 Fonctionnalités

- ✅ Définition dynamique des critères (quantitatifs ou catégoriels avec échelle de préférence)
- ✅ Ajout / suppression d’alternatives à volonté
- ✅ Saisie des scores de chaque alternative pour chaque critère (champ libre ou menu déroulant)
- ✅ Matrice de comparaison par paires des critères selon l’échelle de Saaty (1 à 9)
  - Réciprocité automatique du triangle inférieur
- ✅ Vérification de la cohérence via le rapport de cohérence (CR)
  - **Si CR ≤ 0,1** : affichage des poids des critères, classement final et mise en avant de la meilleure alternative
  - **Si CR > 0,1** : message d’incohérence et identification des paires les plus problématiques
- ✅ Mise à jour automatique de toutes les sections (pas de bouton « Actualiser »)
- ✅ Calcul déclenché uniquement par un bouton dédié

## 🚀 Utilisation

1. **Définir**  
   - Saisissez le nom de vos critères et choisissez leur type (quantitatif ou catégoriel).  
   - Pour un critère catégoriel, définissez les catégories et leurs valeurs (ex. Excellent = 9).  
   - Ajoutez vos alternatives.

2. **Évaluer**  
   - Remplissez le tableau des scores : pour chaque alternative, indiquez une valeur numérique (critère quantitatif) ou choisissez la catégorie correspondante.

3. **Comparer**  
   - Remplissez uniquement les cases **au‑dessus de la diagonale** de la matrice de comparaison des critères.  
   - Utilisez l’échelle de Saaty : 1 = importance égale, 9 = importance extrême.  
   - Les cases inférieures se calculent automatiquement.

4. **Décider**  
   - Cliquez sur le bouton **« Calculer »**.  
   - Si la matrice est cohérente, vous obtenez les poids des critères, les scores finaux et le nom de la meilleure alternative.  
   - En cas d’incohérence, l’outil vous explique pourquoi et vous guide pour corriger les comparaisons.

## 🛠️ Technologies

- HTML5, CSS3, TailwindCSS, JavaScript vanilla
- Aucune dépendance externe
- Fonctionne entièrement côté client

## 👤 Auteur

Projet réalisé dans le cadre du cours **Software Engineering** – Mai 2026.

## 📄 Licence

Libre de droit pour un usage éducatif.