# Docker Newman
> Docker image to run postman collections.


![](example.png)

## Installation

The docker image for Newman is available for download from our docker hub. You must have Docker installed in your
system. Docker has extensive <a href="https://docs.docker.com/installation/" target="_blank">installation guideline for
popular operating systems</a>. Choose your operating system and follow the instructions.

> Ensure you that you have docker installed and running in your system before proceeding with next steps. A quick test
> to see if docker is installed correctly is to execute the command `docker run hello-world` and it should run without
> errors.

**Step 1:**

Pull the <a href="https://hub.docker.com/repository/docker/dmytrosh/docker-newman" target="_blank">newman docker
image</a> from docker hub:

```terminal
docker pull dmytrosh/docker-newman
```

### Run from this repository


**Step 1:**

Clone this repository:

```terminal
git clone https://github.com/DmytroSH/docker-newman.git
```

**Step 2:**

Run docker compose:

```terminal
docker-compose up
```


## Usage example

TBD


## Release History

* 0.0.1
    * Add base implementation + docs

## Contributing

1. Fork it (<https://github.com/DmytroSH/docker-newman>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request