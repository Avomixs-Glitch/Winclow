<div align="center">
  <a href="https://winclow.com">
    <img src="https://res.cloudinary.com/dj0xpttv9/image/upload/f_auto,q_auto:eco,c_fill,w_1200,h_630/v1783182941/site/winclow-logo.png" alt="Winclow" width="680" />
  </a>

  <h1>Winclow</h1>
  <p><strong>Votre prochain jeu mérite le meilleur prix.</strong></p>
  <p>Plateforme de découverte, de veille et d’intelligence prix dédiée aux jeux vidéo.</p>

  <p>
    <a href="https://winclow.com"><img src="https://img.shields.io/badge/Accéder_à-Winclow-8B5CF6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Accéder à Winclow" /></a>
    <a href="#fonctionnalités"><img src="https://img.shields.io/badge/Produit-Price_Intelligence-0EA5E9?style=for-the-badge" alt="Price Intelligence" /></a>
    <a href="#statut-du-projet"><img src="https://img.shields.io/badge/Statut-En_production-10B981?style=for-the-badge" alt="En production" /></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=0B1120" alt="React 18" />
    <img src="https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Supabase-Postgres_%2B_RLS-3ECF8E?logo=supabase&logoColor=white" alt="Supabase" />
    <img src="https://img.shields.io/badge/Cloudflare-Edge-FF7139?logo=cloudflare&logoColor=white" alt="Cloudflare" />
  </p>
</div>

---

## Le problème

Trouver un jeu est facile. Savoir **quand l’acheter, sur quelle plateforme et à quel prix** ne l’est pas.

Les joueurs jonglent entre des boutiques, des promotions qui changent rapidement, des historiques de prix difficiles à lire et des catalogues impersonnels. Winclow rassemble ces signaux dans une expérience claire, premium et orientée décision.

> **Découvrir. Comparer. Suivre. Jouer au bon moment.**

## Winclow en une minute

Winclow est un produit web de nouvelle génération pour les joueurs qui veulent mieux explorer le marché : un catalogue éditorialisé, une intelligence prix multi-plateforme, des alertes personnalisées et un assistant de découverte contextuel.

| Pour le joueur | Pour la plateforme |
| --- | --- |
| Repère les meilleures opportunités, sans surcharge d’information. | Centralise catalogue, données marché, communauté et opérations. |
| Suit ses jeux favoris et reçoit les signaux réellement utiles. | Offre une administration complète pour faire évoluer le produit sans friction. |
| Découvre des titres adaptés à ses envies et à son budget. | S’appuie sur une architecture cloud sécurisée et évolutive. |

## Fonctionnalités

### Intelligence prix, sans bruit

- Comparaison des prix et des remises entre plusieurs boutiques et plateformes.
- Historique de prix, tendances, variations récentes et seuils personnalisés.
- Alertes de baisse de prix et opportunités de réduction centralisées.
- Visualisations de marché : comparatif, heatmap et indicateurs de mouvement.

### Découverte qui comprend le joueur

- Catalogue de jeux avec recherche rapide, filtres et fiches détaillées.
- Listes personnelles, favoris, collections publiques et profil joueur.
- Flux d’actualités et annonces liés aux jeux suivis.
- **CrackAI**, un assistant conversationnel configuré pour guider la découverte à partir du catalogue et des données marché.

### Expérience premium, pensée dans le détail

- Design sombre, cinématique et responsive — du mobile au grand écran.
- Synchronisation des préférences, favoris et notifications entre onglets.
- États de chargement, vide et erreur soignés pour une expérience fiable.
- Authentification sécurisée, gestion des rôles et espace d’administration.

### Un vrai back-office produit

- Gestion du catalogue, des liens boutiques, des utilisateurs et des abonnements.
- Pilotage des annonces, commentaires, signalements et activité.
- Paramétrage de l’apparence, du contenu SEO et de l’assistant IA.
- Tableaux de bord et analytique pour prendre des décisions informées.

## Architecture produit

<div align="center">
  <img src="assets/architecture.svg" alt="Architecture de haut niveau de Winclow" width="880" />
</div>

| Couche | Rôle |
| --- | --- |
| **Interface** | React, TypeScript, design system Tailwind et composants accessibles. |
| **Expérience** | Recherche, catalogue, watchlists, alertes, données prix et assistant de découverte. |
| **Services** | Authentification, base de données PostgreSQL, RLS, fonctions serverless et paiements. |
| **Edge & livraison** | Cloudflare pour le déploiement, les assets statiques et les protections de périphérie. |

## Principes de conception

**Une information utile doit mener à une décision.** Chaque écran privilégie les signaux actionnables : meilleure offre, évolution du prix, disponibilité, alerte ou prochaine découverte pertinente.

**La confiance est une fonctionnalité.** Les contrôles de rôle côté interface ne remplacent jamais les politiques de sécurité serveur. Les données sensibles et les opérations critiques restent protégées par les règles d’accès de la plateforme.

**Le produit reste humain.** L’IA assiste la recherche et l’explication ; elle ne remplace ni la transparence des prix, ni le choix du joueur.

## Stack

| Domaine | Technologies |
| --- | --- |
| Application | React 18, Vite, TypeScript |
| UI | Tailwind CSS, Radix UI, design system personnalisé |
| Données | Supabase, PostgreSQL, Row Level Security, Edge Functions |
| Identité | Clerk |
| État & données distantes | TanStack Query |
| Paiement | Stripe |
| Livraison | Cloudflare Workers & Static Assets |
| Médias | Cloudinary |

## Statut du projet

Winclow est un produit en évolution continue. Les grandes capacités déjà intégrées couvrent la découverte, le suivi de prix, les alertes, les comptes, la communauté, l’administration et l’intelligence de marché.

Les priorités produit évoluent selon les retours des joueurs : densification du catalogue, qualité des signaux prix, précision de la découverte et amélioration permanente de l’expérience.

## Démonstration & contact

<div align="center">
  <a href="https://winclow.com"><strong>Visiter winclow.com →</strong></a>
</div>

Pour une question produit, un partenariat ou une demande professionnelle, utilisez le formulaire de contact disponible sur la plateforme.

## Dépôt de présentation

Ce dépôt est volontairement **sans code applicatif**. Il présente le produit Winclow tout en protégeant son implémentation, ses configurations et ses actifs internes.

- Le code source, l’infrastructure et les secrets ne sont pas distribués ici.
- Les suggestions concernant cette présentation sont les bienvenues via les issues.
- Les marques et éléments visuels de Winclow restent la propriété de leurs titulaires.

## Mentions de marques

Winclow n’est ni affilié, ni approuvé, ni sponsorisé par Steam, Epic Games, GOG, PlayStation, Xbox, Nintendo, Clerk, Supabase, Stripe, Cloudflare ou toute autre marque citée. Ces noms appartiennent à leurs propriétaires respectifs.

<div align="center">
  <sub>Conçu pour les joueurs qui préfèrent jouer plus — et payer moins.</sub>
</div>
