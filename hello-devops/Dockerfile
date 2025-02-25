# Utiliser une image Python 3.9 comme base
FROM python:3.9

# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier tous les fichiers du projet dans le conteneur
COPY . /app

# Installer les dépendances
RUN pip install -r requirements.txt

# Exposer le port 5000 (utilisé par Flask)
EXPOSE 5000

# Lancer l'application Flask
CMD ["python", "app.py"]
