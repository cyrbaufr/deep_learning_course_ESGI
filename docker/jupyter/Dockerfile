FROM jupyter/minimal-notebook:latest

# Time Zone France
ENV TZ=Europe/Paris

# Installation des librairies deep learning & ML
COPY requirements.txt /tmp/requirements.txt
RUN pip install --no-cache-dir -r /tmp/requirements.txt

# démarrage Jupyter sans token pour simplifier en local
CMD ["start-notebook.sh", "--NotebookApp.token="]