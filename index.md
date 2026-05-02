# Portfolio de Hammou Mohammed el Amine
### Développeur Systèmes Embarqués & Logiciel 🚀

Bienvenue sur mon espace dédié à l'ingénierie logicielle et à l'IoT. Je me spécialise dans la création de solutions robustes combinant matériel performant et interfaces intuitives.

---

## 🛠 Compétences Techniques
* **Langages :** C++ (Qt5), JavaScript (Electron), Python, Flutter.
* **Matériel & IoT :** ESP32, Arduino, bibliothèques graphiques LVGL.
* **Environnements :** Linux Mint, Docker, VSCodium.

---

## 📦 Bibliothèques Open Source

### 🔄 EncodeurRotatif (v2.0)
Une bibliothèque avancée pour la gestion d'encodeurs rotatifs quadrature, optimisée pour **ESP32** (utilisation de l'IRAM pour les interruptions) et compatible Arduino.

* **Points forts :** Accélération configurable, détection de clics (simple, double, long) et machine à états anti-rebond intégrée.
* **Licence :** MIT.
* [Voir le code sur GitHub](https://github.com/Aminehammou/EncodeurRotatif) <!-- Ajoutez votre lien ici -->

---

### 🔄 PCF_I2C_Expander (v1.1.0)
Une bibliothèque C++ pour Arduino, générique et performante, pour contrôler les extenseurs de port I2C PCF8574 (8 bits) et PCF8575 (16 bits).

* **Description :** Cette bibliothèque fournit une interface simple et efficace pour étendre le nombre d'entrées/sorties de votre microcontrôleur (Arduino, ESP8266, ESP32, etc.) en utilisant les populaires puces PCF8574 ou PCF8575.

Grâce à l'utilisation de templates C++, la même base de code gère de manière transparente les deux versions du composant, rendant votre code plus propre et facilement adaptable.
* **Licence :** MIT.
* [Voir le code sur GitHub](https://github.com/Aminehammou/PCF_I2C_Expander) <!-- Ajoutez votre lien ici -->

---

### 🔄 UIEncoderComponent (v2.0.0)
Classe de base abstraite pour les interfaces utilisateur contrôlées par encodeur rotatif sur microcontrôleurs.

Conçue pour les projets embarqués (ESP32, STM32, Arduino…) où l'interaction se fait via un encodeur rotatif (tourner + cliquer) plutôt qu'un écran tactile. Elle s'appuie sur la bibliothèque [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) pour le rendu graphique.

## Fonctionnalités 

- **Modèle de focus** : un seul composant actif à la fois, recevant les événements encodeur
- **Dirty flag** : redessin conditionnel — seuls les composants modifiés sont redessinés
- **Événements encodeur** : rotation (`handleEncoder`), clic court (`handleClick`), appui long (`handleLongPress`)
- **Activation/désactivation** : `enable()` / `disable()`
- **Géométrie** : `contains()`, `intersects()`, `setRect()`, `setPosition()`
- **Extensible** : une seule méthode obligatoire à implémenter — `drawInternal()`

* **Licence :** MIT.
* [Voir le code sur GitHub](https://github.com/Aminehammou/UIEncoderComponent) <!-- Ajoutez votre lien ici -->

---

## 🏗 Projets en Cours

### 🏭 SuperPlast-1
Projet de développement industriel intégrant des systèmes de contrôle embarqués.
* **Techno :** Python pour l'automatisation de la documentation technique.
* **Statut :** En développement actif.

### 🏠 Serveur Personnel & IoT
Expérimentation autour de **CasaOS** et **ZimaOS** pour la gestion de serveurs domestiques et le déploiement d'environnements isolés via **Docker**.

---

## 📬 Me contacter
* **GitHub :** [@Aminehammou](https://github.com/Aminehammou)
* **Localisation :** Hassi Bounif, Algérie