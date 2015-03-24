npm install -g node-env

in the node-core folder:

- docker run of the image published on the hub
- exposes commands to the docker container for example

node-env up *to start the Docker container*
node-env up --path "path to the node-core folder"
node-env test *to trigger make test on the Docker container via ssh*
node-env compile *to trigger the compilation on the Docker container via ssh*
