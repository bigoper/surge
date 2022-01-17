# Surge.sh demo
I'll be using this repo to demo just a few of the different features and functionalities that `surge.sh` has to offer.

## Prerequisits
- git
- npm

# Surge
## Installation
```console
$ npm install --global surge
```
## Registration
You need to create an account in order to use `surge`.
It's free and it takes only a ~minute.
```console
$ surge
```
> run `surge` in your terminal, you'll be asked to register.

## Demos
In order to deploy the demos, you'll need to run `surge .` within each folder.  
Remember to replace the content of CNAME files with your own custom domains.

- [00-assets](./demos/00-assets/) - Serving static assets with CORS
- [01-basic](./demos/01-basic/) - Basic surge installation and deployment
- [02-not-found-404](./demos/02-not-found-404/) - Handling HTTP 404
- [03-spa](./demos/03-spa/) - SPA - Single Page Application
- [04-integration-circleci](./demos/04-integration-circleci/) - Integrating with CircleCI
