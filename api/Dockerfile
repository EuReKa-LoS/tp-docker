FROM python
# Dossier de travail APP dans API
WORKDIR /app
# # Copier les élements du dossier courant ./app
COPY . .
# COPY ./api/requirements.txt .
# Exposer le port 5000
EXPOSE 5000
# Installation des dépendances du fichier requirements.txt dans le dossier api
RUN pip install -r requirements.txt
# Démarrer la commande `flask run --host=[0.0.0.0]`
CMD ["flask", "run", "--host=0.0.0.0"]