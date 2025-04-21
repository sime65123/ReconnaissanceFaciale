
## Installation

1. Cloner le dépôt :
    ```bash
    git clone https://github.com/sime65123/ReconnaissanceFaciale.git
    cd face_recognition_project
    ```

2. Créer et activer un environnement virtuel :
    ```bash
    python -m venv venv
    source venv/bin/activate  # Sur Windows : venv\Scripts\activate
    ```

3. Installer les dépendances requises :
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

1. Préparer votre dataset :
    - Placez vos images dans le dossier `dataset`, organisées en sous-dossiers par nom de personne.

2. Enregistrer un nouveau visage :
    ```bash
    python add_faces.py
    ```

3. Lancer la reconnaissance faciale :
    ```bash
    python test.py
    ```

4. Marquer votre présence :
    ```bash
    python app.py
    ```

   

