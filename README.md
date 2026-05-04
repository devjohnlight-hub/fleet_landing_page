# FleetTrack

Plateforme complète de gestion de flotte avec géolocalisation GPS en temps réel, gestion des chauffeurs, alertes intelligentes et reporting avancé.

## Stack technique

- **Framework** : [Next.js 14](https://nextjs.org/) (App Router)
- **Langage** : TypeScript
- **Style** : Tailwind CSS
- **Runtime** : Node.js

## Fonctionnalités

- **Géolocalisation temps réel** — Position, vitesse et état moteur mis à jour toutes les 5 secondes
- **Historique des trajets** — Relecture complète avec export des données
- **Alertes & Notifications** — Geofencing, excès de vitesse, expiration de documents
- **Gestion des chauffeurs** — Profils, documents, affectations et historique
- **Reporting & Analyses** — Export PDF, Excel et CSV
- **Sécurité** — JWT/OAuth2, chiffrement TLS, journal d'audit

## Installation

```bash
# Cloner le dépôt
git clone https://github.com/user/fleettrack.git
cd fleettrack

# Installer les dépendances
npm install

# Lancer en développement
npm run dev
```

L'application est accessible sur [http://localhost:3000](http://localhost:3000).

## Scripts

| Commande | Description |
|---|---|
| `npm run dev` | Serveur de développement |
| `npm run build` | Build de production |
| `npm run start` | Serveur de production |
| `npm run lint` | Vérification du code |

## Structure du projet

```
fleettrack/
├── app/
│   ├── auth/
│   │   ├── login/         # Page de connexion
│   │   └── register/      # Page d'inscription
│   ├── dashboard/
│   │   ├── tracking/      # Suivi en temps réel
│   │   ├── vehicles/      # Gestion des véhicules
│   │   ├── drivers/       # Gestion des chauffeurs
│   │   ├── history/       # Historique des trajets
│   │   ├── reports/       # Rapports & analyses
│   │   └── alerts/        # Alertes & notifications
│   ├── pricing/           # Page tarifaire
│   ├── docs/              # Documentation
│   └── page.tsx           # Landing page
├── components/            # Composants réutilisables
├── public/                # Assets statiques
└── tailwind.config.ts
```

## Tarifs

| Plan | Prix | Véhicules |
|---|---|---|
| Starter | 29 000 FCFA / mois | Jusqu'à 10 |
| Pro | 89 000 FCFA / mois | Jusqu'à 50 |
| Entreprise | Sur devis | Illimité |

Essai gratuit de 14 jours — Sans frais cachés — Résiliation à tout moment.
