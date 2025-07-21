# 🤖 Agent IA Support Client / SAV

Ce projet est une plateforme simple et intelligente qui permet aux utilisateurs de poser des questions de type service client (SAV, activation, panne…) et d'obtenir des réponses instantanées via un agent IA connecté à OpenAI et une base de connaissances Airtable.

## 🚀 Objectifs

- Automatiser les réponses aux questions clients avec l'IA (GPT)
- Permettre l'interaction via une interface web responsive (Bootstrap)
- Gérer la base documentaire via Airtable (FAQ)
- Stocker les échanges utilisateur (via Supabase ou Google Sheets)

---

## 🛠️ Stack technique

- 🧠 **OpenAI API** pour générer les réponses contextuelles
- ⚙️ **n8n** pour orchestrer les flux (Webhook, API, traitement logique)
- 📋 **Airtable** pour gérer la base de FAQ
- 🌐 **Bootstrap + JS** pour l’interface utilisateur
- 🧾 (Optionnel) **Supabase / Sheets** pour historique

---

## 📂 Structure

| Dossier           | Contenu |
|------------------|---------|
| `frontend/`       | Interface HTML + Bootstrap |
| `n8n-workflows/`  | Fichiers JSON exportés depuis n8n |
| `data/`           | Base FAQ, exports ou données |
| `docs/`           | Présentation, livrables, screenshots |
| `.gitignore`      | Pour ignorer fichiers sensibles |
| `README.md`       | Présentation du projet |
