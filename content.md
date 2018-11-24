<!-- .slide: data-background="media/img/aframe.jpg" -->

<div class="talk-title">
  <h1>A-Frame</h1>
  <p>Un framework web pour construire des expériences de réalité virtuelle</p>
  <p class="talk-info">
    @mozilla | Mozilla Tech Speakers | **aframe.io**
  </p>
</div>

<!-- NOTES -->
- Intégrer les développeurs Web dans le monde 3D et VR avec des outils faciles à utiliser
- Expériences WebVR plus rapides

------

# Realité Virtuel

<!-- .slide: data-background-video="media/video/virtualreality.mp4" data-background-video-loop="true" data-background-video-muted="true" data-state="state--bg-dark" -->

<!-- NOTES -->
- Demander combien ont déjà essayé VR.
- La réalité virtuelle est une plateforme technologique qui vous transporte dans des environnements 3D réalistes, interactifs et immersifs
- C'est la prochaine plate-forme, va changer notre façon de travailler + jouer + communiquer numériquement, visage de la société

---

<div class="image-row">
  <div><img data-src="media/img/google-cardboard.png"></div>
  <div><img data-src="media/img/google-daydream.png"></div>
  <div><img data-src="media/img/samsung-gearvr.png"></div>
</div>

<div class="image-row">
  <div><img data-src="media/img/oculus-rift.png"></div>
  <div><img data-src="media/img/playstation-vr.png"></div>
  <div><img data-src="media/img/htc-vive.png"></div>
</div>

<!-- NOTES -->
- Soutenu par les plus grandes entreprises du monde, tout le monde veut
- Gamme de bon marché à cher, attaché et non connecté, contrôleurs, suivi
- HTC Vive avec Steam offre actuellement les expériences les plus convaincantes, mais ne sait jamais
- Voir beaucoup de différents appareils, systèmes, plates-formes en concurrence les uns contre les autres ...

---

## Friction des Ecosystemes VR

<div class="captioned-image-row">
  <div>
    <img data-src="media/img/gatekeeper.png">
    <i>Gatekeepers</i>
  </div>
  <div>
    <img data-src="media/img/downloads-installs.png">
    <i>Installations</i>
  </div>
  <div>
    <img data-src="media/img/closed-door.png">
    <i>Fermés</i>
  </div>
</div>

<!-- NOTES -->
- Les magasins d'applications et les entreprises contrôlent la distribution: peuvent supprimer ou bloquer du contenu
- Les téléchargements / installations sont un obstacle à la consommation: petites pages professionnelles
- Écosystème fermé: moteurs propriétaires, courbes d'apprentissage abruptes, expériences en silos, fragmentation
- Nous voulons que la VR réussisse, nous voulons donc une plate-forme sans ces points de friction. La réponse est WebVR ...

------

# WebVR

Une plate-forme de réalité virtuelle ouverte avec les avantages du **Web**

<div class="captioned-image-row">
  <div>
    <img data-src="media/img/web-is-open.png">
    <i>Ouvert</i>
  </div>
  <div>
    <img data-src="media/img/web-is-connected.png">
    <i>Connecté</i>
  </div>
  <div>
    <img data-src="media/img/web-is-instant.png">
    <i>Instantanné</i>
  </div>
</div>

<!-- NOTES -->
WebVR est ... la réalité virtuelle dans le navigateur, alimenté par Internet

Ouvert:
- Tout le monde peut publier
- Culture Open Source avec des standards ouverts

Connecté:
- Traverser des mondes

Instantannés:
- Cliquez sur un lien sur Twitter ou Weibo, expériences VR immédiates
- Aucune installation
- Imaginez pour les expériences de longue queue: shopping et espaces personnels
- Idéal pour les expériences de bouchée de longue queue

Transition:
- Le Web a des avantages qui en font la meilleure plateforme pour les gens
- Besoin d'agir pour en faire une réalité, ne peut pas attendre que le VR soit cuit et cristallisé
- Être impliqué

---

<img class="stretch" data-src="media/img/webvr.png">

API de navigateur qui permettent le rendu WebGL sur les casques d'écoute et l'accès aux capteurs VR

https://w3c.github.io/webvr/

<!-- NOTES -->
API:
- Chemin de rendu optimisé pour les casques
- Position d'accès et rotation (pose) des données

Histoire:
- API WebVR initiale par Mozilla
- Groupe de travail communautaire W3C
- Mozilla, Google, Samsung, Microsoft, communauté en cours d'itération API WebVR 1.0

Pas seulement une spécification, c'est implémenté ...

---

https://webvr.rocks

