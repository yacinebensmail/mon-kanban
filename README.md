# 📋 KanbanRT - User Dashboard

Bonjour

Un tableau de bord sécurisé développé en React permettant la gestion d'utilisateurs avec un système d'authentification complet.

## 🔗 Liens du projet
- **Déploiement en direct :** [Colle ton lien Vercel ici, ex: https://mon-kanban-xyz.vercel.app]
- **Dépôt GitHub :** [Colle le lien de ton repo GitHub ici]

## 🛠️ Technologies utilisées
- **Frontend :** React.js, Vite, React Router DOM
- **Backend as a Service (BaaS) :** Supabase (PostgreSQL, Authentification)
- **Hébergement :** Vercel

## ✨ Fonctionnalités
- **Authentification :** Inscription et connexion sécurisées via Supabase Auth.
- **Protection des routes :** Redirection automatique si l'utilisateur n'est pas connecté.
- **Base de données en temps réel :** - Affichage de la liste des utilisateurs inscrits.
  - Ajout de nouveaux utilisateurs depuis le tableau de bord.
  - Suppression d'utilisateurs.

## 🚀 Installation en local
Pour faire tourner ce projet sur votre machine :

1. Clonez le dépôt :
\`\`\`bash
git clone [Colle le lien de ton repo GitHub ici]
\`\`\`

2. Installez les dépendances :
\`\`\`bash
npm install
\`\`\`

3. Configurez les variables d'environnement en créant un fichier \`.env.local\` à la racine :
\`\`\`text
VITE_SUPABASE_URL=votre_url_supabase
VITE_SUPABASE_ANON_KEY=votre_cle_publique_supabase
\`\`\`

4. Lancez le serveur de développement :
\`\`\`bash
npm run dev
\`\`\`