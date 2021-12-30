# Space Travel
projet de site en sass 

## Pré-requis
- Avoir ruby d'installer sur le poste (https://www.ruby-lang.org/fr/)
- Avoir nodejs et npm d'instalmler sur votre poste (https://nodejs.org/en/)

## Initialisation du projet

- Initialiser le projet avec npm
    ```bash
    npm init
    ```
    Faite entrée à chaque ligne ou remplisser les infos.

- Installer sass
    ```bash
    npm install sass
    ```

- Reporter les modifications de sass dans le fichier style.css
    dans le fichier package.json écrire dasn la partie scripts:
    ```json
        "scripts": {
            "sass": "sass --watch ./main.scss:./style.css"
        },```

## Reprendre le projet depuis le dépot
- Cloner le projet sur github
    ```bash
        git clone git@github.com:StevenLignereux/spaceTravel.git
    ```
- Positionner vous dans le dossier du projet
    ```bash
        cd spaceTravel
    ```
    Puis lancer la commande npm install:
    ```bash
        npm install
    ```
    
## Lancer le projet

Pour lancer le projet faite la commande (a effectuer à chaque fois que vous reprenez le projet): 
```bash
    npm run sass
```

