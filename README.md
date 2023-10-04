# jupyter_docker_codespaces_template
A repository template for Jupyter Lab + Docker + Codespaces

## Getting started
1. Install docker (see for example https://docker-curriculum.com/ "Setting up your computer"). Launch docker and have it running
2. Clone a repo generated from this template. Make sure it has docker-compose.yml in the top directory
3. On command line, go to the repo directory and type 'docker compose up'
4. It will show a jupyterlab URL with a 'token'. Copy the token (but not the URL)
5. Open a browser and go to http://localhost:8800/lab
6. Type the token you copied
7. Jupyterlab will open under the docker environment
