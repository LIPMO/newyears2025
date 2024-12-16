# Compte à Rebours Nouvel An 🎉

Ce projet est un site web moderne qui affiche :
- **L'heure actuelle en temps réel**.
- **Un compte à rebours jusqu'au Nouvel An**.
- Une **notification webhook Discord** lorsqu'une personne visite le site.

## 🛠️ Fonctionnalités

1. **Horloge en temps réel :** Affiche l'heure actuelle mise à jour chaque seconde.
2. **Compte à rebours jusqu'au Nouvel An :** Affiche les jours, heures, minutes et secondes restants avant minuit du 1er janvier.
3. **Notification Webhook Discord :**
   - Envoie un message automatique dans un canal Discord lorsqu'une personne visite le site.
   - Utilise un webhook Discord pour envoyer des requêtes HTTP POST.

## 🌈 Design Moderne

- **Fond animé en dégradé.**
- **Typographie élégante (Poppins via Google Fonts).**
- **Carte avec effet d'ombre et transparence.**

## 🚀 Comment utiliser

### 1. Héberger le site
Vous pouvez héberger ce projet sur n'importe quelle plateforme de serveur web statique, comme :
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

### 2. Configurer le Webhook Discord
1. Créez un webhook dans le canal Discord où vous souhaitez recevoir les notifications.
   - Allez dans **Paramètres du canal** → **Intégrations** → **Créer un Webhook**.
   - Copiez l'URL du webhook et remplacez-la dans le fichier `index.html` à la ligne suivante :
     ```javascript
     const webhookURL = "VOTRE_URL_WEBHOOK";
     ```
2. Hébergez le fichier et ouvrez-le dans un navigateur. Une notification sera envoyée à votre canal Discord chaque fois qu'une personne accède au site.

## 📄 Structure des fichiers

- `index.html` : Contient le code principal du site web.
- `README.md` : Documentation du projet.

## 🖥️ Technologies utilisées

- **HTML** : Structure du site.
- **CSS** : Mise en page et design moderne.
- **JavaScript** : Gestion de l'horloge, du compte à rebours et des notifications webhook.

## 📷 Aperçu du site

![Aperçu du site](https://via.placeholder.com/800x400.png?text=Aper%C3%A7u+du+compte+%C3%A0+rebours)

## ✨ Exemple de Notification Discord

![Notification Discord](https://via.placeholder.com/800x100.png?text=Exemple+de+notification+webhook)

## 🧑‍💻 Auteur

Créé avec ❤️ par **[Charles Baert]**.

## 📜 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, de le modifier et de le redistribuer.

