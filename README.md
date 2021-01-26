# Analisi dati con R

Avviare il container docker all'interno della cartella ed accedere a Jupyter Lab

```bash
docker run -p 8888:8888 -e JUPYTER_ENABLE_LAB=true -v $(pwd):/home/jovyan/work jupyter/datascience-notebook
```