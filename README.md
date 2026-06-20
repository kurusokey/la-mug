# ☕ la-mug

> Boutique en ligne de mugs et accessoires — objets du quotidien avec caractère.

![status](https://img.shields.io/badge/status-active-brightgreen) ![stack](https://img.shields.io/badge/stack-TypeScript%20%2B%20Next.js%20%2B%20Supabase-blue) ![visibility](https://img.shields.io/badge/visibility-public-lightgrey)

---

## Présentation

`la-mug` est la boutique e-commerce de la marque La Mug. Elle propose des mugs et accessoires du quotidien au design soigné, pensés pour les amateurs de café et de belles choses.

---

## Stack technique

| Couche | Technologie |
|---|---|
| Frontend | Next.js (App Router) |
| Langage | TypeScript |
| Base de données | Supabase (PostgreSQL) |
| Auth | Supabase Auth |
| Déploiement | Vercel |

---

## Installation locale

```bash
git clone https://github.com/kurusokey/la-mug.git
cd la-mug
npm install
np run dev
```

---

## Variables d'environnement

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_SUPABASE_URL` | URL du projet Supabase |
| `NEXT_PUBLIC_SUPABASE_ANON_KEY` | Clé publique Supabase |
| `SUPABASE_SERVICE_ROLE_KEY` | Clé service Supabase (admin) |
