# Installation de Sherlock sur Debian

Pour installer Sherlock :

## 1 - Les dépendances python :
	virtual-environment (venv)
	pip

```
sudo apt install -y python3-venv python3-pip
```

## 2 - Installer Sherlock avec Git

```
sudo git clone https://github.com/sherlock-project/sherlock
```

entrer dans le répertoire et créer un environnement virtuel python

```
cd sherlock
python3 -m venv venv
```

Accéder à l'environnement virtuel
```
# Dans le repertoire où est stocké l'environnement virtuel (ici ~/sherlock/)
source ~/sherlock/venv/bin/activate
```

## Installer les librairies python nécessaire dans le v-env comme indiqué dans le readme sherlock
```
pip install -r requirements.txt
```

## Exécuter le script 
```
sherlock <pseudo>
```

## Pour sortir du v-env
```
exit()
# ou CTRL+D
```
