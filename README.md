# GestiTicket – API REST de gestion de tickets
Projet réalisé en BTS SIO (option SLAM) – TP1 à TP3.
## Fonctionnalités
- API REST en PHP (architecture MVC, PDO)
- CRUD tickets, catégories, utilisateurs
- Authentification par jeton JWT (HS256), mots de passe hachés (bcrypt)
- Protection contre l'injection SQL (requêtes préparées)
## Technologies
PHP 8 · MySQL · Apache (WAMP) · Postman
## Installation
1. Cloner le dépôt dans `C:\wamp64\www\`
2. Exécuter les scripts du dossier `sql/` dans phpMyAdmin
3. Copier `api/config/Config.example.php` en `api/config/Config.php`
4. Renseigner vos identifiants MySQL et une clé `JWT_SECRET`
5. Tester : `http://localhost/gestiticket/api/tickets`
## Auteur
Callaghan VEILLARD – BTS SIO – Promotion 2025-2027
