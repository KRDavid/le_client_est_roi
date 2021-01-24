# Le client est roi

## 1 - Initialisation

### Prérequis

- Python 3
- Navigateur internet

### Installation

- Clonez le contenu du repository sur votre machine.
- Dans un terminal, rendez vous dans le dossier contenant les fichiers avec la commande suivante : ```cd <folder_path>/le_client_est_roi```
- Créez un environnement Python avec la commande suivante : ```pip install -r requirements.txt``` ou ```conda create --name <env_name> --file requirements.txt``` (avec Anaconda)

## 2 - Utilisation

- Dans le même terminal, lancez le serveur en tapant la commande ```python api.py```
- L'url http://localhost:5000/country renvoie la liste de tous les pays 
- L'url http://localhost:5000/country/France renvoie une recherche du pays demandé (France dans cet exemple)
- L'url http://localhost:5000/addcountry/<name> ajoute un pays à la base de donnée, les valeurs de densité et population sont aléatoires
- L'url http://localhost:5000/category/<1/2/3 ou 4> renvoie une tranche des pays présents dans la base, classés selon leur densité
