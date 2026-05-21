#  KanbanRT - User Dashboard

Bonjour

Un tableau de bord sécurisé développé en React permettant la gestion d'utilisateurs avec un système d'authentification complet.

##  Liens du projet
- **Déploiement en direct :** https://mon-kanban-btjpyvlrs-yacinebensmails-projects.vercel.app
- **Dépôt GitHub :** https://github.com/Yacinebensmail/mon-kanban.git

##  Technologies utilisées
- **Frontend :** React.js, Vite, React Router DOM
- **Backend as a Service (BaaS) :** Supabase (PostgreSQL, Authentification)
- **Hébergement :** Vercel

##  Fonctionnalités
- **Authentification :** Inscription et connexion sécurisées via Supabase Auth.
- **Protection des routes :** Redirection automatique si l'utilisateur n'est pas connecté.
- **Base de données en temps réel :** - Affichage de la liste des utilisateurs inscrits.
  - Ajout de nouveaux utilisateurs depuis le tableau de bord.
  - Suppression d'utilisateurs.

##  Installation en local
Pour faire tourner ce projet sur votre machine :

1. Clonez le dépôt :
\`\`\`bash
git clone https://github.com/Yacinebensmail/mon-kanban.git
\`\`\`

2. Installez les dépendances :
\`\`\`bash
npm install
\`\`\`

3. Configurez les variables d'environnement en créant un fichier \`.env.local\` à la racine :
\`\`\`text
VITE_SUPABASE_URL=: https://dgqtyyydjfpithbutzuf.supabase.co/rest/v1/
VITE_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImRncXR5eXlkamZwaXRoYnV0enVmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzkzNDc2NzcsImV4cCI6MjA5NDkyMzY3N30.ygB27oCgJLETGNFdcPGCOFDaw6rJmVVCGQCAEfs8yiA
\`\`\`

4. Lancez le serveur de développement :
\`\`\`bash
npm run dev
\`\`\`