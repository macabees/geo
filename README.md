# Geo
Displays the details of your network.

## geo (Project Info)
[Website](https://github.com/alexanderepstein/Bash-Snippets)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/geo/)

## Build image
`$ docker build -t macabees/geo:latest .`

## Docker Push
`$ docker push -t macabees/geo:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/geo -g`
(An alternative 1 [curl]:   `curl ifconfig.co/json | jq`)
(An alternative 2 [HTTPie]: `http ifconfig.co/json)

## Help
`$ docker run -it --rm macabees/geo help`
