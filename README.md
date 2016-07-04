AWS Django
===

Auto deploy project for Django using pyenv, uwsgi, nginx on AWS Amazon Linux.

## How to use

- Setup your ssh configuration.
- Edit `PROJECT_NAME` and `SSH_HOST` in `/deploy/deploy.conf` if you need.
- Run `prod` commands.

### Initialize

```
$ sh prod initialize
```

### Release

```
$ sh prod release
```

## License

[The MIT License](https://opensource.org/licenses/MIT)
