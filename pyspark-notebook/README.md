# Customization made:

- Based on custom jupyter/scipy-notebook image with python 3.7.12, built as follows:

  1. Build jupyter/base-notebook with --build-arg PYTHON_VERSION=3.7
  2. Build jupyter/minimal-notebook based on the custom base-notebook
  3. Build jupyter/scipy-notebook based on the custom minimal-notebook

- Added Spark distribution from CDH-6.3.4
- Added pyspark==2.4.0


# Jupyter Notebook Python, Spark Stack

[![docker pulls](https://img.shields.io/docker/pulls/jupyter/pyspark-notebook.svg)](https://hub.docker.com/r/jupyter/pyspark-notebook/)
[![docker stars](https://img.shields.io/docker/stars/jupyter/pyspark-notebook.svg)](https://hub.docker.com/r/jupyter/pyspark-notebook/)
[![image size](https://img.shields.io/docker/image-size/jupyter/pyspark-notebook/latest)](https://hub.docker.com/r/jupyter/pyspark-notebook/ "jupyter/pyspark-notebook image size")

GitHub Actions in the <https://github.com/jupyter/docker-stacks> project builds and pushes this image to Docker Hub.

Please visit the project documentation site for help to use and contribute to this image and others.

- [Jupyter Docker Stacks on ReadTheDocs](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html)
- [Selecting an Image :: Core Stacks :: jupyter/pyspark-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-pyspark-notebook)
- [Image Specifics :: Apache Spark](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/specifics.html#apache-spark)
