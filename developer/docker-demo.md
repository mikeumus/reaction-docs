# Install Docker

Install Docker: <https://www.docker.com/products/docker>

# Go

## Quick Easy

But on the command line!
Open Terminal:

     docker run --name myreactiondemo -p 80:3000 -d reactioncommerce/reaction:latest
     docker logs myreactiondemo

this command is saying, run reactioncommerce/reaction, name this "myreactiondemo" for easier reference, and start on the localhost port 80.

Congrats, go to `http://localhost`

Docker logs will show you the container logs so you can grab the admin password. (once you get tired of this, read the docs..)

Stopping demo instance of Reaction

    docker stop myreactiondemo

## GUI

Install [kitematic](https://github.com/docker/kitematic).

Search Reaction, the CREATE either the "reaction" or "prequel" images.