<div class="captioned-image-row small">
  <div>
    <img data-src="media/img/firefox-nightly.png">
    <i>Firefox Nightly</i>
  </div>
  <div>
    <img data-src="media/img/edge.jpg">
    <i>Microsoft Edge</i>
  </div>
  <div>
    <img data-src="media/img/chromium.png">
    <i>Chromium</i>
  </div>
</div>

<div class="captioned-image-row small">
  <div>
    <img data-src="media/img/chrome.jpg">
    <i>Chrome for Android</i>
  </div>
  <div>
    <img data-src="media/img/carmel.jpg">
    <i>Oculus Carmel</i>
  </div>
  <div>
    <img data-src="media/img/samsung-browser.png">
    <i>Samsung Internet</i>
  </div>
  <div>
    <img data-src="media/img/google-cardboard.png">
    <i>Mobile Polyfill</i>
  </div>
</div>

<!-- NOTES -->
- Firefox + Chrome WebVR 1.0 hits canaux de sortie d'ici début 2017
- Actuellement derrière Nightly, les constructions personnalisées et les drapeaux
- Polyfill mobile: utilisez des capteurs de mouvement / d'orientation pour polyfiler sur les smartphones
- Avec tous les navigateurs derrière ...

---

## Metaverse

<!-- .slide: data-background="media/img/metaverse.jpg" -->

<!-- NOTES -->
- Espaces virtuels collectifs persistants partagés
- Alterner la réalité numérique que le monde peut vivre, travailler, jouer
- Doit être décentralisé / ouvert / connecté, le Web est la meilleure plateforme pour réaliser pleinement
- Où commençons-nous?
- three.js résume WebGL, 3D et WebVR, mais pourrait encore le rendre plus accessible

---

Trop difficile de créer des expériences WebVR ...

---

<!-- .slide: data-background-video="media/video/boilerplate.mp4" data-state="state--bg-dark" -->

<div class="slide__boilerplate">
  <p>Importer le polyfill WebVR</p>
  <p>Configurer l'appareil photo</p>
  <p>Configurer les lumières</p>
  <p>Initialiser la scène</p>
  <p>Déclarer et passer la toile</p>
  <p>Écouter le redimensionnement de la fenêtre</p>
  <p>Installez VREffect</p>
  <p>Instancier le rendu</p>
  <p>Créer une boucle de rendu</p>
  <p>Précharger des éléments</p>
  <p>Déterminer la réactivité</p>
  <p>Traitez les méta-tags et les mobiles</p>
</div>

<!-- NOTES -->
- Il est encore trop difficile de créer des expériences WebVR
- Enorme obstacle pour faire de petits prototypes et des expériences
- Boilerplate doivent être mis à jour avec les nouvelles versions de WebVR, three.js et les caprices du navigateur
- Encapsuler tout cela en une seule ligne ...

------

# A-Frame

<!-- .slide: data-background="media/img/aframe-rendered-full.png" -->

Un framework web pour construire des expériences de réalité virtuelle

<!-- NOTES -->
- Lancé en décembre dernier
- Pourquoi:
   - Facile pour les développeurs Web de créer du contenu VR, sans connaissances graphiques
   - Prototyper et expérimenter WebVR et VR UX plus rapidement
   - Un véhicule pour relancer l'écosystème WebVR

---

## Hello World

<!-- .slide: data-background="media/img/aframe.jpg" data-transition="slide-in none" -->

```html
<html>
  <script src="https://aframe.io/releases/0.5.0/aframe.min.js"></script>
  <a-scene>





  </a-scene>
</html>
```
<!-- .element: class="stretch" -->

<!-- NOTES -->
- Juste du HTML
- Déposer une balise de script, pas de build
- Utilisation d'éléments HTML personnalisés
- Une ligne de HTML `<a-scene>` s'occupe de
   - toile, caméra, moteur de rendu, lumières, contrôles, boucle de rendu, polyfill WebVR, VREffect
- Mettre des choses à l'intérieur de notre scène ...

---

## Hello World

<!-- .slide: data-background="media/img/aframe.jpg" data-transition="fade-in slide-out" -->

```html
<html>
  <script src="https://aframe.io/releases/0.5.0/aframe.min.js"></script>
  <a-scene>
    <a-box color="#4CC3D9" position="-1 0.5 -3" rotation="0 45 0"></a-box>
    <a-cylinder color="#FFC65D" position="1 0.75 -3" radius="0.5" height="1.5"></a-cylinder>
    <a-sphere color="#EF2D5E" position="0 1.25 -5" radius="1.25"></a-sphere>
    <a-plane color="#7BC8A4" position="0 0 -4" rotation="-90 0 0" width="4" height="4"></a-plane>
    <a-sky color="#ECECEC"></a-sky>
  </a-scene>
</html>
```
<!-- .element: class="stretch" -->

