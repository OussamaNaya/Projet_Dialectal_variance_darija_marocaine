# 📌 Projet : Classification des Dialectes Darija Marocains  

## 📖 Description  
Ce projet vise à classifier les variantes régionales du dialecte marocain (Darija) en utilisant un modèle de deep learning basé sur **AraBERT**. Nous avons collecté des données textuelles à partir de vidéos YouTube provenant de plusieurs villes marocaines (**Casablanca, Agadir, Marrakech, Oujda, Tanger**) et les avons utilisées pour entraîner un modèle de classification.  

Le modèle résultant est intégré dans une application de chat développée avec **Django**, permettant d'identifier en temps réel l'origine géographique approximative du dialecte utilisé.  

![image](https://github.com/user-attachments/assets/472f59ad-492c-41eb-8a20-f4413bad4ece)


## 🚀 Fonctionnalités  
- **Collecte de données** : Extraction automatique des transcriptions de vidéos YouTube (**YouTube API, Selenium, BeautifulSoup**).  
- **Prétraitement** : Nettoyage, normalisation et annotation des dialectes.  
- **Fine-tuning d'AraBERT** : Adaptation du modèle pour la classification des dialectes marocains.  
- **Déploiement dans une application Django** : Intégration du modèle dans un chat en temps réel pour détecter la région linguistique.  

## 🛠️ Technologies utilisées  
- **Langage** : Python  
- **Framework NLP** : AraBERT  
- **Web Scraping** : YouTube API, Selenium, BeautifulSoup  
- **Développement Web** : Django  
- **Modèles de Deep Learning** : Transformers (Hugging Face)  

## 🔥 Installation et Exécution  
1. Clone le repo :  
   ```bash  
   git clone https://github.com/OussamaNaya/Projet_Dialectal_variance_darija_marocaine.git  
   cd Projet_Dialectal_variance_darija_marocaine  
   ```  
2. Installe les dépendances :  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Lance l'application Django :  
   ```bash  
   python manage.py runserver  
   ```  

## 📌 Auteurs  
- **NAYA OUSSAMA** – Développement & NLP  
- **Collaborateurs :**  BOUCHAMA TOUHAMI 

