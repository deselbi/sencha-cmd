[Docker](http://www.docker.com/) image to run [Sencha Cmd 5.1.0.26](http://cdn.sencha.com/cmd/5.1.0.26/release-notes.html).

## What's Inside

This image is based of [Java 8 JRE Image](https://hub.docker.com/_/java/)

* Sencha CMD 5.1
* Ruby 2.1

## 

## How to build this image


```shell
docker build -t dvc.sencha .
```

## How to use this image


Basic usage

```shell
docker run --rm -v "$(pwd)":/project deselbi/sencha-cmd [<options>]
```


To build an application on current directory

```shell
docker run --rm -v "$(pwd)":/project deselbi/sencha-cmd app build
```
