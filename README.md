#  LAB 1 – HelloToast : Manipuler les composants et les événements

---
### Réalisé par

**Abla MARGHOUB**

### Encadré par

**Pr. Mohamed LACHGAR**

### Module

**Techniques de Programmation Avancée**

### Établissement

**École Normale Supérieure - Université Cadi Ayyad**

---

## 1. Objectif du TP

 - Affiche un message Toast lors du clic sur un bouton.
 - Permet de saisir des informations personnelles (nom, prénom, ville, genre) et de les afficher sous forme de Toast.

---

## 2. Architecture technique

### 2.1 Stack technique

| Élément | Description |
|----------|-------------|
| **Langage principal** | Java |
| **IDE utilisé** | Android Studio |
| **Version Android minimale (API)** | 24 (Android 7.0 Nougat) |
| **Système de build** | Gradle |
| **Structure du layout** | XML (LinearLayout vertical) |
| **Ressources** | `strings.xml`, `array` de villes |
| **Composants UI** | `TextView`, `EditText`, `Spinner`, `RadioGroup`, `RadioButton`, `Button` |
| **Gestion des événements** | `setOnClickListener()` |
| **Affichage des messages** | `Toast.makeText(...).show()` |
| **Logs de débogage** | `Log.d()` |
| **Émulateur utilisé** | Android Virtual Device (AVD) ou smartphone physique |


### 2.2 Structure du TP

<img width="560" height="950" alt="image" src="https://github.com/user-attachments/assets/40c3d70d-e679-405e-b6f4-84a304ed64a3" />

## 3. Composants et fonctionnement de l’application

 ### 3.1 Interface (XML)
`activity_main.xml` définit la structure de l’écran :

Champs de saisie pour le nom, prénom, et sélection de la ville.

Boutons pour afficher un Toast et incrémenter le compteur.

Utilisation de LinearLayout pour un alignement vertical.

### 3.2 Logique (Java)
`MainActivity.java` contient :

Le lien entre l’interface graphique et le code (avec `findViewById()`).

La gestion d’événements avec `setOnClickListener()`.

L’affichage de messages via `Toast.makeText()`.

L’incrémentation du compteur et l’affichage dynamique dans un TextView.

### 3.3 Ressources (XML)
`strings.xml` contient les textes statiques et le tableau des villes utilisé par le Spinner.

---

## 4. Résultat attendu
### 4.1 Compilation et exécution

L’application s’exécute correctement sur un émulateur Android ou un téléphone réel.

<img width="908" height="911" alt="2" src="https://github.com/user-attachments/assets/f2a64481-b331-446a-a95b-c8edaf1f10e1" />

### 4.2 Interface de l’application

L’application affiche un formulaire simple permettant de saisir le nom, le prénom, la ville et le genre, puis un message Toast apparaît à la validation, confirmant les informations saisies par l’utilisateur.

<img width="357" height="632" alt="1" src="https://github.com/user-attachments/assets/3e4680e1-6146-40a2-9fc9-a7658943d715" />

## 5. Demonstration :

<video src="https://github.com/user-attachments/assets/58c80fe2-3d1e-453a-82be-568207ef16e1" controls>
</video>




