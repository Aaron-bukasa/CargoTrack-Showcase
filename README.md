<div align="center">
  <img src="LIEN_IMAGE_MOCKUP_CARGOTRACK" width="100%" alt="CargoTrack Banner" />
</div>

<div align="center">
  <h1>🚚 CargoTrack - Logistics & Fleet Management</h1>
  <p>
    <strong>Solution Desktop complète pour la traçabilité des cargaisons et la coordination logistique.</strong>
  </p>
  
  <p>
    <img src="https://img.shields.io/badge/Electron-Desktop-blue?style=for-the-badge&logo=electron" />
    <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=nodedotjs" />
    <img src="https://img.shields.io/badge/Socket.io-Real_Time-010101?style=for-the-badge&logo=socketdotio" />
    <img src="https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma" />
  </p>
</div>

---

### 🔒 Note sur le Code Source
> **Ce projet est une application commerciale propriétaire.**
> Le code source n'est pas public pour des raisons de confidentialité client.
> Ce dépôt sert de documentation technique et de présentation de l'architecture.

---

### ⚡ Les Défis (The Challenge)

Le secteur logistique nécessite une coordination millimétrée. Le client avait besoin de **centraliser** des informations dispersées (chauffeurs, camions, statuts de livraison) sur une interface unique capable de gérer des mises à jour fréquentes sans rechargement.

**Solutions implémentées :**
* **Flux Temps Réel :** Intégration de **Socket.io** pour voir les changements de statut des cargaisons instantanément sur le dashboard, sans action de l'utilisateur.
* **Architecture Robuste :** Utilisation d'**Electron** pour offrir une expérience "logiciel bureau" stable, capable de gérer des tableaux de données massifs (DataGrids) sans ralentissement.
* **Intégrité des Données :** Modélisation complexe avec **Prisma** pour lier les Trajets, Véhicules, Chauffeurs et Marchandises.

### 🛠 Stack Technique Détaillée

| Composant | Technologie | Rôle |
| :--- | :--- | :--- |
| **App Shell** | Electron.js | Application native cross-platform |
| **Frontend** | React + Tailwind | Tableaux de bord dynamiques |
| **Real-time** | Socket.io | Communication bidirectionnelle Serveur/Client |
| **Backend** | Express + Node.js | API REST et logique métier |
| **Data** | PostgreSQL + Prisma | Base de données relationnelle |

### 📸 Aperçu des Fonctionnalités

| Dashboard Logistique | Suivi des Opérations |
| :---: | :---: |
| <img src="LIEN_IMAGE_1" width="100%"> | <img src="LIEN_IMAGE_2" width="100%"> |

*Note : Les images ci-dessus sont des maquettes ou des versions anonymisées.*

---

### 📬 Contact & Démo
Pour discuter de solutions logistiques ou voir mon code en action :
**[Visiter mon Portfolio](https://aaron-bukasa.netlify.app)** ou me contacter sur **[LinkedIn](https://linkedin.com/in/aaron-bukasa-bb84b42a0)**.
