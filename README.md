# Docker compose file for h5p running in Moodle

## Running

1. Install [Docker Engine](https://docs.docker.com/engine/installation/) and [Docker Compose](https://docs.docker.com/compose/install/).
2. Clone this repository, and clone the [h5p moodle plugin](https://github.com/h5p/h5p-moodle-plugin) repository.
3. Edit [docker-compose.yml](https://github.com/tajakobsen/docker-compose-h5p-moodle/blob/131d7e302a34ddb13c79ac3fcc63a093684118b5/docker-compose.yml#L18) so that the volume points to the _moodle plugin_
4. Run with [docker-compose](https://docs.docker.com/compose/)

```bash
docker-compose up
```
