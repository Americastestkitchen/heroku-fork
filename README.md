# heroku-fork

Fork Heroku apps

## Installation

```console
$ heroku plugins:install https://github.com/heroku/heroku-fork.git
```

## Usage

```console
$ heroku fork -a example example-staging
Creating fork example-staging... done
Copying slug... done
Adding pgbackups:plus... done
Adding heroku-postgresql:dev... done
Creating database backup from example... .. done
Restoring database backup to example-staging... .. done
Copying config vars... done
Fork complete, view it at http://example-staging.herokuapp.com/
```

## License

MIT
