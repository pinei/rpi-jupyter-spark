# rpi-jupyter-spark

An attempt to build a Docker image for running JupyterLab and PySpark with all dependencies pre-installed

## Running a default image for Jupyter Lab

```
docker run -it -p 10000:8888 --network host -e JUPYTER_ENABLE_LAB=yes jupyter/scipy-notebook
```

## References

- Docker images
  - [Stack do Jupyter para PySpark](https://github.com/jupyter/docker-stacks/blob/main/images/pyspark-notebook/)
  - [Base image raspberrypi4-64-python](https://hub.docker.com/r/balenalib/raspberrypi4-64-python)
  - [Alternative Jupyter image for raspberrypi3](https://github.com/kidig/rpi-jupyter-lab/)
- Recent tutorials
  - ...
- Old Tutorials
  - [How to set up PySpark for your Jupyter notebook](https://opensource.com/article/18/11/pyspark-jupyter-notebook)
