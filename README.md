`docker run -it <id>` provides way to interact with container where -i is for interactive and -t is for tty (terminal).

Alternatively, you can use the `docker start -a -i <id>` command.

To remove the stopped container `docker rm <id>`

To remove the stopped container images `docker rmi <id>`

To remove the all stopped container images `docker image prune`