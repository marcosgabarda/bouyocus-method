FROM jupyter/scipy-notebook:latest
COPY ./notebooks/ /home/jovyan/bouyoucus/
USER root
RUN chown -R jovyan /home/jovyan/bouyoucus/
USER jovyan