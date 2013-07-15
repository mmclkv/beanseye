# What is beanseye ?

Beanseye is proxy and monitor for beansdb, written in Go.

# How to build

Install Go first, then 
``` bash
$ clone git@github.com:douban/beanseye.git
$ cd beanseye
$ make
```

# How to run 

prepare your configuration, according to conf/example.ini
``` bash
$ ./bin/proxy -conf=conf/example.ini
```

# Proxy

You can access whole beansdb cluster throught localhost:7905
as configured, by any memcached client.

# Monitor

There is a web monitor on http://localhost:7908/ at default.
