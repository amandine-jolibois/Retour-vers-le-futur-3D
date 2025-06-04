# 🚀 Scène 3D — Retour vers le Futur (Metaverse TP)

Ce projet est une expérience immersive en 3D réalisée avec [A-Frame], inspirée de l’univers culte du film **Retour vers le Futur**.  
Il a été développé dans le cadre d’un TP de modélisation 3D & d’intégration interactive en HTML/VR.

---

## 🧭 Description de la Scène

La scène se déroule dans une **rue typique des années 80**, intégrant les éléments suivants :

- 🏙️ Environnement urbain : bâtiments rétro, route, station-service, lampadaires, mobilier urbain
- 🚗 **DeLorean** au centre de la rue
- 🧑‍🔬 **Doc** & **Marty** modèles 3D
- 🛹 **Hoverboard** flottant et interactif
- 📺 **Télévision rétro** affichant une vidéo du film
- 🎛️ **Générateur temporel** création originale animée
- 💡 Éclairage dynamique et ambiance rétro

---

## 🎮 Interactions & Comportements

### 🖱️ Interactions au clic

| Objet              | Effet déclenché                                                              |
|--------------------|------------------------------------------------------------------------------|
| **DeLorean**       | Joue le son du moteur                                |
| **Télévision**     | Allume ou éteint l’écran / démarre ou met en pause une vidéo intégrée        |
| **Hoverboard**     | L’objet flotte plus haut pendant un instant (effet boost)                    |
| **Cube orange**    | Survol = couleur verte + agrandissement<br>Clic = rotation + changement rose |
| **Sphère cyan**    | Survol = brillance + échelle<br>Clic = rebond + couleur rouge                |
| **Cylindre violet**| Réagit au clic et survol avec des transformations visuelles                  |

---

## 📼 Éléments multimédia

- 🎥 Vidéo du film intégrée dans l’écran 
- 🎇 Éclairage dynamique sur certains objets (générateur, lampadaires…)

---

## 🛠️ Technologies utilisées

- **HTML** + [A-Frame 1.4.2]
- **GLTF** / **GLB** modèles 3D
- **Composants personnalisés** :
  - `tv-controller`
  - `car-sound`
  - `hoverboard-interaction`

---

## 📁 Arborescence du projet

```
Projet_BTTF/
├── index.html
├── assets/
│   ├── textures/     ← textures sol, mur, ciel
│   ├── images/       ← posters
│   ├── audio/        ← sons moteur
│   └── video/        ← extraits vidéos
├── models/           ← modèles GLB : delorean, doc, marty, hoverboard
└── README.md
```

---

## 🧪 Pour tester

1. Ouvrir un terminal dans le dossier du projet
2. Lancer un serveur local :

   python -m http.server 8080
   
3. Accéder à :  
   👉 `http://localhost:8080`

---

