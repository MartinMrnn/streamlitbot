## Groupe:
    * Martin Morin

# Comment récupérer le code sur un pc et comment l'exécuter.

## 1. clone le repo

git clone https://github.com/MartinMrnn/streamlitbot.git

## 2. utiliser le chat bot

### a. ouvrir un terminal bash et faites

    cd streamlitbot

    python3 -m venv stenv

    pip3 install -r requirements.txt

    source stenv/bin/activate 

### b. utiliser l'API

- Créez un nouveu dossier .streamlit dans le projet streamlitbot

- Créez un nouveu fichier secrets.toml dans le projet .streamlit

- Copiez collez les lignes de code ci-dessous dans le fichier secrets.toml

    OPENAI_API_KEY = "YOUR_API_KEY"


### c. run le chatbot

    # with AI
    streamlit run chatbotgpt.py

    # whithout AI
    streamlit run chatbot.py


    