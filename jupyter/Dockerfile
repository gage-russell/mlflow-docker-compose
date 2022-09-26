FROM jupyter/datascience-notebook:latest
# Install python packages
COPY requirements.txt /tmp
RUN pip install -r /tmp/requirements.txt
# Copy starter notebooks
ADD notebooks /home/jovyan/work/starter_notebooks
