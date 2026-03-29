#  AutoScanner Pro

AutoScanner Pro est une application web monolithique et 100% locale permettant de transformer des photos de documents, notes de cours ou brouillons en fichiers PDF nets, recadrés et binarisés. 

L'application s'appuie exclusivement sur des algorithmes de traitement de signal et de vision par ordinateur (mathématiques pures), sans aucune dépendance à l'intelligence artificielle ou à des serveurs distants. Vos données ne quittent jamais votre navigateur.

## 🎯 Fonctionnalités Principales

* **🕵️‍♂️ Recadrage Automatique :** Détection intelligente des contours de la page et correction de la perspective (déformation géométrique) grâce à l'algorithme de Canny.
* **🔲 Binarisation Adaptative :** Séparation parfaite du texte (noir) et du fond (blanc), même avec un éclairage inégal ou des ombres portées.
* **🧹 Destruction de Quadrillage :** Utilisation avancée de la morphologie mathématique pour repérer et effacer les lignes de cahier sans altérer l'écriture manuscrite.
* **🖱️ Glisser-Déposer (Drag & Drop) :** Réorganisation intuitive des pages numérisées avant l'export, optimisée pour le clic (PC) et le tactile (Mobile).
* **📑 Export PDF natif :** Redimensionnement intelligent et fusion des images traitées dans un document A4 standard.
* **🔒 Zéro Cloud / Zéro Serveur :** Tout le traitement s'effectue dans la mémoire vive de votre navigateur. Confidentialité absolue.

## 🚀 Utilisation

L'application est conçue pour être la plus légère et accessible possible :
1. Téléchargez le fichier `index.html`.
2. Ouvrez-le simplement avec n'importe quel navigateur web moderne (Chrome, Firefox, Safari, Edge).
3. Glissez-déposez vos images (JPG/PNG).
4. Activez ou désactivez la destruction de quadrillage.
5. Réorganisez l'ordre des pages si nécessaire.
6. Cliquez sur **Traiter et Télécharger** pour obtenir votre fichier PDF.

## 🛠️ Pile Technologique (Tech Stack)

* **Interface :** HTML5 Pur, JavaScript (Vanilla JS).
* **Style :** [Tailwind CSS](https://tailwindcss.com/) (via CDN).
* **Vision par Ordinateur :** [OpenCV.js](https://docs.opencv.org/4.8.0/opencv.js) (WebAssembly / JavaScript port).
* **Génération PDF :** [jsPDF](https://github.com/parallax/jsPDF) (via CDN).
* **Interactions :** [SortableJS](https://sortablejs.github.io/Sortable/) (pour un glisser-déposer fluide sur tous supports).

## 📈 Optimisation SEO

Le code intègre des balises meta enrichies, de l'Open Graph pour les réseaux sociaux, ainsi qu'un balisage **Schema.org (JSON-LD)** structuré spécifiquement pour le référencement naturel par les moteurs de recherche classiques et les IA (Type : `WebApplication`).

---
*Créé et pensé pour l'efficacité mathématique pure.*