# To-do list intelligent
# 📸 Instagram - Task Manager & Notifications Studio

Une application web mobile optimisée (PWA) conçue pour simuler des notifications Push au style Instagram et gérer une To-Do List intelligente validée par l'IA Gemini.

---

## 🚀 Fonctionnalités

* **📋 To-Do List interactive** : Ajout, suppression et sauvegarde automatique des tâches dans le navigateur (`localStorage`).
* **🤖 Vérification par IA (Gemini API)** : Analyse des photos prises avec l'appareil du téléphone pour valider l'accomplissement d'une tâche (modèle `gemini-3.8-flash`).
* **🔔 Studio de Notifications** : Test et personnalisation complète de notifications style Web Push (titre, message, image, vibration, boutons d'action).
* **⚡ Service Worker** : Support complet des notifications sur mobile (Android Chrome).
* **🔒 Confidentialité** : Clé API et données stockées uniquement en local sur votre appareil.

---

## 🛠️ Configuration & Utilisation

1. **Obtenir une clé API Gemini** :
   * Rendez-vous sur [Google AI Studio](https://aistudio.google.com/).
   * Générez une clé API gratuite.
2. **Lancer l'application** :
   * Ouvrez l'application depuis votre navigateur web ou via GitHub Pages.
   * Entrez votre clé API dans le champ dédié en haut de page (elle sera sauvegardée automatiquement).
3. **Tester les notifications** :
   * Cliquez sur **« Autoriser les Notifications »**.
   * Accédez au **Studio de Notifications** pour envoyer des alertes de test.

---

## 🧰 Technologies utilisées

* **HTML5 / CSS3** (Interface sombre style Instagram)
* **JavaScript ES6+** (Modules ESM)
* **Google Gen AI SDK** (`@google/genai`)
* **Service Worker API** (`sw.js`)
* **HTML5 Canvas API** (Compression et redimensionnement d'images sur mobile)

---

## 📁 Structure du projet

```text
.
├── index.html     # Application principale (UI & Logique)
├── sw.js          # Service Worker pour la gestion des notifications
└── README.md      # Documentation du projet

'''




# Lien public : https://toyboy6.github.io/Test-notification/