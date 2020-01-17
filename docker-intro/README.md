# Docker Intro
This workshop it meant for people with basic or no knowledge at all about `Docker`.

It covers basic usage of `Docker` such as:
* Listing images / containers
* Creating snapshots
* Tagging images
* Mounting volumes
* Exposing ports

## Watching
The presentation was made using [Marp - Markdown Presentation Writer](yhatt.github.io/marp).

To watch it, simply run:
```
docker run --rm --init -v $PWD:/home/marp/app/ -p 80:8080 -p 52000:52000 marpteam/marp-cli -s .
```

