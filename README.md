# Quick Start

```
$ git clone git@github.com:mochizukikotaro/template-rollup.git && cd $(basename $_ .git)
$ yarn

$ rollup -c --watch
# Access http://localhost:10001
```

![2017-12-07 11 25 26](https://user-images.githubusercontent.com/7911481/33695571-5e661e1c-db41-11e7-8ad1-08ffed0e962b.png)


# Heroku

```
$ heroku create {YOUR_APP}
$ heroku config:set NPM_CONFIG_PRODUCTION=false
$ git push heroku master
$ heroku open
```
