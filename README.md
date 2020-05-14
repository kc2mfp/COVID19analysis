# COVID19analysis
My COVID19 analysis

# Start Docker Container
sudo docker run -d -p 8888:8888 --name Jupyter-COVID19 --restart unless-stopped -v /home/macmahon/jupyter/COVID19analysis/work:/home/jovyan/work jupyter/datascience-notebook
