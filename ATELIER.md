# Git initiation

Exercice Git

## Étape 1 : Création d'un dépôt

1. **Initialisez un dépôt vide** pour démarrer l’atelier.
2. **Créez un fichier `README.md`** et ajoutez-y un texte d'introduction. Effectuez un premier commit pour sauvegarder cette version initiale du dépôt.

## Étape 2 : Création de branches et modifications simples

1. **Créez une branche `feature-a`** et ajoutez une nouvelle section dans `README.md`. Faites un commit de cette modification.
2. **Retournez sur la branche principale** et créez une autre branche appelée `feature-b`. Ajoutez une autre section dans `README.md` et faites un commit.

## Étape 3 : Fusion de branches sans conflit

1. **Fusionnez la branche `feature-a` dans `main`**. Observez ce qui se passe lorsque la fusion est simple.
2. **Fusionnez ensuite `feature-b` dans `main`**. Notez l’effet de cette seconde fusion et les différences avec la première.

## Étape 4 : Création d’un conflit de fusion

1. **Créez une branche `feature-c`** à partir de `main` et modifiez une ligne existante dans `README.md`. Faites un commit.
2. **Retournez sur la branche `main`**, modifiez la même ligne que celle modifiée dans `feature-c` et faites un commit.
3. **Tentez de fusionner `feature-c` dans `main`** et résolvez le conflit qui se présente.

## Étape 5 : Rebase avec conflit

1. **Créez une branche `feature-d`** à partir de `main` et ajoutez un nouveau fichier, puis faites un commit.
2. **Créez une autre branche, `feature-e`, également à partir de `main`**. Dans cette branche, modifiez le fichier `README.md` en y ajoutant du contenu dans une section qui se trouve aussi dans `feature-d`, puis faites un commit.
3. **Revenez sur `feature-d`** et ajoutez une modification dans `README.md` au même endroit que celle de `feature-e`, puis faites un nouveau commit.
4. **Fusionnez `feature-d` dans `main`.
5. Rebasez `feature-e` sur `main`. Vous devriez faire face à un conflit.

   - **Résolvez le conflit** en choisissant quelle version intégrer ou en combinant les changements.
   - Terminez le rebase une fois les conflits résolus.

## Étape 6 : Conclusion et nettoyage

1. **Fusionnez les branches restantes dans `main`** si nécessaire pour finaliser le travail.
2. **Supprimez les branches locales** utilisées dans cet atelier une fois la fusion terminée.

---

Cette étape supplémentaire permet aux étudiants de manipuler et résoudre un conflit dans le contexte spécifique d’un rebase, ce qui offre une expérience complète de la gestion des branches dans Git.