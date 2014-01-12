docker-monnode
==============

[quarry/node](https://github.com/binocarlos/docker-node) + mon for keeping processes running

```
FROM quarry/node
RUN (mkdir /tmp/mon && cd /tmp/mon && curl -L# https://github.com/visionmedia/mon/archive/master.tar.gz | tar zx --strip 1 && make install)
```