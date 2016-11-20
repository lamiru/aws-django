AWS Django
===

Auto deployment project for Django using pyenv, uwsgi, nginx on AWS Amazon Linux.

## How to use

### Setup ssh configuration

```
Host project-prod-web
  Hostname XX.XXX.XXX.XXX
  User ec2-user
  IdentityFile ~/.ssh/XXXXXXXXXXX.pem
```
- Edit `SSH_HOST` in `/prod` if you need.

### Initialize

```
$ sh prod initialize
```

### Release

```
$ sh prod release
```

## How to access to public website

- Access to `http://[your domain]/robots.txt` to confirm nginx is running.
- Access to `http://[your domain]/admin` to confirm uwsgi is running.

## License

[The MIT License](https://opensource.org/licenses/MIT)
