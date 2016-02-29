kinesalite-docker
========
Docker image of [kinesalite](https://github.com/mhart/kinesalite) which is a Node.js implementation of AWS Kinesis.

How to use this image
--------

```
docker run -d -p 4567:4567 takezoe/kinesalite
```

You can also specify the data directory by `-v` option:

```
docker run -d -p 4567:4567 -v `pwd`/kinesalite:/var/kinesalite takezoe/kinesalite
```
