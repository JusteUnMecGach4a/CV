# Maintenance du CV - Léo Canova-Prévot

Ce document explique comment gérer et mettre à jour votre CV hébergé sur GitHub Pages.

## Actions effectuées
1. **Récupération du dépôt** : Clonage de `JusteUnMecGach4a/CV`.
2. **Mise à jour du thème** : Passage du thème "Valentin" au thème "Fête du Travail" (Vert/Blanc).
3. **Activation de GitHub Pages** : Activation via l'API GitHub pour héberger le CV sur `https://justeunmecgach4a.github.io/CV/`.
4. **Automatisation des thèmes** : Mise en place d'un script JavaScript pour changer automatiquement le style selon les fêtes françaises.

## Guide de mise à jour future

### Modifier le contenu (Informations, Expériences)
1. Ouvrez `index.html`.
2. Modifiez le texte dans les balises correspondantes (ex: `<p class="text-content">`).
3. Enregistrez et poussez les changements (`git commit -m "..." && git push`).

### Modifier les styles des fêtes
Les thèmes sont définis dans `style.css` sous forme de variables CSS. Chaque fête a ses propres variables (ex: `--holiday-bg`, `--holiday-primary`).

### Ajouter une nouvelle fête
1. Ajoutez les variables dans `style.css` dans une classe `.theme-[nom-fete]`.
2. Mettez à jour le script `setHolidayTheme()` dans `index.html` pour inclure la date de la nouvelle fête.

## Liste des fêtes supportées
- **Jour de l'An** : 1er Janvier
- **Saint-Valentin** : 14 Février
- **Fête du Travail** : 1er Mai
- **Victoire 1945** : 8 Mai
- **Fête Nationale** : 14 Juillet
- **Halloween** : 31 Octobre
- **Toussaint** : 1er Novembre
- **Armistice** : 11 Novembre
- **Noël** : 25 Décembre

## Lien du CV en direct
[https://justeunmecgach4a.github.io/CV/](https://justeunmecgach4a.github.io/CV/)