<!-- NOTES -->
- Primitives 3D de base avec des éléments personnalisés
- Lisible: HTML sans doute le langage le plus accessible en informatique
- Encapsulé: copier-coller HTML ailleurs et encore travailler, pas d'état ou de variables
- Regardez rapidement un exemple en direct ...

---

## Hello Metaverse

<i>by Ada Rose Edwards (@lady_ada_king)</i>

<!-- .slide: data-background="media/img/metaverse.jpg" -->

<div class="stretch" data-aframe-scene="scenes/80s.html"></div>

<!-- NOTES -->
- Une scène A-Frame par Ada Rose Edwards en cours d'exécution à partir de l'intérieur de mes diapositives HTML
- Fonctionne sur ordinateur de bureau, Android, iOS, Samsung Gear VR, Oculus Rift, HTC Vive
- Pourrait ouvrir l'inspecteur DOM pour changer les valeurs en direct
- Puisque c'est juste du HTML ...

---

<!-- .slide: data-background="media/img/aframe.jpg" -->

## Works With Everything

<div class="captioned-image-row">
  <div>
    <img data-src="media/img/d3.png">
    <i>d3.js</i>
  </div>
  <div>
    <img data-src="media/img/vue.png">
    <i>Vue.js</i>
  </div>
  <div>
    <img data-src="media/img/react.png">
    <i>React</i>
  </div>
  <div>
    <img data-src="media/img/redux.png">
    <i>Redux</i>
  </div>
  <div>
    <img data-src="media/img/jquery.png">
    <i>jQuery</i>
  </div>
  <div>
    <img data-src="media/img/angular.png">
    <i>Angular</i>
  </div>
</div>

<!-- NOTES -->

- Basé sur HTML, compatible avec toutes les bibliothèques / frameworks existants
- Bonne raison d'avoir du HTML en tant que couche intermédiaire entre WebGL / three.js
- Tous les outils étaient au-dessus de la notion de HTML
- Sous le capot, A-Frame est un framework déclaratif et extensible pour three.js ...

------

# Entity-Component-System

<!-- .slide: data-background="media/img/minecraft-blocks.png" -->

<!-- NOTES -->
- Est un cadre d'entité-composant
- Populaire dans le développement de jeux, utilisé par Unity
- Tous les objets dans la scène sont des **entités** qui, par nature, vident des objets. Branchez les **composants** pour attacher l'apparence / le comportement / la fonctionnalité
- Web 2D où chaque élément a été réparé
- 3D / VR est différent, les objets de types et de complexités infinis, ont besoin d'un moyen facile de construire différents types d'objets

---

<!-- .slide: data-background="media/img/minecraft-blocks.png" data-transition="slide-in none" -->

## Composer un Entité

```html
<a-entity>
```
<!-- .element: class="stretch" -->

<!-- NOTES -->
- Commencer avec un <a-entity> `
- En soi, n'a pas d'apparence, le comportement, la fonctionnalité
- Branchez des composants pour ajouter de l'apparence, du comportement, de la fonctionnalité

---

## Composer un Entité

<!-- .slide: data-background="media/img/minecraft-blocks.png" data-transition="none" -->

```html
<a-entity
  geometry="primitive: sphere; radius: 1.5"
  material="color: #343434; roughness: 0.4; sphericalEnvMap: #texture">
```
<!-- .element: class="stretch" -->

<!-- NOTES -->
- Syntaxe similaire aux styles CSS
- Noms de composants en tant qu'attributs HTML
- Propriétés et valeurs des composants en tant que valeur d'attribut HTML

---

## Composer un Entité

<!-- .slide: data-background="media/img/minecraft-blocks.png" data-transition="none" -->

```html
<a-entity
  geometry="primitive: sphere; radius: 1.5"
  material="color: #343434; roughness: 0.4; sphericalEnvMap: #texture"
  position="-1 2 4" rotation="45 0 90" scale="2 2 2">
```
<!-- .element: class="stretch" -->

---

## Composer un Entité

<!-- .slide: data-background="media/img/minecraft-blocks.png" data-transition="none" -->

```html
<a-entity
  geometry="primitive: sphere; radius: 1.5"
  material="color: #343434; roughness: 0.4; sphericalEnvMap: #texture"
  position="-1 2 4" rotation="45 0 90" scale="2 2 2"
  animation="property: rotation; loop: true; to: 0 360 0"
  movement-pattern="type: spline; speed: 4">
```
<!-- .element: class="stretch" -->

---

## Composer un Entité

<!-- .slide: data-background="media/img/minecraft-blocks.png" data-transition="none" -->

```html
<a-entity
  json-model="src: #robot"
  position="-1 2 4" rotation="45 0 90" scale="2 2 2"
  animation="property: rotation; loop: true; to: 0 360 0"
  movement-pattern="type: spline; speed: 4">
