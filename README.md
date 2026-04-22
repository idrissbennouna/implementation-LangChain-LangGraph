# agenticaiLangchain LangGraph

Un projet Python expérimental basé sur LangChain et LangGraph pour explorer la création d'agents intelligents avec résultats vectoriels et recherche.

## Description

Ce dépôt contient une base pour développer des agents conversationnels et des workflows de traitement de données avec :

- `langchain` pour orchestrer les composants d'IA
- `faiss-cpu` pour l'indexation vectorielle
- `duckduckgo-search` pour la recherche Web
- `langgraph-checkpoint-postgres` pour la persistance des checkpoints
- `python-dotenv` pour charger les variables d'environnement

Le projet inclut également des notebooks (`agentic_ai_with_langchain_V3.ipynb`, `sma.ipynb`) pour expérimentation et démonstration.

## Installation

1. Cloner ce dépôt :

   ```bash
   git clone https://github.com/votre-organisation/agenticaiLangchain_LangGraph.git
   cd agenticaiLangchain_LangGraph
   ```

2. Créer un environnement virtuel Python 3.11+ :

   ```bash
   python -m venv .venv
   .venv\Scripts\Activate.ps1
   ```

3. Installer les dépendances :

   ```bash
   pip install -e .
   ```

## Usage

### Exécution du script principal

```bash
python main.py
```

Cela affichera :

```text
Hello from agenticailangchain-langgraph!
```

### Notebooks

- `agentic_ai_with_langchain_V3.ipynb` : expérimentation avec LangChain
- `sma.ipynb` : modèle et prototype de workflow

Ouvrir les notebooks dans Jupyter ou VS Code pour explorer les exemples.

## Configuration

Si vous utilisez des clés API ou des variables d'environnement, créez un fichier `.env` à la racine :

```env
OPENAI_API_KEY=...
DATABASE_URL=...
```

## Structure du dépôt

- `main.py` : point d'entrée principal
- `pyproject.toml` : configuration du projet Python et des dépendances
- `README.md` : documentation du projet
- `agentic_ai_with_langchain_V3.ipynb` : notebook LangChain


## Contribution

1. Forker le dépôt
2. Créer une branche de fonctionnalité
3. Ajouter ou modifier le code
4. Ouvrir une Pull Request

## Licence

À définir selon vos besoins (MIT, Apache 2.0, etc.).
