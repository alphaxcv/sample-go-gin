# Sample Application with Go and Gin

This sample is running on: https://go-gin.is-easy-on-scalingo.com/

## Deploy via Git

Create an application on https://scalingo.com, then:

```shell
scalingo --app my-app git-setup
git push scalingo master
```

And that's it!

## Deploy via One-Click

[![Deploy on Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://dashboard.scalingo.com/create/app?source=https://github.com/alphaxcv/sample-go-gin#main)


## Running Locally

```shell
docker-compose up
```

The app listens by default on the port 3000 or the one defined in the `PORT`
environment variable.
