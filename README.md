# YouQuote - API de Gestion des Citations

![YouQuote](https://img.freepik.com/vecteurs-libre/illustration-api-design-plat_23-2149392285.jpg?t=st=1741688242~exp=1741691842~hmac=9392bfcff332a0e3d7d28801410dacacbc1226544fd9e94818ddd5641eaadcfc&w=900)

## Description
YouQuote est une API RESTful permettant de gérer des citations. Elle offre des fonctionnalités essentielles telles que la création, la lecture, la mise à jour et la suppression de citations (CRUD). De plus, elle propose des fonctionnalités avancées telles que l'obtention de citations aléatoires, le filtrage des citations en fonction de leur longueur, ainsi que le suivi de la popularité des citations les plus demandées.

L'API intègre également des fonctionnalités bonus comme la génération d'images pour les citations populaires et une authentification sécurisée permettant aux utilisateurs de gérer leurs propres citations.

---

## 🚀 Fonctionnalités Principales
- ✅ **Gestion des Citations (CRUD)** : Créer, lire, mettre à jour et supprimer des citations.
- 🔄 **Citations Aléatoires** : Obtenir une ou plusieurs citations aléatoires.
- 🎯 **Filtrage des Citations par Longueur** : Rechercher des citations en fonction du nombre de mots.
- 📊 **Suivi de la Popularité** : Enregistrement de la fréquence d'accès des citations pour identifier les plus populaires.

## 🎁 Fonctionnalités Bonus
- 🖼️ **Génération d'Images** : Création d'images contenant les citations les plus populaires.
- 🔐 **Authentification** : Gestion des utilisateurs avec JWT pour un accès sécurisé et personnalisé.

---

## 🛠️ Exigences Techniques
- **Framework** : Laravel
- **Base de Données** : MySQL 
- **Génération d'Images** : Intervention Image ou une bibliothèque similaire
- **Authentification** : JSON Web Tokens (JWT)
- **Déploiement** : Hébergement sur un serveur Linux via AWS EC2, Azure VM, ou DigitalOcean Droplet

---

## 📌 Installation et Configuration
```bash
# Cloner le projet
git clone https://github.com/abdelkouddousalami/YouQuote.git
cd youQuote

# Installer les dépendances
composer install

# Copier le fichier d'environnement et configurer les variables
cp .env.example .env

# Générer la clé d'application
php artisan key:generate

# Exécuter les migrations et seeders
php artisan migrate --seed

# Démarrer le serveur
php artisan serve
```

---

## 🚀 Déploiement
- L'API sera accessible via une URL sécurisée.
- Hébergement recommandé : AWS, Azure, ou DigitalOcean.
- Utilisation d'un serveur Linux avec une configuration adaptée à Laravel.

---

## 🎓 Modalités Pédagogiques
- **Travail individuel**
- **Durée** : 5 jours (du 10/03/2025 au 14/03/2025, 16h00)
- **Modalités d'évaluation** :
  - 🕐 5 minutes : Simulation de l'application web
  - 🕐 5 minutes : Code Review + Questions Techniques
  - 🕐 10 minutes : Mise en situation individuelle

---

## 📂 Livrables
- 📌 **Code source propre** (hébergé sur GitHub)
- 📌 **Conception UML**

---

## 📊 Critères de Performance
- ✅ Implémentation des Bonnes Pratiques pour CRUD en Laravel
- ✅ Validation des Données Entrantes
- ✅ Utilisation des Seeders et Factories pour les Citations
- ✅ Gestion Appropriée des Données Populaires

---

## 🤝 Contribuer
Les contributions sont les bienvenues ! Veuillez suivre ces étapes :
1. Forkez le projet 📌
2. Créez une branche feature (`git checkout -b feature-ma-feature`) 🔄
3. Commitez vos modifications (`git commit -m 'Ajout de ma feature'`) 💡
4. Pushez vers la branche (`git push origin feature-ma-feature`) 🚀
5. Ouvrez une Pull Request 📢

---

## 📧 Contact
Pour toute question, veuillez contacter [abdoalami.ru@gmail.com] ou créer une issue sur le dépôt GitHub.


