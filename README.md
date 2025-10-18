⚠️ Chaque jour, un **fragment** apparait dans la matrice, injecté quotidiennement dans le code vert de GitHub.  
Mais les yeux les plus attentifs sauront remarquer **l’anomalie**, le premier qui le trouve pourra annoncer :

> “J’ai trouvé le Space Invader infiltré dans la matrice du Git d’un jeune développeur de Paris !”
*Jeune développeur … frère de Néo, ou du moins c’est ce que certains murmurent, parce qu’il aurait un frère nommé Noé.*

Il n’y a **pas de récompense financière**, cependant… sauf ce tas de billets 💸  

Seulement ce tas de billets virtuels 💸
```
🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙✨✨
🪙🪙🪙🪙🪙💵🪙🪙💵🪙🪙🪙🪙🪙🪙🪙✨✨✨
🪙🪙💵🪙💵💵💵💵💵🪙💵🪙🪙🪙🪙✨✨
🪙🪙💵💵💵💵💵💵💵💵💵🪙🪙🪙✨
🪙🪙🪙💵👽💰💵👽💰💵🪙🪙🪙🪙🪙✨✨
🪙🪙💵💵💵💵💵💵💵💵💵🪙🪙🪙🪙🪙✨✨✨
🪙🪙💵🪙💵🪙🪙🪙💵🪙💵🪙🪙🪙🪙✨
🪙💵💵🪙💵💵🪙💵💵🪙💵💵🪙🪙🪙✨✨
🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙🪙✨✨
```
et la satisfaction d’avoir perçu la faille avant les autres.

---

Bienvenue dans **GitHub Pixel Art** !

# 🎨 GitHub Pixel Art – Space Invader à Paris

Ce dépôt permet de **planifier et générer des motifs** sur ma grille de contributions GitHub, en transformant chaque jour de commit en un pixel de couleur sur ta grille.
Mais attention… ce n’est pas un projet comme les autres : **Paris est envahi par les Space Invaders**, et un s'immisce même dans ma grille GitHub… saurez-vous le repérer ?

![Pixel Art Banner](banner.jpg)

---

## 🌟 Histoire

Chaque curieux à Paris sait que la ville cache ses secrets…
Moi, dev parisien, j’ai décidé de laisser un **Space Invader discret** dans mon GitHub, infiltré dans ma grille de contributions.
Il apparaît chaque jour, **injecté**, il se cache parmi mes contributions.
Qui sera le premier à le découvrir ? 🔍

Chaque jour, **à 23h30 précises**, un fragment discret s’immisce dans ma grille GitHub.  
Il ne peut pas se révéler en entier d’un seul coup : trop volumineux pour passer d’un bloc à l’autre.  
Ainsi, **jour après jour**, il s’injecte progressivement, pixel par pixel, fragment par fragment, jusqu’à ce que sa forme complète devienne perceptible.

Chaque case verte de ta grille représente une journée active, et chaque “1” dans la matrice est un pixel du Space Invader qui prend vie.
L’inspiration vient de **l’invasion des Space Invaders sur Paris**, mais cette fois-ci, le jeu se joue directement dans ton profil GitHub !

## 🕹️ Première matrice : Space Invader

Voici le tout premier motif utilisé, un **mini Space Invader** dans une grille 7x10 (jours x semaines) :

```python
pattern = [
  [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,1,0,0,0,0],  # dim
  [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,1,1,1,1,1,0,1,0,0],  # lun
  [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,1,1,1,1,1,1,1,0,0],  # mar
  [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,1,0,0,1,0,0,0],  # mer
  [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,1,1,1,1,1,1,1,0,0],  # jeu
  [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,1,0,0,0,1,0,1,0,0],  # ven
  [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,0,1,1,0,1,1,0,1,1,0],  # sam
]
```

> Chaque `1` correspond à une case verte (active), chaque `0` correspond à une case vide.
> Ce motif est le tout premier **easter egg** caché dans mon GitHub.

---

## 🚀 Fonctionnalités

* Grille interactive **7x52 semaines** (année actuelle)
* **Cases cliquables** pour créer ton motif
* **Jours hors année grisées**
* **Export automatique** de la matrice pour Python ou autre
* Indication de la **case correspondant à aujourd'hui**
* Total des contributions pris en compte pour reproduire la couleur exacte de GitHub
* **Mise en évidence de la case du jour** pour ne jamais perdre ton pixel magique

---

## 🎮 Usage

1. Ouvrir le fichier `index.html` ou le **CodePen lié**.
2. Cliquer sur les cases pour créer ton dessin.
3. Exporter la matrice via le bouton **Exporter la matrice**.
4. (Optionnel) Ajouter la matrice au workflow pour générer les commits automatiquement et laisser tes Space Invaders s’infiltrer dans la grille.

---

## 💡 Bonus

* Adaptation automatique à l’année courante
* Possibilité d’injecter tes propres motifs ou **nouveaux easter eggs** dans la grille
* Démo live possible sur **CodePen** pour tester la grille interactive et visualiser les Space Invaders en action

---

> Préparez vos yeux et vos commits… Paris n’a jamais été aussi pixelisé ! 🛸
