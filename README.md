This is a docker container created for testing Flarum.

This container will create the myssql instance with the root password being **rootpass** (you have to modify the dockerfile to change it, the way it is now)

A database with the name **flarum** is created in the container.

When the web part of the installation runs, you have to use **127.0.0.1** instead of localhost, or it will fail.
