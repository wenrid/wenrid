![header](https://capsule-render.vercel.app/api?type=waving&color=0:0055FF,100:00CC99&height=200&section=header&text=Wenchel%20RIDORÉ&fontSize=40&fontColor=ffffff)

# 👋 Salut, je suis Wenchel RIDORÉ  

🎓 Je suis ingénieur logiciel et étudiant en Master Systèmes Intelligents et Multimédia à l'**International School**, l’**Université Nationale du Vietnam (VNU Hanoi)** et l’**Université de La Rochelle (France)**   

💡 Passionné par l’**Intelligence Artificielle**, la **Vision par Ordinateur** et la **Data Science**,  
j'aime concevoir des systèmes intelligents qui allient **innovation technologique** et **impact social**,  
notamment dans les domaines de l’**agriculture durable** et de la **santé numérique**.  

📜 Citation : *« Utiliser l’intelligence artificielle pour bâtir une agriculture plus saine, plus durable et plus humaine. »*

---

## 🚀 Projets majeurs

### 🌿 IA pour l’Agriculture saine et durable en Haïti  
**Système de Diagnostic Automatisé pour la Santé du Caféier et du Citronnier**

Développement d’un système d’analyse d’images basé sur YOLOv11 et OpenCV pour diagnostiquer les maladies du caféier et du citronnier..  
Les agriculteurs reçoivent des diagnostics instantanés avec des recommandations ciblées via une application web.

**Stack :** OpenCV, Python, IA & Vision par Ordinateur, Streamlit  
**Impact :** Amélioration de la productivité agricole grâce à la détection précoce et à la prévention ciblée des maladies 

🔗 [Voir le projet (à venir)](#)

---

### 🖼️ Image Captioning — Transfer Learning vs From Scratch
**Analyse comparative d'architectures de génération automatique de descriptions d'images**

Étude comparative de deux approches d'image captioning sur le dataset Flickr8k :
ResNet-50 préentraîné (transfer learning) vs CNN personnalisé entraîné from scratch.
Les deux architectures utilisent un décodeur LSTM avec mécanisme d'attention additive
de Bahdanau.

**Contributions clés :**
- Task A : Encodeur ResNet-50 (ImageNet) + LSTM + Attention → BLEU-4 = 0.0695
- Task B : Custom CNN 5 couches + GAP layer + LSTM → BLEU-4 = 0.0444
- Visualisations Attention Heatmaps et Grad-CAM pour interpréter les modèles
- Analyse approfondie : hallucinations, language prior, bottleneck effect

**Performances :** BLEU-4 ResNet-50 = 0.0695 · Gain transfer learning = +56,5%  
**Stack :** Python, PyTorch, ResNet-50, LSTM, Flickr8k  
**Impact :** Démonstration que le transfer learning est indispensable avec datasets limités

🔗 [Voir le projet (à venir)](#)

---

### 🚦 Classification des Panneaux de Signalisation Allemands — GTSRB
**CNN léger pour la reconnaissance de panneaux routiers en temps réel**

Conception et entraînement d'un réseau de neurones convolutif (CNN) pour classifier 
43 classes de panneaux allemands sur 51 839 images réelles. Le modèle intègre 
dropout, augmentation de données et visualisation des activations.

**Contributions clés :**
- Architecture CNN légère (549 355 paramètres) avec 2 blocs convolutifs + dropout
- Augmentation de données : rotation, variation de luminosité, zoom simulé
- Comparaison CNN vs HOG via t-SNE pour quantifier l'apport du deep learning
- Visualisation des heatmaps d'activation (Grad-CAM)

**Performances :** Précision validation = 99,44% · Précision test officiel = 95,62%  
**Stack :** Python, PyTorch, OpenCV, Matplotlib, Scikit-learn  
**Impact :** Modèle robuste et léger applicable aux systèmes embarqués de véhicules autonomes

🔗 [Voir le projet (à venir)](#)

---

### 📜 Numérisation Automatique des Actes de Naissance — RDC  
**Pipeline OCR end-to-end pour les documents administratifs manuscrits congolais**

Développement d'un pipeline complet de reconnaissance optique de caractères (OCR) 
spécifiquement adapté aux actes de naissance manuscrits de la République Démocratique 
du Congo. Le système transforme automatiquement une image scannée en document Word 
structuré exportable, avec extraction des 40 champs officiels du certificat.

**Contributions clés :**
- Construction d'un dataset annoté de 300 certificats
- Fine-tuning de LightOnOCR-2-1B sur le domaine spécifique RDC
- Post-correction par 40 règles regex adaptées à l'onomastique congolaise
- Interface Streamlit avec base SQLite et export Word

**Performances :** F1-Score = 93,7% · CER = 10,95% · Recall = 96,0%  
**Stack :** Python, HuggingFace Transformers, Streamlit, SQLite, python-docx  
**Impact :** Préservation du patrimoine documentaire 
de la RDC et modernisation de l'administration de l'état civil 

🔗 [Voir le projet](https://github.com/wenrid/ocr-actes-naissance-rdc)

---

### 🏥 Système de Suivi Médical Intelligent  
Plateforme complète de gestion de dossiers médicaux intégrant **4 modules d’IA** :  
- Prédiction du risque patient  
- Analyse épidémiologique par âge et localisation  
- Détection de foyers de maladies  
- Prévision de tendances sur 30 jours  

**Stack :** Django 5.1.4, TensorFlow, PostgreSQL, Chart.js  
**Impact :** Aide à la décision médicale et recherche en santé publique  

🔗 [Voir le projet (à venir)](#)

---

### ❤️ Analyse Prédictive des Maladies Cardiaques  
Développement de modèles de **Machine Learning** (régression logistique, réseaux de neurones)  
pour identifier les facteurs de risque sur un jeu de 918 patients.  
**Performance :** AUC-ROC = 0.925  

**Stack :** Python, Scikit-learn, TensorFlow, Pandas, Seaborn, Matplotlib  

---

### 🖼️ Segmentation Intelligente d’Images  
Pipeline complet en **6 étapes** combinant filtrage, segmentation HSV et analyse géométrique.  
Performance globale : **96% de réussite** sur 3 images complexes.  

**Stack :** Python, OpenCV, NumPy  
**Applications :** OCR, vision industrielle, imagerie médicale  

---

### 🤖 Simulation Multi-Agents – BFS avec GAMA  
Implémentation de l’algorithme **Breadth-First Search (BFS)** en environnement multi-agents  
pour la visualisation interactive d’algorithmes de recherche de chemin optimal.  

**Stack :** GAMA Platform, GAML  
**Applications :** Robotique, navigation GPS, IA pour jeux vidéo  

---

## 🧠 J’apprends actuellement

- 🚀 Optimisation et déploiement de modèles CNN pour périphériques edge  
- 🧩 Intégration d’agents conversationnels et chaînes d’IA avec **LangChain** et **LLMs**  
- ☁️ MLOps, Docker et déploiement sur le cloud  
- 📈 Analyse avancée des données et visualisation interactive  
- 🧠 Renforcement de mes compétences en cybersécurité appliquée à l’IA et aux systèmes web


## 🛠️ Compétences techniques

### 🧠 Intelligence Artificielle & Vision
![YOLOv11](https://img.shields.io/badge/-YOLO-00FFFF?style=flat-square&logoColor=black)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/-Transformers-FF6F00?style=flat-square&logo=huggingface&logoColor=white)
![OCR](https://img.shields.io/badge/-OCR-007FFF?style=flat-square&logoColor=white)
![Transfer Learning](https://img.shields.io/badge/-Transfer%20Learning-8B5CF6?style=flat-square&logoColor=white)
![ResNet-50](https://img.shields.io/badge/-ResNet--50-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CNN](https://img.shields.io/badge/-CNN-007FFF?style=flat-square&logoColor=white)
![LSTM](https://img.shields.io/badge/-LSTM-8B5CF6?style=flat-square&logoColor=white)
![Attention Mechanism](https://img.shields.io/badge/-Attention%20Mechanism-059669?style=flat-square&logoColor=white)
![Grad-CAM](https://img.shields.io/badge/-Grad--CAM-D97706?style=flat-square&logoColor=white)


### 📊 Data Science & Machine Learning
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-005571?style=flat-square)
![Seaborn](https://img.shields.io/badge/-Seaborn-4B8BBE?style=flat-square)
![Pillow](https://img.shields.io/badge/-Pillow-3776AB?style=flat-square&logo=python&logoColor=white)
![JiWER](https://img.shields.io/badge/-JiWER-059669?style=flat-square&logoColor=white)
![t-SNE](https://img.shields.io/badge/-t--SNE-005571?style=flat-square&logoColor=white)
![BLEU Score](https://img.shields.io/badge/-BLEU%20Score-059669?style=flat-square&logoColor=white)
![HOG](https://img.shields.io/badge/-HOG-4B8BBE?style=flat-square&logoColor=white)

### 💻 Développement & Bases de Données
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/-Gradio-FF6F00?style=flat-square&logo=gradio&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![python-docx](https://img.shields.io/badge/-python--docx-2B579A?style=flat-square&logo=microsoftword&logoColor=white)


### ☁️ MLOps & Outils
![Google Colab](https://img.shields.io/badge/-Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 💼 Expérience professionnelle

**Assistant IT Manager — Brasserie de la Couronne S.A (Coca-Cola Haïti)**  
*Sept. 2018 – Janv. 2019, Port-au-Prince*  
- Maintenance et support de 50+ postes informatiques  
- Administration réseau et serveurs Windows/Linux  
- Gestion bases de données MSSQL  

---

## 🎓 Formation académique

🎓 **Master en Système Intelligent et Multimédia (SIM)**  
*Université Nationale du Vietnam (VNU Hanoi) & Université de La Rochelle (France)*    

🎓 **Licence en Sciences Informatiques**  
*École Supérieure d’Infotronique d’Haïti*   

---

## 📜 Certifications

- 🔥 *[Deep Learning with PyTorch](https://coursera.org/share/fcd78314a45d5a239691d154de46d1f8)* — Coursera (2025)
- 🧠 *Python for Computer Vision with OpenCV and Deep Learning* — Udemy (2025)
- 🐍 *[Python for Machine Learning](https://www.udemy.com/certificate/UC-a60bb33a-d269-4364-92f7-566a038e6aee/)* — Udemy (2025)
- 📊 *[Data Manipulation](https://www.udemy.com/certificate/UC-045b7532-2567-4ae3-838d-d2a10cf9d793/)* — Udemy (2025)
- 🤖 *[Maîtriser les LLMs avec LangChain](https://www.udemy.com/certificate/UC-d1148540-d61e-46d4-8298-b7a031a61721)* — Udemy (2025)
- 🛡️ *Cybersécurité* — Udemy (2024
- 💼 *Entrepreneuriat et Gestion des PME* — 2018
- 🌐 *IT-Network* — 2017

---

## 🌍 Langues

🇭🇹 **Créole (natif)** | 🇫🇷 **Français (courant)** | 🇬🇧 **Anglais (intermédiaire)** | 🇪🇸 **Espagnol (intermédiaire)**  

---

## 📫 Me contacter

[![Email](https://img.shields.io/badge/-rwenchella@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rwenchella@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-Wenchel_RIDORÉ-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/wenchel-ridore-38632b169)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/wenrid)
[![WhatsApp](https://img.shields.io/badge/-+509_37_93_00_62-25D366?style=flat-square&logo=whatsapp&logoColor=white)](tel:+50937930062)

---

## 📊 Statistiques GitHub

![Stats](https://github-readme-stats.vercel.app/api?username=wenrid&show_icons=true&theme=tokyonight&count_private=true)
![Langages](https://github-readme-stats.vercel.app/api/top-langs/?username=wenrid&layout=compact&theme=tokyonight)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=wenrid&theme=tokyonight)

---


![footer](https://capsule-render.vercel.app/api?type=waving&color=0:00CC99,100:0055FF&height=120&section=footer)
