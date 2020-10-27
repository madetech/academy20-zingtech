# Academy 2020 - Bristol Team Final Project

This is a fictitious web app for a government department to manage basic HR tasks.

## Setting up a development environment

1.  Clone the repo:

```shell
$ git clone https://github.com/madetech/academy20-zingtech
$ cd academy20-zingtech
```

2.  Build the Docker image:

```shell
$ docker build -t hmrc-hr .
```

3.  Set up a new Docker container based on that image (make sure Docker is running first):

```shell
docker run -d -p 8080:80 --name hmrc-hr hmrc-hr
```

## Resources

We've relied on these resources:

- [Tutorial on the ReactJS.NET site](https://reactjs.net/getting-started/tutorial.html).
