# aframe-presentation-kit

Diapositives de démarrage officielles pour donner des conférences et des présentations sur A-Frame.

[VIEW SLIDES](https://mariot.github.io/aframe-presentation-kit/#/)

## Installation

1. [Télécharger le dépot (.ZIP)] (http://github.com/mariot/aframe-presentation-kit/zipball/master) (> 200MB)
2. Démarrez le serveur local (`npm run start`)
3. Ouvrez `http://localhost:8080` dans votre navigateur

## Table des matières
- Introduction
- Réalité virtuelle
   - Matériel
   - Friction des écosystèmes VR
- WebVR
   - Avantages
   - API
   - Navigateurs
   - Métaverse
   - Barrière à l'entrée
- A-Frame
   - Introduction
   - Hello World
   - Démo
   - Fonctionne avec tout
- Entité-Composant-Système
   - Concept
   - Composer une entité
   - Registre
   - Inspecteur
- Communauté
   - Exemples
   - Nombres

## Modifier le Design

Le kit utilise [reveal.js] (https://github.com/hakimel/reveal.js/), un
framework HTML de présentation. Si vous souhaitez personnaliser, lisez
leur documentation pour voir comment configurer et mettre en forme
le jeu de diapositives.

Pour le style, le thème du kit est basé sur le thème blanc trouvé dans le reveal.js
dépôt. Ceci a été copié dans `src/main.css` que vous pouvez remplacer ou
modifier.

## Modifier le Contenu

Modifiez le fichier **content.md** pour modifier le contenu.
Les diapositives sont écrites en Markdown et séparé par six traits d'union "------".
Vous pouvez également ajouter des diapositives verticales séparé par
trois traits d'union `---`. Les diapositives sont regroupées, en utilisant des
diapositives verticales pour forer ou construire sur des points généraux.
Vous pouvez ajouter des notes de conférence
en plaçant le contenu sous `<! - NOTES ->` sur chaque diapositive.

Adaptez le contenu à votre public. Filtrer les diapositives en fonction des réponses
à ces questions (ainsi que la durée de votre exposé). Par exemple:

- **Votre public est-il familier avec la réalité virtuelle?** - Si oui, vous voudrez peut-être sauter ou réduire la section *Réalité Virtuelle*.
- **Votre audience s'intéresse-t-elle au code sous-jacent (c.-à-d. JavaScript, composants A-Frame, three.js)?** - Sinon, rognez la section *Entity-Component-System*.

### Ajouter des scènes A-Frame


Les scènes A-Frame sont intégrées directement dans les diapositives, ce qui vous permet de faire une démonstration sans
devoir s'éloigner. Le kit reconnaîtra `<div data-aframe-scene="scenes/yourscene.html"> </div>`et se chargera dans la scène A-Frame.

## Déploiement

Dans la page des paramètres de votre dépot GitHub sous **Pages GitHub** et *Source*,
sélectionnez "branche master". Ensuite, appuyez simplement sur votre dépôt GitHub, puis votre
les diapositives seront en direct sur `https://votrenom.github.io/aframe-presentation-kit`
ou tout ce que vous avez nommé le dépot. [En savoir plus sur les Pages GitHub] (https://github.com/blog/2228-simpler-github-pages-publishing).

## En présentant
Servir les diapositives localement à partir de votre ordinateur pour une meilleure performance du réseau.

Appuyez sur la touche `f` de votre clavier pour passer en plein écran. Appuyez sur la touche `s` de votre
clavier pour ouvrir la fenêtre **Speakers Notes**. Appuyez sur la touche `<esc>` ou `o` de votre clavier pour voir une vue agrandie des diapositives.

Il y a des diapositives avec des scènes A-Frame incorporées. Jouez avec ces scènes en direct depuis la diapositive. Cliquez et faites glisser pour regarder autour. Vous pouvez entrer en plein écran, ou si vous avez un casque connecté, entrer en VR.

Ouvrez une scène dans l'inspecteur A-Frame en appuyant sur `<ctrl>+<alt>+i` sur votre clavier. Cela ouvrira une scène A-Frame intégrée dans un outil visuel.

Jetez un coup d'oeil à ce [guide pour parler en public] (http://speaking.io/) et bonne chance!
