**DOCKER ARCHITECTURE:**

Docker uses a client server architecture.

Docker client talks to the Docker Daemon by using rest API .

Docker Daemon does the heavy lifting of building running and distributing containers.

Docker client and docker daemon can run on the same system as well as client can communicate with a remote daemon.

When someone use command like docker run Client send these commands to Docker Daemon which carries them out.