```
<!-- .element: class="stretch" -->

---

## Composer un Entité

<!-- .slide: data-background="media/img/minecraft-blocks.png" data-transition="none" -->

```html
<a-entity
  json-model="src: #robot"
  position="-1 2 4" rotation="45 0 90" scale="2 2 2"
  animation="property: rotation; loop: true; to: 0 360 0"
  movement-pattern="type: attack; target: #player"
  explode="on: hit">
```
<!-- .element: class="stretch" -->

---

<!-- .slide: data-background="media/img/standard-components.png" data-background-size="contain" -->

<!-- NOTES -->
- Voici quelques composants livrés avec A-Frame
- A-Frame est entièrement extensible à sa base donc ...

---

<!-- .slide: data-background="media/img/community-components.png" data-background-size="contain" -->

<!-- NOTES -->
- La communauté a rempli l'écosystème avec des tonnes de composants
- Les composants peuvent faire ce qu'ils veulent, avoir un accès complet à three.js et API Web
- L'écosystème des composants est la pierre angulaire de A-Frame
- Physique, mouvement de saut, systèmes de particules, visualisations audio, océans
- Déposez ces composants en tant que balises de script et utilisez-les directement à partir du HTML
- Des développeurs avancés habilitant d'autres développeurs
- Travailler sur la collecte de ces composants ...

---

# Registre

<!-- .slide: data-background-color="#333" -->

Collection organisée de composants A-Frame.

<a class="stretch" href="https://aframe.io/aframe-registry">
  <video loop data-src="media/video/registrypreview.mp4" data-autoplay></video>
</a>

<!-- NOTES -->
- Collecte dans le registre A-Frame
- Comme un magasin de composants que nous nous assurons de bien marcher
- Les gens peuvent parcourir et rechercher des composants ou les installer ....

---

# Registre

<!-- .slide: data-background-color="#333" -->

Collection organisée de composants A-Frame.

<video loop data-src="media/video/leaphands.mp4" data-autoplay></video>

---

## Inspecteur

<!-- .slide: data-background="media/img/inspector.png" data-state="state--bg-dark" -->

Outil visuel pour A-Frame. Juste `<ctrl>+<alt>+i`.

<div class="stretch" data-aframe-scene="scenes/80s.html"></div>

------

<!-- .slide: data-background="media/img/header.png" -->

# Communauté

https://aframe.io/blog/

---

<!-- .slide: data-background="media/img/apainter.gif" -->

# Art - *A-Painter*

@mozillavr

---

<!-- .slide: data-background="media/img/syria.gif" -->

# Journalism - *Fear of the Sky*

Amnesty International UK

---

<!-- .slide: data-background="media/img/mars.jpg" -->

# Journalism - *Journey to Mars*

The Washington Post

---

<!-- .slide: data-background="media/img/citybuilder.gif" -->

# Sandbox - *City Builder*

@kfarr

---

<!-- .slide: data-background="media/img/adit.gif" -->

# Data Visualization - *Adit*

@datatitian

---

<!-- .slide: data-background="media/img/a-blast.gif" -->

# Gaming - *A-Blast*

@mozillavr

---

<!-- .slide: data-background="media/img/ux.gif" -->

# Prototyping - *UI Widgets*

@whoyee

---

<!-- .slide: data-background="media/img/math.gif" -->

# Mathematics - *MathworldVR*

@sleighdogs

---

<!-- .slide: data-background="media/img/ar.gif" -->

# AR - *AR.js + A-Frame*

@jerome_etienne

---

<!-- .slide: data-background="media/img/webvrstudio.png" -->

# Tools - *WebVR Studio*

@webvrstudio

---

<!-- .slide: data-background-video="media/video/livetour.mp4" data-background-video-loop="true" -->

# Real Estate - *Live Tour*

iStaging

---

<!-- .slide: data-background="media/img/cadavr.gif" -->

# Education - *CadaVR*

@drryanjames

---

# aframe.io

<div class="captioned-image-row">
  <div>
    <img data-src="media/img/github.png">
    <i>180+ contributeurs 6000+ Stargazers</i>
  </div>
  <div>
    <img data-src="media/img/slack.png">
    <i>Plus de 4000 membres sur Slack</i>
  </div>
  <div>
    <img data-src="media/img/scene-collage-circle.png">
    <i>100s de projets en vedette</i>
  </div>
</div>

<!-- NOTES -->
- Projet open source et inclusif
- La plupart du travail effectué sur GitHub
- Communauté active sur Slack pour partager des projets, interagir, sortir, demander de l'aide
- Projets en vedette sur le référentiel `awesome-aframe` et sur le blog *A Week of A-Frame*
