# Mon Premier Projet Git

Ce dépôt contient mes premiers scripts Python sous gestion de version Git.

## Description du Projet

Ce projet simple a été créé pour apprendre les bases de Git et GitHub. Il contient un script de salutation basique et une fonction utilitaire.

## Structure du Projet
mon_premier_projet_git/
├── script_salutation.py
└── utils/
└── helpers.py
└── .gitignore
└── README.md

## Installation

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/VOTRE_NOM_UTILISATEUR/mon_premier_projet_git.git](https://github.com/VOTRE_NOM_UTILISATEUR/mon_premier_projet_git.git)
    cd mon_premier_projet_git
    ```
    (Remplacez `VOTRE_NOM_UTILISATEUR` par votre nom d'utilisateur GitHub)

2.  **Créer et activer un environnement virtuel (recommandé) :**
    Si vous utilisez `uv` :
    ```bash
    uv venv
    source .venv/bin/activate # Sur macOS/Linux
    # Ou ./.venv/Scripts/activate # Sur Windows (PowerShell)
    ```
    (Nous verrons plus en détail la gestion des environnements virtuels dans une prochaine étape si vous le souhaitez)

## Utilisation

Pour exécuter le script de salutation :

```bash
# Assurez-vous d'être dans l'environnement virtuel si vous en avez un
python script_salutation.py