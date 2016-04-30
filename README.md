Heroku buildpack: NodeJS
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of NodeJS without `package.json`.

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/dtaniwaki/heroku-buildpack-nodejs-without-package-json

# or if your app is already created:
$ heroku buildpacks:add https://github.com/dtaniwaki/heroku-buildpack-without-package-json

$ git push heroku master
```
