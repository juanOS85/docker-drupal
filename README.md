# Docker template for WordPress projects

* This repo template is meant to be forked for Drupal projects.
* Drupal files should be placed on `./drupal` directory.

## Development

### Build

```
$ docker-compose -f base.yml -f dev.yml up -d
```

### Stop containers

```
$ docker-compose -f base.yml -f dev.yml stop
```

## Production

### Build

```
$ docker-compose -f base.yml up -d
```


### Stop containers

```
$ docker-compose -f base.yml stop
```