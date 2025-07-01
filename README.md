# 🧠 Assistant Règles - Jeu de Société

Un assistant intelligent capable de répondre aux questions sur les règles d’un jeu de société à partir du manuel en PDF.

---

## 🎯 Objectif

Ce projet utilise l'IA pour :
- Extraire automatiquement le texte d’un manuel de jeu en PDF
- Indexer les règles avec FAISS pour des recherches rapides
- Générer des réponses claires à des questions de joueurs
- Afficher le tout dans une interface simple via **Gradio**

---

## 📦 Technologies utilisées

| Outil / Lib          | Rôle |
|----------------------|------|
| `PyPDF`              | Extraction du texte PDF |
| `SentenceTransformers` | Création d'embeddings (représentation vectorielle) |
| `FAISS`              | Indexation et recherche rapide de texte |
| `Transformers`       | Modèle de génération de texte |
| `Gradio`             | Interface utilisateur simple et interactive |

---

## 🚀 Lancer le projet

### 1. 📁 Préparer votre environnement

```bash
git clone https://github.com/ton-utilisateur/assistant-regles-jeux.git
cd assistant-regles-jeux
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate sur Windows
pip install -r requirements.txt
