# Ground Tutorials

This repository contains the infrastructure and Dockerfile for the introductory Ground tutorials. The first tutorial walks users through a simple instrumented analytics scenario; the second tutorial walks users through debugging an unexpected change in a machine learning pipeline. The last exercise will show users how to build their own Aboveground application.

A compiled version of the Docker image is on Dockerhub. You can pull it by running `docker pull groundcontext/tutorial`. To start the image, run `docker run --rm --it -p 8888:8888 groundcontext/tutorial`.