
# 📘 README – Débogage d’une application React

## 🎯 Objectif

Ce travail consiste à déboguer une application React en utilisant React Developer Tools afin d’identifier les erreurs liées aux props, aux images et à la structure des composants, puis de corriger ces erreurs et vérifier le bon fonctionnement final.

---

# 📸 Étapes du débogage

---

## 🖼️ Capture 1 : Arborescence de l’application

### 🔍 Description :

Dans cette étape, j’ai ouvert **React Developer Tools** pour inspecter la structure des composants.

### 📌 Observation :

L’arbre des composants est le suivant :

* App
* PlayersList
* Player

### 🎯 Objectif :

Vérifier que les composants sont bien organisés et correctement affichés.

---

## 🐞 Capture 2 : Erreur de props (nom / name)

### 🔍 Description :

J’ai détecté une erreur dans les props du composant Player.

### ❌ Problème :

* Utilisation de `nom` au lieu de `name`

### 🛠️ Correction :

* Remplacement de `nom` par `name` dans le fichier `players.js`

### 🎯 Objectif :

Corriger les erreurs de transmission des données entre composants.

---

## 🖼️ Capture 3 : Erreur d’image (Messi)

### 🔍 Description :

L’image du joueur Messi ne s’affichait pas correctement.

### ❌ Problème :

* Mauvaise référence de l’image (`string` incorrect ou chemin mal importé)

### 🛠️ Correction :

* Correction de l’import de l’image dans `players.js`
  
### 🎯 Objectif :

Corriger l’affichage des images dans les cartes joueurs.

---

## ✅ Capture 4 : Vérification du code et affichage final

### 🔍 Description :

Après correction, j’ai vérifié l’application dans le navigateur.

### 📌 Résultat :

* Tous les joueurs s’affichent correctement
* Les images sont visibles
* Les informations sont correctes

### 🎯 Objectif :

Confirmer que toutes les erreurs sont résolues.

---

## 🧪 Capture 5 : Test des defaultProps

### 🔍 Description :

J’ai testé le comportement des `defaultProps`.

### 📌 Observation :

Lorsque certaines props sont absentes :

* Les valeurs par défaut sont affichées (ex: "Unknown", 0, image par défaut)

### 🎯 Objectif :

Vérifier la robustesse du composant Player face aux données manquantes.

---

# 🏁 Conclusion

Après débogage :

* Les erreurs de props ont été corrigées
* Les problèmes d’images ont été résolus
* L’application fonctionne correctement
* Les defaultProps assurent la stabilité des composants


