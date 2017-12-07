# Quick Start

```
$ git clone git@github.com:mochizukikotaro/template-rollup.git && cd $(basename $_ .git)
$ yarn

$ rollup -c --watch
# Access http://localhost:10001
```


# Heroku

```
$ heroku create {YOUR_APP}
$ heroku config:set NPM_CONFIG_PRODUCTION=false
$ git push heroku master
$ heroku open
```
