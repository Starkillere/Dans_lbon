# 📚 Dans l'bon

> **Dans l’bon** est une application d’entraide entre étudiants, favorisant la collaboration et le partage de compétences académiques.

---

## 🚀 Objectif

Mettre en relation des étudiants selon leurs **compétences**, **besoins** et **proximité géographique**, pour réviser ensemble ou s’entraider avant un examen.

---

## 🧩 Fonctionnalités principales

- 🔐 Authentification (email / Google)
- 👤 Profils détaillés (niveau, matières maîtrisées)
- 🔍 Recherche intelligente d’étudiants
- 💬 Chat intégré en temps réel
- ⭐ Système d’évaluation après entraide
- 🔔 Notifications

---

## 🏗️ Architecture du projet

- **Frontend** : React + Tailwind CSS  
- **Backend** : FastAPI (Python) + PostgreSQL  
- **Auth** : JWT + OAuth2  
- **Infra** : Docker + Nginx  
- **Déploiement** : GitHub Actions / Render / Railway

---

## ⚙️ Installation

```bash
# Cloner le projet
git clone https://github.com/votre-nom/dans-lbon.git
cd dans-lbon

# Initialiser la structure
bash scripts/init_structure.sh

# Installer le backend
cd backend
pip install -r requirements.txt

# Lancer le serveur backend
uvicorn app.main:app --reload

# Installer et lancer le frontend
cd ../frontend
npm install
npm start

