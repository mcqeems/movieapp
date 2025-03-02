# Movie App based on TMDB API

## Introduction

A simple website for overviewing popular and featured Movies based on the realtime API from The Movies Database

## Installation

Make sure you have **Docker** to install it. if not you can install it right away by clicking here. [GET DOCKER](https://www.docker.com/)

1. Clone this repository.

```git
git clone https://github.com/mcqeems/movieapp
```

2. Build the App

```docker
docker build -t movieapp .
```

3. Run the Docker Container

```docker
docker run -p 8080:80 movieapp
```
