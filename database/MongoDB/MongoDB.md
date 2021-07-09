### use locally

* need to run mongodb server

```s
    $ sudo systemctl status mongodb
    $ sudo systemctl start mongodb
    $ sudo systemctl stop mongodb
```

* to store docs in specific location and run mongodb server locally

```s
    $ mongod --dbpath=[COMPLETE_PATH] --bind_ip 127.0.0.1

    $ mongod --dbpath=data --bind_ip 127.0.0.1
```