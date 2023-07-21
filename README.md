# Zeomancer Data

This is the repository of Zeomancer Data, this repository provides the 
temperature JSON data that the [zeomancer_web](https://bitbucket.org/zatonovo/zeomancer_web/src/master/) repository use,
main purpose of this repository is .

Current link to website: https://zeomancer-data.netlify.app/
Check this Slite doc for repository details: https://zatonovo.slite.com/app/docs/8jHsd9CXlon0uo/Repositories

## Built With

* [Hugo](https://gohugo.io/)
* [Netlify](https://app.netlify.com/)

# Site Layout

Code in `src` overrides same file names in `themes/portio`

## Configuration Files

* src/config/\_default/config.toml
* For UAT - src/config/uat/config.toml

# Getting Started

To get a local copy up and running follow these simple example steps.

## Prerequisites

1. Docker (if you plan on just building and running Hugo through docker)
  1. You can refer to this site on [how to install docker on Linux](https://docs.docker.com/engine/install/ubuntu/)

## Setup

```
git clone git@github.com:charnelclamosa/zeomancer_data.git
```

## Run

Execute this command to build the Docker image, and run the image in a Docker container:

```
make build run
```

If you have issues with permissions, add `sudo` prior to the command.

Access the site at http://localhost:1313/

# Deployment

Deployment will be done through Netlify. Whenever you push changes to the master branch or a branch gets merged to master, it will trigger auto build and deploy.
Check this Slite doc for more information about deployment: https://zatonovo.slite.com/app/docs/qyiiHDsztYdyh5/Deployment

NOTE: We will transfer the deployment to Cloudflare soon.