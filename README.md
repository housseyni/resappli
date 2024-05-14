# ResAppli

ResAppli est une application web développée en Django, dont le but est de créer un agenda interactif permettant de gérer des événements à l'aide de la bibliothèque FullCalendar. Avec ResAppli, vous pouvez ajouter, supprimer et modifier des événements facilement à travers une interface utilisateur conviviale.

## Fonctionnalités

- **Ajouter des événements** : Permet d'ajouter de nouveaux événements à l'agenda.
- **Modifier des événements** : Permet de mettre à jour les détails des événements existants.
- **Supprimer des événements** : Permet de supprimer des événements de l'agenda.
- **Affichage calendrier** : Utilise FullCalendar pour afficher les événements de manière intuitive et interactive.

## Prérequis

- Python 3.x
- pip (Python package installer)

## Installation

### Étape 1 : Cloner le dépôt

```bash
git clone https://github.com/housseyni/ResAppli.git
cd ResAppli
```


### Étape 2 : Installer les dépendances
```bash
pip install -r requirements.txt
```
### Étape 3 : Configurer la base de données

Appliquer les migrations pour configurer la base de données.
```bash
python manage.py migrate
```
### Étape 4 : Créer un superutilisateur

Pour accéder à l'interface d'administration de Django, vous devez créer un superutilisateur.
```bash
python manage.py createsuperuser
```
### Étape 5 : Lancer le serveur de développement

Démarrez le serveur de développement pour tester l'application localement.
```bash
python manage.py runserver
```
