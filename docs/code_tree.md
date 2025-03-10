/src
├── app/
│   ├── core/                    # Services globaux, WebSocket, Auth
│   │   ├── services/
│   │   │   ├── chat.service.ts   # Communication avec le backend (WebSocket)
│   │   │   ├── auth.service.ts   # Gestion des utilisateurs
│   │   │   ├── api.service.ts    # Requêtes HTTP pour historique des chats
│   │   ├── models/
│   │   │   ├── message.model.ts  # Interface des messages
│   │   │   ├── user.model.ts     # Interface des utilisateurs
│   │   ├── guards/
│   │   │   ├── auth.guard.ts     # Vérifie l’authentification avant d’accéder aux chats
│   ├── shared/                   # Composants et utilitaires réutilisables
│   │   ├── components/
│   │   │   ├── chat-message.component.ts  # Affichage d’un message
│   │   │   ├── user-avatar.component.ts   # Affichage de l’avatar
│   │   ├── directives/
│   │   ├── pipes/
│   ├── features/
│   │   ├── chat/
│   │   │   ├── chat.page.ts       # Page principale avec les conversations
│   │   │   ├── chat.routes.ts     # Routes spécifiques au chat
│   │   │   ├── chat-input.component.ts  # Champ de saisie des messages
│   │   ├── auth/
│   │   │   ├── login.page.ts      # Page de connexion
│   │   │   ├── register.page.ts   # Page d'inscription
│   ├── app.routes.ts              # Gestion des routes principales
│   ├── app.component.ts           # Composant racine standalone
│   ├── main.ts                    # Bootstrap de l’application
│   ├── environments/               # Configurations (dev/prod)
