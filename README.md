#Dockerized Laravel App

This repository is a example of a dockerized Laravel application that has been created by following the [Shipping Docker](https://shippingdocker.com) course.

## Helper Commands

The helper scripts in ```./develop``` assume you are running this project on a windows machine, and use windows specific considerations such as double slashes for paths.

### Running Containers

```bash
./develop up -d
```

You can now view the hello world application at [localhost](http://localhost).

```bash
./develop down
```

### Run Artisan Commands

```bash
./develop artisan optimize
```

### Run Composer Commands

```bash
./develop composer require predis/predis
```

### Run NPM Commands

```bash
./develop npm install lodash
```

### Run Gulp Tasks

```bash
./develop gulp
```