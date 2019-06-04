ARG BASE_CONTAINER=jupyter/base-notebook
FROM $BASE_CONTAINER

LABEL maintainer="Karron Qiu <karronqiu@gmail.com>"

RUN conda install --quiet --yes numpy PyYAML matplotlib sqlalchemy psycopg2 pandas sasl thrift thrift_sasl PyHive  &&\
    conda clean --all -f -y