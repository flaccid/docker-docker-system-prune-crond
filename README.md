# docker-system-prune-crond

:whale: Regularly run docker system prune under crond

## Usage

### Build

    $ docker build -t flaccid/docker-system-prune-crond .

### Run

    $ docker run \
        -it \
        --mount type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock \
          flaccid/docker-system-prune-crond

### Push

    $ docker push flaccid/docker-system-prune-crond
