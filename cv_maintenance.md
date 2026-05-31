# Maintenance du CV - Léo Canova-Prévot

Ce document explique comment gérer et mettre à jour votre CV hébergé sur GitHub Pages.

## Actions effectuées
1. **Récupération du dépôt** : Clonage de `JusteUnMecGach4a/CV`.
2. **Hébergement en ligne** : Configuration de GitHub Pages pour héberger le CV en direct sur `https://justeunmecgach4a.github.io/CV/`.
3. **Moteur saisonnier intelligent** : Mise en place d'un algorithme JavaScript calculant automatiquement le thème saisonnier selon la fête la plus proche (21 fêtes gérées avec bannières dynamiques interactives).
4. **Mois de la Pride** : Création d'un thème arc-en-ciel élégant pour tout le mois de juin, doté d'un header en dégradé multicolore.
5. **Neutralisation PDF stricte** : Garantie que les thèmes saisonniers et bannières n'influent aucunement sur l'export PDF (le rendu imprimé reste 100 % professionnel et neutre).
6. **Menu de sélection manuelle** : Intégration d'un menu déroulant en glassmorphism discret dans le header permettant d'outrepasser l'algorithme automatique avec sauvegarde persistante (`localStorage`).

## Guide de mise à jour future

### Modifier le contenu (Informations, Expériences)
1. Ouvrez `index.html`.
2. Modifiez le texte dans les balises correspondantes (ex: `<p class="text-content">`).
3. Enregistrez et poussez les changements (`git commit -m "..." && git push`).

### Modifier les styles des thèmes de fêtes
Les thèmes saisonniers sont définis dans `style.css` sous forme de variables CSS injectées sur l'attribut `[data-holiday="..."][data-theme="..."]`. Vous pouvez y ajuster les couleurs primaires/secondaires, les bordures, ombres et effets de lueur.

### Liste des 21 événements et thèmes saisonniers supportés
- **Nouvel An** (`new-year`) : Or & Indigo Nuit (`✨`)
- **Saint-Valentin** (`valentine`) : Rose & Rouge Passion (`❤️` animée)
- **Fête des Grands-Mères** (`grandmothers-day`) : Lavande & Violet (`💜` animée)
- **Saint-Patrick** (`st-patrick`) : Trèfle Vert & Émeraude (`🍀`)
- **Printemps** (`spring`) : Blossom Pink & Vert Tendre (`🌸`)
- **Pâques** (`easter`) : Lime & Jaune Pastel (`🐣`)
- **Jour de la Terre** (`earth-day`) : Vert Botanique & Bleu Océan (`🌍`)
- **Fête du Travail** (`labor-day`) : Vert Muguet & Émeraude (`🌸`)
- **Fête des Mères** (`mothers-day`) : Rose Poudré & Or Rose (`❤️` animée)
- **Fête des Pères** (`fathers-day`) : Oxford & Bleu Denim (`👔`)
- **Mois des Fiertés (Pride Month)** (`pride-month`) : Dégradé Arc-en-ciel vibrant ou pastel (`🌈`)
- **Solstice d'Été (Bel Été)** (`summer`) : Soleil Jaune & Sable (`☀️`)
- **Fête de la Musique** (`music-day`) : Synthwave Violet/Cyan (`🎵`)
- **Fête du Cinéma** (`cinema-day`) : Tapis Rouge & Or (`🎬`)
- **Fête Nationale** (`national-day`) : Patriotique Bleu/Blanc/Rouge (`🇫🇷`)
- **Rentrée Scolaire** (`back-to-school`) : Vert Tableau & Craie Jaune (`🎒`)
- **Journée des Développeurs** (`programmer-day`) : Rétro Cyber Terminal Vert/Noir (`💻` animée)
- **Halloween** (`halloween`) : Citrouille & Noir Sombre (`🎃`)
- **Armistice** (`armistice`) : Devoir de mémoire Bleuets & Gris (`🕊️`)
- **Automne & Thanksgiving** (`autumn`) : Cuivré & Ambré (`🍁`)
- **Noël** (`christmas`) : Magique Rouge/Vert/Or (`🎄`)

## Lien du CV en direct
[https://justeunmecgach4a.github.io/CV/](https://justeunmecgach4a.github.io/CV/)
