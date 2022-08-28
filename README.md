# python-custom-vscode-dev-container
Customized and minimal VS Code remote container definition for python

## Pre-requisites 
The requirements to use this code is outlined primarily [here](https://code.visualstudio.com/docs/remote/containers#_getting-started). Please be sure to have the remote development extension installed [here](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack). 

## Dockerfile 

Python base images is obtained from [here](https://hub.docker.com/_/python/tags).  It is recommended to use `ctrl + shift+ p` and use the command palette to either reopen in container with or without cache. 

## Acknowlegements 

The author studied Microsoft devcontainer documentation and base python devcontainer environments. See [here](https://github.com/microsoft/vscode-dev-containers/tree/v0.245.0/containers/python-3/.devcontainer) for further reading.

# References 
- [Developing inside a Container](https://code.visualstudio.com/docs/remote/containers#_dev-container-features-preview)
- [Getting Started with Python 3 Dev Containers](https://medium.com/@dexterwilliams04/getting-started-with-python-3-dev-containers)
- [Technically Williams Python DevContainer](https://github.com/TechnicallyWilliams/vscode-remote-try-python/tree/master/.devcontainer)
- [Remote Try Python](https://github.com/microsoft/vscode-remote-try-python)
- [Creating a non-root user](https://code.visualstudio.com/remote/advancedcontainers/add-nonroot-user#)